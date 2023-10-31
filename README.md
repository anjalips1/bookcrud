# bookcrud
# API endpoints
1.add new book :-
  URL : http://localhost:3000/books
  METHOD : POST
  To add a new book into the db.Here title,author and summary is considered as required fields.when any one of the field is missing,it    
  returns an error message ie,(the 'field' is required)
2.get all books :-
  URL : http://localhost:3000/books
  METHOD : GET
  To return all the books in the table.
3.get details of book by its id :-
  URL : http://localhost:3000/books/{id}
  METHOD : GET
  To return the details of the book.Id of the book is given as a paramater in url.If the provided id is invalid or not found,it returns 
  that error message.
4.update book :-
  URL : http://localhost:3000/books/{id}
  METHOD : PUT
  To update a book, title,author and summary is considered as required fields.when any one of the field is missing,it     
  returns an error message ie,(the 'field' is required).Id of the book is given as a paramater in url.If the provided id is invalid or 
  not found,it returns that error message.
5.delete book by its id :-
  URL : http://localhost:3000/books/{id}
  METHOD : DELETE
  To delete a book.Id of the book is given as a paramater in url.If the provided id is invalid or not found,it returns 
  that error message.

# Setup and run application
1.install the required packages by running the following command in terminal:-
    npm i
2. run the application by running the command in terminal:-
    npm start
