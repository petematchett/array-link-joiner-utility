# Array Link Joiner Utility
A simple Javascript tool created to help speed up repetitive task of creating a large list of hyperlinks on a non-database driven webpage.

Why:
I was supplied a really long list of URLs and titles for each URL. They were listed in two-columns in a spreadsheet with the link text in the first column, and the corresponding URL in the second column. Since the website was not database-driven I turned to Javascript to join arrays of these columns and output as html code for these links. I then copied and pasted directly into the code of the page requiring the list of links.

Instructions:
1. Copy the first column of data (movie titles in this example)
2. Paste into a converter tool to create a comma-delimited list. I use [delim.co](http://delim.co).
3. Adjust the converter settings to enclose each item in quotes and add a comma after each.
4. Convert.
5. Copy the comma-delimited list and paste into the javascript code underneath the comment tag that reads: *paste in titles array here*.
6. Repeat for the second column (IMDB URLs in this example), and paste the comma-delimited list into the javascript code underneath the comment tag that reads: *paste in links array here*
7. Open index.html in a browser.
8. Click the copy button to copy the generated linked up HTML code.
