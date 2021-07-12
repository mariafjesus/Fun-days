# Fun Days
## CS50 Final Project 2021
### Video Demo: https://youtu.be/d0wfrTYUgMQ
### How everything began:
#### In the begining of January another lockdown was implemented in Portugal and online classes restarted. This time I decided I was really going to spend my time wisely. I had already heard about CS50x about a year from then. Although, I had watched some of the first lectures and I loved it, I never explored anything more. However, I decided that I was going to take CS50 course on my free time and finally learn programming, and so I started. It was extremely rewarding to know I was learning something new and important that was not only fun and exiting but also useful. I am forever grateful for CS50x!
### Final Project Idea:
#### After realising what I could do in my free time during quarantine I had the idea of creating a website that would guide other kids and teens to use their free time as best as possible. I had the idea of creating Fun Days where my goal is to help kids, teens, adults and really anyone to try something new to create memories and really explore their full potencial and who knows they might find something they are really passionate about. Just as I did!
### Fun Days Description:
#### On this website I wanted to encourage people to try new things and explore new activities they never tried. Through some questions this web application suggests you some activities to try, perhaps learn programming, making a special dish or inventing your own story. My ultimate goal is to help people realise how many things they could do instead of watching TV or social media and to engage with new activities that make them happy.
### Implementation:
#### For this website I used Flask's framework. I began with the idea of using and external IDE to develop Fun Days, however, the process was really slow and so I decided to use CS50 IDE for my Final Project. 
### Files:
- **application.py** is the only python file. I makes the conections between the .html files and all the logic needed is there.
- **templates** stores all the .html files
  - **layout.html** - to avoid repetition every other .html file extends this one
  - **index.html** - Homepage
  - **suggestion.html** - after choosing the activity preferences and pressing the "Go" button on index.html the user is redirected to here where suggestions of activities will appear
  - **random.html** - after pressing the "Select Random activity" from suggestions.html the user is redirected to here and one randomly choosen activity is displayed
  - **explore.html** - a page with all the activities on activities.csv
  - **why.html** - has a small extract of a Forbes article about the relationship between hapiness and free time (https://www.forbes.com/sites/hbsworkingknowledge/2021/02/05/want-to-be-happier-make-more-free-time/?sh=69868f315c0d)
- **static**
  - **styles.css** - all the CSS programming
  - images

##### Final toughts:
###### I am very happy with the final result of Fun Days. Even tough it was hard and there were few details I couldn't perfect, I am impressed with how much I learned in such a short period of time. **Thank you CS50x!!!**
