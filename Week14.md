# Week 14

This week was self guided learning, so I used this week to further improve my project. Here is what I did.

### Login System

This week I introduced my login and registration system.

<img src="https://raw.githubusercontent.com/travisbyr/SDV602-Blogs/main/Documentation%20Images/login.PNG">



I did this by creating a separate GUI that would open when the application runs. This GUI would ask the user to enter their login details or to register an account.

<img src="https://raw.githubusercontent.com/travisbyr/SDV602-Blogs/main/Documentation%20Images/register.PNG">

If a user didnt have an account they could click register and create an account.

When a user enters their login details correctly, the application will provide the user will full access to all the data analysis tools.

<img src="https://github.com/travisbyr/SDV602-Blogs/blob/main/Documentation%20Images/login_code.png">

To check whether a user exists in the remote data base, I am sending a URL query using the GET method to return a value that will tell the application whether the login is correct or not. If its incorrect, the application will not proceed further without the correct login details.

