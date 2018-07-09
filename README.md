# loop-data-project

This is a project I worked on to try out PHP for the first time. I received the Avilon template and here were the instructions:
1. Go to https://onepagelove.com/templates/free-templates and download the "Avilon" template

2. Upload to FTP site in the 'www' directory.  Once complete, you should see the page visible at http://PostForever.org

3. Change the name of the site to "Post Forever" in three places: the site name in the visible header, the site name in the meta data, and the site name in the TITLE tag.  Also populate some more meta data with reasonable values (you can make up your own).

4.  Find a tiny icon of a tombstone (yuck!) or something more pleasant that represents "forever" and change the "favicon" to that.

5.  semi-advanced CSS tricks:  Remove the middle image of the three that slide up at the top of the page, and scoot the first and third ones closer together.  Check the dev tools or "inspector" for any script errors on the page.

6.  Create a PHP file called "contact.php" and make the contact form at the bottom of the page call it.  The php file should capture the user's info and build an email which can be sent to [redacted email] using the php mail() function.  Be prepared to speak to security concerns about "scrubbing" user input and some of the ways PHP protects the site from being hack through user-submitted form values.

7.  Create a php block at line one that sets a variable called "$long_date" with a value of "January 1, 2018".  Change the "Lorem Ipsum" header under the "About Us" page to a PHP function that uses the php date() and strtotime() functions (and any others needeed) so that the header says "Today is the Xth day of the year."  The "Xth" should be the integer number of the day of year, followed by the string for ordinal, i.e. "th" or "st" or "rd" etc 

8.  Bonus points:  Add a field to the contact form called "Full Address" and see if you can have the php file use the curl command (or JSON Request object, or any other PHP-based method you choose) to connect to the Google geolocation API.  Get the latitude and longitude of the submitter's full address and include them in the return email.


