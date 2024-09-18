# Having issues with my XMLHttpRequest.


# Description:
The webpage is actually working well, and the numers are updating correctly as per the frequency of the timeout, but I'm getting an error on the development console which I do not understand.
An example of the error is: <br><br>
Uncaught TypeError: Cannot read properties of null (reading 'getElementsByTagName') at XMLHttpRequest.response ((index):49:26) at process ((index):68:11) at <anonymous>:1:1

I've reviewed my html & script but do not understand what I'm doing wrong.

See images bellow.
- The first image shows the error appearing in the console<br>
- The second image shows the location (line 49 of the index file) where the error is occuring.<br>
- The third and fourth images show the content of two consective XML files (dont worry about the numbers on the webpage being differnt as I've paused debug).<br>

PS: I'm using an "OR" rather then an "AND" in my if statement *** if(xhr.readyState === 0 || xhr.readyState === 4) *** as I have a dedicated server firing the XML file every second, so I want to run this function either way ("UNSENT"  or when "DONE")

![Error1](https://github.com/AIoT-Consulting/AJAX_Example/blob/main/assets/Screenshot%20Errors_1.png)

![Error1](https://github.com/AIoT-Consulting/AJAX_Example/blob/main/assets/Screenshot%20Errors_2.png).

![Error1](https://github.com/AIoT-Consulting/AJAX_Example/blob/main/assets/Screenshot%20Network_2.png).

![Error1](https://github.com/AIoT-Consulting/AJAX_Example/blob/main/assets/Screenshot%20Network_3.png).


Any help in understanding why I'm getting this error would really be appreciated...

