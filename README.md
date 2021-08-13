# Love Sandwiches

Love Sandwiches is a command-line based Python program to handle data automation for a sandwich company. Love Sandwiches runs a local market stall, selling a small range of sandwiches. For each market day, the staff pre-make stock to sell. If they sell out of a particular sandwich, the staff make extra for their customers, unsold sandwiches are thrown away at the end of the day.

Love Sandwiches will collect the company’s market day sales data,  calculate the surplus for the day, and produce recommendations for the number of each sandwich to make for the next market. The goal is to save the company staff time by automating a repetitive task and help reduce the surplus by better predicting sales for future markets. To achieve this, we will wire up our Python program to interact with a Google Sheet, so that we can push and pull data to and from the spreadsheet.

<insert mockup>
  
## Features 

### Existing Features

- __The Run Program Button__

Featured at the top of the page, 

- __The Terminal Area__

In this section, the program will request the market day sales data from our user,  and then check if the data provided is valid.  If it isn’t, the data will be requested again. Once the data is confirmed as valid, the rest of the program will run to add the sales data to the sales worksheet, calculate and update the surplus data, calculate the sales averages and make stock recommendations. 

- __The Program Structure__
 
### Features Left to Implement

Another feature idea that I can add 

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing 

- Python
  - After checking the Python code for [PEP8 requirements](http://pep8online.com/), no errors were found

### Unfixed Bugs
Mention of unfixed bugs and why they were not fixed 

## Deployment

This project has been deployed to Heroku 

- Create a requirements.txt file using the terminal command pip freeze > requirements.txt
- Create a Procfile with the terminal command echo web: python app.py > Procfile
  - git add and git commit the new requirements and Procfile and then git push the project to GitHub.
- Navigate over to Heroku
- Click the "new" button, give the project a name & set the region to Europe.
- From the Heroku dashboard of your newly created application, click on "Deploy" > "Deployment method" and select GitHub.
- Confirm the linking of the Heroku app to the correct GitHub repository.
- In the Heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".
- Set the config vars accordingly


The live link can be found here - https://love-sandwiches.herokuapp.com/

## Credits 

- Inspiration for the site was taken from … 

### Content 

- The text for the Home page was taken from...
- Instruction on how to implement Google Sheets was taken from [Specific YouTube Tutorial](https://www.youtube.com/) 
