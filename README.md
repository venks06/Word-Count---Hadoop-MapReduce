WordCount - Hadoop MapReduce
----------------------------
The program calculates the word count for the given input files

1. Word is defined as separated by space, comma, period(.), tab(\t), parentheses(), brackets[], curly braces({}) characters.
2. Program considers multiple input files in the given input directory
3. Program accepts 4 positional arguments - Number of reducers, should the word be considered case-sensitive, input path and output path.

Sample command to execute
$ hadoop jar MyWordCount.jar 4 true /home/cloudera/input/big.txt /user/cloudera/outputWordCount

Input path can be specified as hdfs path. For instance /user/cloudera/input/big.txt

You can download big text file from here 
http://norvig.com/big.txt
http://www.gutenberg.org/