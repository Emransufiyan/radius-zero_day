cd ~/radius-zero_day/0x02-command_line get to the directory
mkdir -p practice/file-lab/documents---- 
mkdir -p practice/file-lab/drafts-------all of the 3 creat a directories
mkdir -p practice/file-lab/backup-------

touch practice/file-lab/documents/notes.txt----
touch practice/file-lab/documents/commands.txt- 4 of them creates a files
touch practice/file-lab/drafts/draft.txt-------
touch practice/file-lab/drafts/remove-me.txt---

echo "Linux commands help developers manage files and directories." > practice/file-lab/documents/notes.txt
echo "The terminal is an important development tool." >> practice/file-lab/documents/notes.txt

cat practice/file-lab/documents/notes.txt---- show us the contents
head practice/file-lab/documents/notes.txt--- show the 1st 10 lines
tail practice/file-lab/documents/notes.txt-- show us the last 10 lines
wc -l practice/file-lab/documents/notes.txt-- counts the number of lines

cp for copying files
mv to move and rename them
rm to remove them

ls -l for detailed listing

> is used for overwriting like creates new files or overwrites files

>> is used to add output at the end of existing file

when I run file permissions I saw that both commands.txt and meeting-notes.txt are 0bytes cuz they don't contains any data where as document/notes.txt and backup/notes.txt have same size cuz we recently copied them from one directory to another
