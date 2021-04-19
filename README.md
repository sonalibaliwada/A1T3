# This is the repository for BUSA8090 Assignment 1 Task 3.

# Question 1: This question is based on the Wünschier book.
(a). (2 points) Create a tab-separated file in your AWS instance that contains all the data from the ‘expression’ table. Your file should look like the following
gene expr_value alr1207 8303 alr2938 10323 alr3395 1432 alr3556 8043 alr4392 729 alr4851 633 alr5000 5732
Explain how you created this file on your Linux command lines in the AWS instance. Put your file on Github so it can be checked.
(b). (2 points) Create a tab-separated file in your AWS instance that contains all the data from ‘annotation’ table. Explain how you created this file on your Linux command lines in the AWS instance. Put your file on Github so it can be checked.
(c). (5 points) Using the join command in the Linux shell (not MySQL) on your AWS instance, perform the following computation.
πgene,function_1,expr_value,metabolism(annotation ◃▹gene=gene expression) Put your Linux command on Github so it can be checked.
(d). (6 points) Consider the problem of listing all duplicate metabolisms in the annota- tion table using SQL.
i. (3 points) Give the relational algebra for this query.
ii. (3 points) Based on your relational algebra above, give MySQL code to imple- ment this query. (Put your code on Github so it can be checked.)
1
# Question 2 This question is based on the Churcher book.
(a). Consider the problem of listing all members (last names, first names, then memberID) who don’t have a coach.
i. (2 points) Give the relational algebra for this query.
ii. (2 points) Give the relational calculus for this query.
iii. (2 points) Give the MySQL code for this query. (Put your code on GitHub so it can be checked.)
(b). Consider the problem of listing all members (last names, first names, then memberID) who joined during the 2013 calendar year.
i. (2 points) Give the relational algebra for this query.
ii. (2 points) Give the relational calculus for this query.
iii. (2 points) Give MySQL code for this query. (Put your code on Github so it can be checked.)
(c). Consider the problem of finding the member names and IDs of those who didn’t compete in any tournaments in 2013, but have competed in other years
i. (3 points) Give the relational algebra for this query.
ii. (3 points) Give the relational calculus for this query.
{m.MemberID, m.LastName, m.FirstName|Member(m), Entry(e) and m.MemberID=e.MemberIDand 􏰀 Entry(y) and y.Year=2013}
iii. (3 points) Give MySQL code for this query. (Put your code on GitHub so it can be checked.)
(d). Consider the problem of finding the member names and IDs of those who have competed in every year that club members have competed.
2

i. (4 points) Give the relational calculus for this query.
ii. (5 points) Give MySQL code for this query. (Put your code on GitHub so it can be checked.)


# Softwares used:
Shell programming language, Ubuntu, Terminal, Amazon Web Services, MySQL
