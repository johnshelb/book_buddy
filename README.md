# Book Buddy Career Simulation

This site is using the following API

```
https://fsa-book-buddy-b6e748d1380d.herokuapp.com/docs/
```

This starter code allows a user to do the following:

- view a list of books
- register with a username and password
- login to the application with a username and password
- reserve and unreserve a list of books 

As a developer, you will be responsible for adding the following features to the application, as well as deploying it. You won't need to make any additional api calls. The state of the application consists of the following:
  - auth
  - books
  - reservations

Each task below is worth a max of 2 points. Total of 36 points. The two extra credit tasks are worth a max of 3 points each. 

```
[ ] Format the navbar and logout button using flexbox
[ ] Indicate if the user is on the Home page or the Books page
[ ] The button for the register and login forms both are labeled submit. The button on the login form should be labled login, and the button on the register form should be labeled register.
[ ] Don't show the password in the register and login forms.
[ ] The button on the login and register form should be disabled if an email or password is blank.
[ ] A non logged in user should not see the buttons for reserving and unreserving books or reservation counts (currently it throws an error when the buttons are clicked. Don't attempt to fix the error, just make sure the buttons are not shown to a non logged in user)
[ ] The book listing page should also display the author of each book
[ ] The books page currently displays all the books vertically. Instead the books should be displayed with 4 books per line.
[ ] A media query should be used so that on screen widths less than 700px only show 1 book per line.
[ ] A book detail page needs to be added. A user should be able to click on book title and see a detail page with the following format /books/:id
[ ] The book detail page should display the title, author, and coverimage
[ ] The book detail page should have a link back to all the books
[ ] For a logged in user, the home page should show the total number of reservations a user currently has.
[ ] For a logged in user, the Books link in the navbar should display the number of reservations a user currently has.
[ ] For a logged in user, if a book is not reserved, the reservation message for 0 books should not be shown.
[ ] The reservation message should have the correct grammer for a book reserved one time and more than one time. (you reserved this book 1 time vs. you reserved this book 2 times)
[ ] Display an error message on the login and registration forms if login was not successful.
[ ] Add a link to the navbar named FAQ's. Clicking on that link should go to the faq route and show an faq component. Feel free to add some content which describes the application.

** extra credit **

[ ] Add an indication (using css) on the books page for the book(s) which have been reserved the most times.

[ ] Add search functionality to the books page which allows a user to filter the books. A search should result in a hash change to /books/search/:term
```
