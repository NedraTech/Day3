the previous name of kali Linux is Backtrack.
~ :- is Tilda
$(user)
#(root)
All directory *
**command** is small program that do one task well.
ls -l to list directories created user, date ,time and their name.
ls -R => recursive to list all files and folders in the directory.
ls -a to list hidden and unhidden  files.
ls filename to list the files and folders in the filename folder.
we combine ls -Rla :- to list all folders and files , their created date and time and all directory and files.
cd :- change directory
cd / to change in to root directory
cd .. 1* back
cd ../.. 2* back
cd "new folder"
cd newfolder
pwd(print working directory) it prints the present directory path.
echo to display text/string passed an argument.
e.g:- echo "hello world"
to create text into files.
**example:-**
echo "hello world" > hello.txt
to add(append)
**example:-**
echo "hi" >> hello.txt
**cat/head/tail/less**
**head** used to show the texts first line
**tail**       ""    ""   ""     "     "       last line
**cat** used to show content of that file.
**example:-**
cat hello.txt

**touch** to create a file
**example:-** touch filename
**mkdir** to create a folder
**example:-** mkdir hello
        - mkdir "hello world"  
to clear ctrl + L
**rm/remove**
**rm -r** => recursive(folders)
**rm -i** => for prompt(to ask our delete or not)
**rm -f** => force delete
**cp** copy / **mv** move

grep global search for regular expression
     to filter searches a file or particular pattern of characters and display all lines that contain that pattern.
 example:- grep "my" test.txt.
 grep -i
 case insinsitive
 grep -c count number
 grep -l  displays file name
 grep -R search text in folder
 grep -v to display without this term
 grep -n to display the term find number
wc - word count 
wc -l line
wc -c 
wc -w word
example :-
wc filename
multiple command executions
AND(&&)
or(||)
piping(|)
