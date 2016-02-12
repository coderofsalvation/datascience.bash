## Lightweight Data science shellscripts

Poor man's R

> csvget <columnnr>[,columnr2,..]

outputs specific column 

> csv2rrd

outputs rrd file for graphrendering with rrdtool

> csv2table

outputs csv as pretty-aligned asciitable

> csv2tsv

converts tabseperated values to commaseparated values

> csvskiphead 

[applies only to csvdata](https://github.com/jeroenjanssens/data-science-at-the-command-line/blob/master/tools/body): seq 10 | header -a 'values' | csvskiphead sort -nr

> csvheader 

add, replace, and delete header lines.

> dumbplot

output plot on the terminal given list of X,Y coordinates using gnuplot

> dateseq 

generate sequence of dates relative to today

> seq (sequence)

Sequence: generate a sequence of numbers.


> expand

converts tabs into spaces

> stats

simple awk script to get min,max,total,mean,median from piped input

> parsejson 

bash script to easify parsing json on the commandline (JSON.sh)

> num

awk statistical [functions](http://www.numcommand.com/doc/functions.html) for piping

> diff2html 

generates nice html to show differences

> histogram

awk script which renders ascii histogram based on piped input

> bashdown 

evaluate bashvariables into string ( FOO="flop" echo 'hey $FOO' | bashdown )

> markdown 

convert markdown (.md) file to html

> awk

The awk command typically processes text, fields, records, and data.

> cat

The cat command typically prints the contents of a file.

> comm

The comm command selects or rejects lines common to two files.

> cut

Cut a field

> head

Get the head of the text, meaning the first lines of data or a file.

> join

Join files by matching on fields.

> look

Display lines beginning with a given string.

> paste

Paste concatenates the corresponding lines of the given input files.

> rev (reverse)

The rev command reverses the characters of each line.

> shuf (shuffle)

Shuffle a list, a.k.a. randomize the order of list items.

> split

Split a file into pieces.

> sort

Sort the items.

> tail

Get the tail of the text, meaning the last lines of data or a file.

> uniq (unique)

Unique: make the items unique by removing duplicates.

> wc (word count)

Word count: this typically counts lines, words, and characters.

> xxd (hexdump)

Make a hexdump.

> pv (pipe viewer)

monitor progress of a pipeline with [pv](http://www.ivarch.com/programs/pv.shtml)

> pick (select a line)

allows user to select a line based on the incoming line
