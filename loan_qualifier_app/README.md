# Screen-A-Lender

Just after the title, introduce your project by describing attractively what the project is about and what is the main problem that inspires you to create this project or what is the main contribution for the potential user of your project.

**Have you ever tried to find a lender and struggled to separate the silt from the gold?**
*If so, then Screen-A-Lender is designed for you!*

This allows you to upload your list of every lender into the app, your basic financials, and the loan you want, and it will filter your huge list 
    down to just the ones that fit your tailored situation! No more shall you have dozens of tabs open, or submit unneeded applications to lenders 
    that will do nothing more than cause hurtful hard inquiries!

---

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

This app utilizes the following:
-Python (version 7.3.10 or higher)
-Fire (python libarary)
-Questionary (python library)
-Basic user skills with your Command Line Interface (CLI), see below for details
-A list of all possible lenders saved as a .csv file

---

## Installation Guide & Usage

In this section, you should include detailed installation notes containing code blocks and screenshots.

**The following will provide instruction on how to access and use this software**

1) Download the code from this repository and move the app's folder to the desired location. 
2) Access your Command Line Interface || *OS X* || *Windows* ||  link to cli access for each platform
3) Navigate to the location you stored the downloaded app. link to using CD function
4) Run the app by entering the following command into your prompt: `python app.py`
5) The software will require you to direct it to the spreadsheet of lenders you have compiled.
    - You can find that path by right clicking on your file and "get info" 
    - Copy and past that into the prompt
    - It should look something like this: `./loan_qualifier_app/data/daily_rate_sheet.csv`
6) You will be asked a series of questions about your current finances. Enter each as a number and hit Enter after each.
7) The app has now filtered your loans!
8) You will be asked if you wish to save this list. Select y/n. 
9) If you selected yes, you will need to enter the file path where it should be saved.
    - Recommend against using the same file path as when loading as that will overwrite your full list!
    - It may look something like this: `./loan_qualifier_app/filtered_lender_list.csv`
10) Congrats! You're all set! Now go stimulate the economy with your freshly borrowed money! 

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

**User Story**
As a user, I need the ability to save the qualifying loans to a CSV file so that I can 
share the results as a spreadsheet.

**Acceptance Criteria**
-Given that I'm using the loan qualifier CLI, when I run the qualifier, then the tool should
    prompt the user to save the results as a CSV file.

-Given that no qualifying loans exist, when prompting a user to save a file, then the program
    should notify the user and exit.

-Given that I have a list of qualifying loans, when I'm prompted to save the results, then I 
    should be able to opt out of saving the file.

-Given that I have a list of qualifying loans, when I choose to save the loans, the tool 
    should prompt for a file path to save the file.

-Given that I'm using the loan qualifier CLI, when I choose to save the loans, then the tool
    should save the results as a CSV file.

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
