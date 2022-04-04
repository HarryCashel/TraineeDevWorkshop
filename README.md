### Dev Basics Workshop

Log into Gitlab via Mantel

```https://gitlab.mantelgroup.com.au/```

Make sure your password is set! You can do this in preferences
(top right hand corner of website) we will use this to authenticate in the terminal.

1. Open Terminal
2. Move to home directory
   1. ```cd ~ ```
3. Copy the project files to your local computer
   1. ```git clone https://gitlab.mantelgroup.com.au/kseniia.isaeva1/hello-everyone.git```
4. Navigate to the project folder
   1. ```cd hello-everyone```
5. Create a new branch
   1. ```git checkout -b name```
6. In the next few steps we will use vim (a text editor) to edit two files
   1. ```vim main.go```
7. Press i on the keyboard to enter insert mode and use the arrow keys to navigate to line 14
8. We want the line to look like this -->
```str = str + "Song and Harry" + "!"```
9. Press Esc on the keyboard to exit insert mode and save the file
   1. ```:wq!```
10. Edit the test file
    1. ```vim main_test.go```
11. Enter insert mode and navigate to line 11
12. We want the line to look something like this -->
```expected := "Hi Song and Harry!"```
13. Press Esc and save
    1. ```:wq!```
14. Run the unit tests
 ```Should get 'PASS ok' in your terminal as an output```
15. Add changes to the staging area (This adds all changes you've made to git automatically)
    1. ```git add .```
16. Commit these changes
    1. ```git commit -m "message"```
17. Push to the repo!
    1. ```git push origin <branch name you set up in step 3 goes here>```
