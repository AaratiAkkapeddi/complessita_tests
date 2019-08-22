# complessita_tests
file sharing for complessita

1. Download the *individual version* you want to test, *not the whole repository (i.e. test.zip)*

2. unzip the file.

3. open terminal and cd into the folder: 
`cd <PATH TO TEST FOLDER>` 
*note, you can drag the folder from finder into terminal after typing cd   to get the path, but you need to have a space between "cd" and the path.*

4. Now, you need to run a local server in order to see the example in chrome. To do this, type into terminal...
`python -m http.server 8080 --bind 127.0.0.1`  *note: if this command does not work you might need to type this instead:*  `python -m SimpleHTTPServer` (it just means you are running python 2 instead of 3)

5. Now you should be able to open chrome and go to `localhost:8080` (or localhost:8000) to see your stuff.

6. To edit the file, just drag the whole test folder into Sublime Text (or whatever editor you are comfortable with). As you make changes, you should be able to just refresh the page in chrome to see it update.

7. When you are done working, you'll want to shut down your local server. To do this, go back to Terminal and hold the `control` key and press the `c` key. 
