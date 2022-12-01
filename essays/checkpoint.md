---
layout: essay
type: essay
title: "Checkpoint Assignment #3"
# All dates must be YYYY-MM-DD format!
date: 2022-11-30
published: true
labels:
  - MIS
  - Learning
---

<b> Show what each page will look like. The pages do not have to be “functional” but the design should clear. </b><br>
Click <a href="https://youtu.be/-0zsVEb-OMs">here</a> to view my screencast.<br>
<b> Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart. </b><br>
Our site’s shopping cart will be a separate page that the user can view and edit. We will do this by putting a “My Cart” button on the right side of our navigation bar. Our shopping cart page will allow users to add and remove quantities of the products in their cart. In addition to that, they will also be allowed to remove a product from their cart completely. We will also need the appropriate checks done here (e.g.: can’t enter an invalid quantity). On this page will also be a checkout button. If they are not logged in, they will be redirected to the login page. The user will then have access to their invoice once login is successful. <br>
We now have 3 product pages (iPhones, iPads, and Mac). While users shop the site and add items from these different pages, all products should still transfer over to the same shopping cart. We will use sessions to store the quantities of each product in the shopping cart. <br>
<b> Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session. </b><br>
We will use sessions to manage our shopping cart. Our code for this will follow the following format: USER: Product, Quantity, Series.
A more specific example:<br> "username":[ { "name": "iPhone 14 Pro", "price": 999, “series”: “iPhone” }, { "name": "iPad Pro (11-inch)", "price": 799,  “series”: “iPad”}, { "name": "Macbook Pro (14-inch)", "price": 1999, “series”:”Mac”} ] <br>
Similar to what we discussed in class, we can use something like request.session.shopping_cart to store the shopping cart data in the session on the server. That way, products that were added to the cart will remain there even when the user is switching between pages on the site. <br>
<b> How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address? </b><br>
We will avoid access to our application when a user has not logged in or registered by checking to see if our logged in status is true or false and if a cookie exists for the user. A user will be able to complete their purchase if their logged in status is true and there is a cookie that exists. A particular security concern could be if someone were to manually type in the URL with a valid username. However, for Assignment 3, we are no longer saving the user’s ID in the query string. Instead, it will be through sessions and cookies which can eliminate that concern. However, this may possibly pose a new security concern, being that cookies can be manipulated or forged. <br> 
<b> Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary). </b><br>
We have already provided personalization in our UI in Assignment 2 by addressing customers by their name when they login, providing the last time they logged in, and how many times they have logged in. We plan to add personalization in Assignment 3 by including the number of items a user has in their cart, and possibly having a pop up cart/message appear every time an item is added. <br>
<b> If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when? </b><br>
We split up the work by giving clear assignments to each person. We assigned the roles specifically so that what one person is working on will not conflict with something that the other person is working on at the same time. For example, if I am working on password encryption and sending emails for completed invoices, it should not interfere with my partner if she is working on personalization aspects. I also think we should have personal deadlines for certain tasks so that it helps us stay on track and hopefully have things done in a more timely manner. <br>
<b> How are you approaching Assignment 3 differently than Assignment 2? </b><br>
We are approaching Assignment 3 differently than Assignment 2 by being more organized this time around. Since we now have a better idea of what it’s like to work with a partner, we know what works best for us. For Assignment 3, we are making sure to assign responsibilities that do not coincide with what the other person is working on. Creating a prototype was also really helpful so that we can visualize our site before actually building it. This way, we are on the same page of how we want everything to work. Additionally, I think it would be a good idea for us to ask and go in for help sooner rather than later when we really need it. <br>
