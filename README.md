# Weather and Forecast App
This app uses two API Calls, one to return information about todays weather conditions for a user inputted location and the other returns a three day forecast. 

This is an interesting project and one of my first ventures into API calls and the Date function in JS. It was fun and I am happy with the end result. 

Overall Structure
On page load an input field prompts the user to type in a location. This value is passed into a setter function which then passes it into the API call. 
After a successful search, it returns today's date (day, date, month, year) and gives todays temperature and weather conditions. 

A second API call has the user inputted query passed in the same way as the first and returns the next three days of the week and the maximum and minimum temperatures. 

a ternary operator is used to check to see if the API calls have been made before displaying information. 

Key takeaways
Using the date function was new and translating the date stored by the computer into a readable display was fun. 
Essentially you just need to define an array for days/ months etc, pull in the computers value and run the relevant date function that you are after. 
Passing this array value [0-6 for days of the week] and [0-11 for months] where you have outlined all possible values returns todays date value. 

API call
The key takeaway regarding API calls are that they are asychronous, therefore if you are relying on results of both you have to run conditional statements (easy way). 

Improvements needed down the line
error handling for if location entered doesnt match a location

the use of promises and async/await as a more robust solution to API handling. 


