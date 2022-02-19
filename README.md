The Power of LaunchDarkly – Feature Management Platform

What you Need to Know
You must have a LaunchDarkly account (Free or Paid)
You can use you Client side ID in the file, but never put your Server side ID in a file. Use an environmental variable for that.
All naming rights owned and trademarked by Disney.


How to use this file with LaunchDarkly Feature Flags 
(Note: if you are used IKEA diagrams please be prepared for words :)
1.	Open the index.html file.  
a.	Find <Client_side_ID> on line 67 & replace it with YOUR Client-side ID key from your LaunchDarkly dashboard: Account settings>Projects.
2.	Next, you have to create a feature flag named “Sith” in the dashboard, click the Create flag button.
a.	The Key field should be “sith”
b.	Check the box "SDKs using Client-side ID"
c.	Click save flag
3.	Now open the “Sith” flag by clicking it.
a.	Click on "+ Add user targets"
b.	Under true click on "Add users..." and select Luke Skywalker.
c.	Under false click on "Add users..." and select Han Solo.
d.	At the top right is “save changes” click to save
4.	We have to create another feature flag, click Create flag again and call this one “Jedi” in the Name field.
a.	The Key field should be “jedi”
b.	Check the box "SDKs using Client-side ID"
c.	Click save flag
5.	Now open the “Jedi” flag by clicking it. 
a.	Click on "+ Add user targets"
b.	Under true click on "Add users..." and select Han Solo.
c.	Under false click on "Add users..." and select Luke Skywalker.
d.	Click on “save changes” to save
6.	You are all Set. Now you can turn on or off the two feature flags to see what messages you get.
![image](https://user-images.githubusercontent.com/32644865/154804556-1f9a35d9-3969-40cf-bb8c-27e2956457f9.png)
