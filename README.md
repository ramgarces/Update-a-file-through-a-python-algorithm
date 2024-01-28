<h1>Update a File Through a Python Algorithm</h1>

<h2>Description</h2>
In this lab, I will work with a text file that contains IP addresses that are allowed to access speicific restricted content at an organization. The file that will be created will have IP addresses added, removed, and parsed for readability. I will develop an algorithm that parses the text file of IP addresses and updates the file by removing addresses that no longer have access to the restricted content.

<h2>Programming Language(s) Used</h2>

- <b>Python</b>

<h2>Environments Used</h2>

- <b>Jupyter Notebooks</b>

<h2>Going through the Lab</h2>

<p align="center">
The view of the Jupyter notebook when it is first opened: <br/>
<img src="https://i.imgur.com/cBOE6TO.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Completing the first task of printing the contents of the file and list that will be used: <br/>
<img src="https://i.imgur.com/xwseHfI.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Opening the text file using the <code>with</code> keyword and the <code>open()</code> function with the <code>"r"</code> parameter: <br/>
<img src="https://i.imgur.com/PyJOosx.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Using the <code>.read()</code> method on the imported file and storing it in the variabled named <code>ip_addresses</code>: <br/>
<img src="https://i.imgur.com/upyl3so.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Next, I used the <code>.split()</code> method on the <code>ip_addresses</code> variable so that the data type is updated from a string to a list: <br/>
<img src="https://i.imgur.com/VUTFbiv.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Here I wrote code that will iterate through a list of IP addresses that should be removed from having access (the <code>remove_list</code> variable) using a <code>for</code> loop and an <code>if</code> statement: <br/>
<img src="https://i.imgur.com/esqvig6.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Converting <code>ip_addresses</code> back into a string with the <code>.join()</code> method, rewriting the file, and replacing its contents with the string stored in <code>ip_addresses</code>: <br/>
<img src="https://i.imgur.com/4KMHnWt.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />

<p align="center">
Finally, for the final task of the project, I put all the code used to add to, remove from, and parse the file into a function called <code>update_file()</code>: <br/>
<img src="https://i.imgur.com/9BzrpGx.png" height="80%" width="80%" alt="Domain Controller VM creation"/>
<br />
