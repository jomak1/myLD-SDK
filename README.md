The Power of LaunchDarkly – Feature Management Platform

What you Need to Know
You must have a LaunchDarkly account (Free or Paid)
You can use you Client side ID in the file, but never put your Server side ID in a file. Use an environmental variable for that.
All naming rights owned and trademarked by Disney.

How to use this file with LaunchDarkly Feature Flags 
(Note: if you are used IKEA diagrams please be prepared for words :)

1.	Open the index.html file.  
2.	Find <Client_side_ID> on line 67 & replace it with YOUR Client-side ID key from your LaunchDarkly dashboard: Account settings>Projects.
3.	Next, you have to create a feature flag named “Sith” in the dashboard, click the Create flag button.
4.	The Key field should be “sith”
5.	Check the box "SDKs using Client-side ID"
6.	Click save flag
7.	Now open the “Sith” flag by clicking it.
8.	Click on "+ Add user targets"
9.	Under true click on "Add users..." and select Luke Skywalker.
10.	Under false click on "Add users..." and select Han Solo.
11.	At the top right is “save changes” click to save
12.	We have to create another feature flag, click Create flag again and call this one “Jedi” in the Name field.
13.	The Key field should be “jedi”
14.	Check the box "SDKs using Client-side ID"
15.	Click save flag
16.	Now open the “Jedi” flag by clicking it. 
17.	Click on "+ Add user targets"
18.	Under true click on "Add users..." and select Han Solo.
19.	Under false click on "Add users..." and select Luke Skywalker.
20.	Click on “save changes” to save
21.	You are all Set. Now you can turn on or off the two feature flags to see what messages you get.
