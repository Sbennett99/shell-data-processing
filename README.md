# Shell-Data-Processing

## Useful Commands

- curl - used to retrieve data from url
- cat - used to copy and append files
- tr - used to transform a text file

## Examples

```Bash
curl "URL_Goes_Here" -O "fileToOutputTo"

cat file1.txt > file2.txt \\copy
cat file1.txt >> file2.txt \\ append

tr ' ' '\12' < file1.txt | sort > output.txt \\ replaces spaces with new lines

```

## Commands I used

```Bash
\\retrieve
curl "http://gutenberg.net.au/ebooks02/0200041.txt" -O 
\\ copy
cat 0200041.txt > data.txt
\\sort
tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt


```
[Data](data.txt)
[Results](result.txt)