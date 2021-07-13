# Fun Days
## CS50 Final Project 2021
### Video Demo: https://youtu.be/d0wfrTYUgMQ
### How everything began:
#### In the begining of January another lockdown was implemented in Portugal and online classes restarted. This time I decided I was really going to spend my time wisely. I had already heard about CS50x about a year before then. Although I had watched some of the first lectures and I had loved it, I never explored it any further. However, I decided that I was going to take CS50 course in my free time and finally learn programming, and so I started. It was extremely rewarding to know I was learning something new and important that was not only fun and exciting but also useful. I am forever grateful for CS50x!
### Final Project Idea:
#### After realizing what I could do in my free time during quarantine I had the idea of creating a website that would guide other kids and teens to use their free time as best as possible. I had the idea of creating Fun Days where my goal is to help kids, teens, adults and really anyone to try something new to create memories and really explore their full potencial and who knows they might find something they are really passionate about. Just as I did!
### Fun Days Description:
#### On this website I wanted to encourage people to try new things and explore new activities they never tried. Through some questions this web application suggests you some activities to try, perhaps learn programming, making a special dish or inventing your own story. My ultimate goal is to help people realize how many things they could do instead of watching TV or social media and to engage in new activities that make them happy.
### Implementation:
#### For this website I used Flask's framework. I began with the idea of using and external IDE to develop Fun Days. However, the process was really slow and so I decided to use CS50 IDE for my Final Project. 
### Files:
- **application.py** is the only python file. It makes the conections between the .html files and contains all the logic needed.
- **templates** stores all the .html files
  - **layout.html** - to avoid repetition every other .html file extends this one;
  - **index.html** - Homepage;
  - **suggestion.html** - after choosing the activity preferences and pressing the "Go" button on index.html the user is redirected to here where suggestions of activities will appear;
  - **random.html** - if the "Select Random activity" button is pressed from suggestions.html the user is redirected to here and one randomly choosen activity is displayed;
  - **explore.html** - a page with all the activities on activities.csv;
  - **why.html** - has a small extract of a Forbes article about the relationship between hapiness and free time (https://www.forbes.com/sites/hbsworkingknowledge/2021/02/05/want-to-be-happier-make-more-free-time/?sh=69868f315c0d);
- **static**
  - **styles.css** - all the CSS programming;
  - images
- **activities.csv** - this is the file that stores all the information about each activity. Each activity has: Name,age,people,place,time,image,description
  - the age, people, place and time of the activities are represented by 0, 1, 2 or 3. Each number is associated with a different value of the dropdown menu (ex. time: 0 - A lot, 1 - One day, 2 - Less than 4 hours, 3 - Less than 1 hour). I chose this aproach because it makes it much easier to manage this information and use it in loops and compare values (<, =, >).

##### Final toughts:
###### I am very happy with the final result of Fun Days. Even tough it was hard and there were few details I couldn't improve, I am impressed with how much I learned in such a short period of time. **Thank you CS50x!!!**
