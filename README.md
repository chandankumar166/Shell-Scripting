## Shell Commands
1. Print some text
```sh
echo "Hello World"
```
2. List the files in a directory
```sh
ls
```
3. Create a new file
```sh
touch file_name(with extension)
touch test.txt
```
4. Create a directory
```sh
mkdir directory_name
mkdir test_folder
```
5. To change the current directory
```sh
cd directory_name
```
6. To print the current working directory
```sh
pwd
# It displays the absolute path from the root
```
7. To get the hidden files in a directory
```sh
ls -a
```
8. To go back to the parent directory
```sh
cd ..
```
9. To see the permissions, owner, size of file
```
ls -l
```
10. To see all the commands with ls
```sh
man ls
```
11. To copy a file from one folder to other folder
```sh
cp file_name directory_name
```
12. To get all the files in a directory that starts with a specific name
```sh
ls name*
# It displays all the files in the current directory that starts with the name that we enter
```
13. To go back to the previous working directory
```sh
cd -
```
14. To move a file from one directory to other
```sh
mv file_name directory_name
# if the file and directory are not in same directory
mv file_name absolute_file_path_till_directory
```
15. To display the complete content of a file
```sh
cat file_name
```
16. To display some contents of a file (if a file is too large)
```sh
less file_name
```
17. To display the response of a url in HTML format
```sh
curl url
curl www.google.com
```
18. To download the output of the curl command in a file
```sh
curl -o google.html www.google.com
curl -o wordlist.txt http://www.mit.edu/\~ecprice/wordlist.10000
```
19. To search a word in a file
```sh
less file_name # It displays the content
/word # It highlights the word that we are searching for
```
20. To copy all the files in a directory
```sh
cp -r old_directory_name new_directory_name
# Recursively it copies all the files in old directory to new directory
# If the new_directory_name does not exists then it creates one.
```
21. To remove a file
```sh
rm file_name
```
22. To remove all files in a directory
```sh
rm *
```
23. To delete a directory
```sh
rm -r directory_name
```
24. To display the word count, line count in a file
```sh
wc fine_name
```
25. To search a pattern in a file
```sh
grep pattern_or_text file_name
grep hello wordlist.txt
# It returns all words in the file that matches the patter or text
# grep - global regular expression print
```
26. To count the number of words that matches in a file
```sh
grep pattern file_name | wc
grep py wordlist.txt | wc
| => pipe operator that takes the output of the first command and gives it to the second command as an input
```





















