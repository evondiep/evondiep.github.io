---
layout: essay
type: essay
title: "E6: Reflecting on Assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2022-12-18
published: true
labels:
  - MIS
  - Learning
---

<b> Briefly describe your system (e.g. A store selling Pokemon game cards) </b><br>
Our website sells different models of iPhones, iPads, and Macs. There are 3 product pages (one for each series), with 6 products on each page. Users will be able to view and add products to their cart without having to login. However, logging in is required for checking out. Information will also be maintained if the user leaves the site and comes back (as long as it does not pass the time the cookie/session expires). <br>
<b> Any notable shortcomings, bugs, problems, or additional features not implemented? </b><br>
I think our website came out really well. I don’t feel as if there were any major issues. However, a possible notable shortcoming that my partner brought up was that an admin would have to manually type “true” and “yes” to delete a user. I personally don’t have an issue with this method, but I’m sure there are more intuitive ways to go about the admin page. <br>
<b> Describe what you are most proud of about your system: </b><br>
I am most proud that we got the main components working smoothly. I thought it was really cool that our website resembles a real ecommerce website quite well. I also liked that our UI design was very clean and easy to use. <br>
<b> Describe what you are least happy with your system: </b><br>
Something I am least happy about with our system is the organization of our code. While it works, it would’ve been nice if we could’ve done it in a more concise and easy to read way. A lot of it had to do with creating everything on the server, which I think is beneficial a lot of the time. However, having long strings in the server makes it harder to read and edit. Towards the end of our project, we figured out a way to make our pages as .html files and then route it to the server by calling the file. If we figured this method out sooner, I think we could have made our code cleaner so that it would have been easier for us to read and edit. <br> 
<b> How was developing this assignment different than assignment #2? </b><br>
Developing this assignment was different than Assignment #2 because this time we had to maintain things using cookies and sessions. This brought a more realistic feel to the site since users could now maintain their login and cart even if they leave the site for a short period of time and come back. It was also trickier having to deal with 3 different product pages and having items update in the cart properly. <br>
<b> When you ran into a problem, what did you do to address it? </b><br>
When we ran into a problem, we often used a lot of console.logs to pinpoint exactly where the issue was being caused. We also reached out to our classmates for help at certain times which was really helpful. Additionally, we googled a lot of the problems we ran into. I found Stack Overflow and YouTube videos particularly helpful. <br>
<b> Describe what worked well in doing this assignment? </b><br>
Something that worked well doing this assignment was having clear roles/assignments while working on a team. We made it clear who was responsible for getting different parts done and organized it in a way where we could work parallel to each other so that it was more efficient. I felt that my partner and I had good communication which was really helpful. <br>
<b> Describe what did not work well in doing this assignment? </b><br>
Something that did not work well during this assignment was anticipating the time it would take to implement certain things. Even though we tried to give ourselves a good amount of time to complete a task, some things ended up taking longer than we expected. I also never pushed the code that I worked on so that we could avoid any mixups. Instead, I would copy over the code I worked on so that my partner could paste it in the respective sections, then she would push the code. This system worked fine for us, but it was still a bit time consuming since our code was very long. I had to keep track of what I wrote and where I wrote it so that I could tell my partner. <br>
<b> What did you learn from doing this assignment? </b><br>
This assignment gave me a really good understanding of how cookies and sessions work together to help sites maintain certain things. I also felt I learned a lot of patience and perseverance through this assignment (and class) overall. <br>
<b> If you could go back in time and do things differently, what would you change? </b><br>
If I could go back in time and do things differently, something I would have changed was to have set “mini” deadlines for each of the requirements. That way, we would’ve had certain things done at certain times, which would’ve helped things be completed in a more timely manner. It also would have been nice if we could have formatted the content of the email to be nicer. However, we ran into a bit of a time crunch towards the end of the project. <br>
<b> Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging </b><br>
I believe we spent about 10% of the time thinking how to do something, 45% of the time coding, and 45% of the time testing and debugging. <br>
<b> Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”) </b><br>
I would assign my partner (Deborah Yuan) 55% and myself 45%. I worked on sending the emails, security portions such as password encryption and cookies to log a user out when appropriate, and personalization portions such as displaying a user’s name and the number of items in their cart. I also worked with sessions and cookies to maintain the last product page visited by a user so that they would be redirected to it when appropriate. My partner worked on the active user cookies, shopping cart sessions, and shopping cart and admin pages. She also worked on parts of security and personalization (e.g., using cookies/sessions to block checkout if a user is not logged in, being able to logout without checking out). Additionally, she implemented a ratings feature. <br>
