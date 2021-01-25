# Shell-Data-Processing

## Useful Commands

- curl - used to retrieve data from url
- cat - used to copy and append files
- tr - used to transform a text file
- cd - change working directory
- mkdir - make directory
- ls - list items in current directory
- touch - create new file
- ni - create new item

## Examples

```Bash
curl "URL_Goes_Here" -O "fileToOutputTo"

cat file1.txt > file2.txt \\copy
cat file1.txt >> file2.txt \\ append

tr ' ' '\12' < file1.txt | sort > output.txt \\ replaces spaces with new lines

cd DirectoryOfChoice

mkdir DirectoryName

ls
ls -l

touch newfile.txt

ni .gitignore

```

## Commands I used

```Bash
\\retrieved the great gatsby
curl "http://gutenberg.net.au/ebooks02/0200041.txt" -O 

\\ copy
cat 0200041.txt > data.txt

\\sort
tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt


```
[Data](data.txt)

[Results](result.txt)
