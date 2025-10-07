# TheJokeShopAssignment
Creating Simple Internet website to track jokes and the categories
ASP.NET Core MVC (2025) Review Assignment #2 – The Joke Shop
Your latest work assignment is having been tasked with creating a simple internet website that tracks Jokes and the Categories they belong to.
When generating your ASP.NET Core Project initially:
-
Support an MVC Architecture that targets .NET 8.0
-
Do not use HTTPs
-
Choose a site template with no authentication
-
Configure your website to support Entity Framework Core using SQL Server
-
Configure your new Project to track changes using GIT (as demonstrated within class) as well as track the changes you make to your project as they’re made /3
The Required information about Jokes / Categories appears below:
The Joke Model:
-
ID: integer, required
-
Title: string, required (at least 3 characters and no greater than 50 characters)
-
JokeTest: string, required (This compound word should display within the views with a user-friendly formatting. It should not allow content longer than 350 characters)
-
Perform the necessary action(s) to create the Joke model as indicated, set it up for communication with your database, and use migrations.
-
Create the initial migration (initialDb) and apply it so that it will result in the creation of the Jokes table (called JokeList) in the database named mvcJokeShopAssignment2024 /5
The Category Model:
-
ID: integer, required
-
Name: string, required (at least 5 characters)
-
Perform the necessary action(s) to create the Category model and implement the required migration that will result in the creation of a Categories table containing the information above. Call this migration addedCategoryModel and apply it. /3
-
As it turns out, there are additional changes that will be required to the models and database schema:
o
Add a required field called Teaser to the Joke model . It should have a length of at least 3 characters and no more than 325 characters– create a migration for this called addedTeaserFieldToJokeModel and apply the migration.
o
Add a field named CreationDate to the Joke Model (this is required). Create a migration for this called addedCreationDateFieldToJokeModel. Apply the migration. Do what is needed so that the MVC date picker/calendar will display in the view where needed.
o
Add what is required to implement a one to many relationship in your project whereby one Category can have many Jokes. Create a migration for this called addedRelationshipBetweenModelsJokeCategory. Apply the migration. /7
-
You have decided you are ready to scaffold controllers and views now. Do what is needed to generate the appropriate controllers and views for the Categories and Jokes. /2
-
Implement the appropriate navigation at the top of every single website page so a user can easily jump to the index action of both category and joke. Then, set up what is needed in order to ensure that instead of loading the home controller…when the application is run the index view of the jokes loads first by default. /2
-
Demonstrate the addition of application data (at least 7 jokes and three categories) that both triggers/passes validation and ensure that the application is working to this point via a walkthru video. (NOTES):
▪
The Walkthru video demonstrates the required validation, including the uniqueness for Category Names. Ensure to watch this for all required behaviour
▪
Do not simply replicate my testing data – you need to generate your own.) /3
