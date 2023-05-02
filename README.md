Download Link: https://assignmentchef.com/product/solved-cos418-assignment-1-part-1-intro-to-go
<br>
<h2><a id="user-content-introduction" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#introduction" aria-hidden="true"></a>Introduction</h2>

In this assignment you will solve two short problems as a way to familiarize yourself with the Go programming language. We expect you to already have a basic knowledge of the language. If you’re starting from nothing, we highly recommend going through the <a href="https://tour.golang.org/list" rel="nofollow">Golang tour</a> before you begin this assignment. Get started by <a href="https://golang.org/doc/install" rel="nofollow">installing Go</a> on your machine.

<h2><a id="user-content-software" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#software" aria-hidden="true"></a>Software</h2>

You will find the code the same directory. The two problems that you need to solve are in <tt>q1.go</tt> and <tt>q2.go</tt>. You should only add code to places that say <tt>TODO: implement me</tt>. Do not change any of the function signatures as our testing framework uses them.

<b>Q1 – Top K words:</b> The task is to find the <tt>K</tt> most common words in a given document. To exclude common words such as “a” and “the”, the user of your program should be able to specify the minimum character threshold for a word. Word matching is case insensitive and punctuations should be removed. You can find more details on what qualifies as a word in the comments in the code.

<b>Q2 – Parallel sum:</b> The task is to implement a function that sums a list of numbers in a file in parallel. For this problem you are required to use goroutines (the <tt>go</tt> keyword) and channels to pass messages across the goroutines. While it is possible to just sum all the numbers sequentially, the point of this problem is to familiarize yourself with the synchronization mechanisms in Go.

<h3><a id="user-content-testing" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#testing" aria-hidden="true"></a>Testing</h3>

Our grading uses the tests in <tt>q1_test.go</tt> and <tt>q2_test.go</tt> provided to you. To test the correctness of your code, run the following:

<pre>  $ cd assignment1-1  $ go test</pre>

If all tests pass, you should see the following output:

<pre>  $ go test  PASS  ok      /path/to/assignment1-1   0.009s</pre>

<h3><a id="user-content-submitting-assignment" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#submitting-assignment" aria-hidden="true"></a>Submitting Assignment</h3>

Now you need to submit your assignment. Commit your change and push it to the remote repository by doing the following:

4.7/5 - (3 votes)