# Midsemester-Canvas-surveys
Light cleaning and processing of CSV files of midsemester Canvas surveys.

I use Instructure's Canvas LMS for my classes. Canvas has an anonymous survey feature that I use to see how my students are doing and see if they have any feedback to improve the course. The survey questions can be either fixed response (e.g., multiple choice) or open-ended. While Canvas presents a helpful analysis of the responses to the fixed-response questions, the only way to access the responses to the open-ended questions is to download a CSV file of all of the responses plus some other information.

This code is part of my survey workflow. It does the following:

* Gives the CSV file a more descriptive name by appending the course(s) and the date of the survey from the response file. Note that the original file is not deleted or altered.
* Removes the uninteresting or irrelevant data (e.g., scores).
* Offers to print the responses to the screen after removing blanks. I find this useful since I can then easily copy and paste particular responses from the Jupyter notebook into a discussion forum about the survey.

The code has minimal UI and even less error handling, and assumes that the file(s) are in the download folder.
