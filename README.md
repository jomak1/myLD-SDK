The Power of LaunchDarkly – Feature Management Platform

What you Need to Know

•	You must have a LaunchDarkly account (Free or Paid)

•	You can use you Client side ID in the file, but never put your Server side ID in a file. Use an environmental variable for that.

•	Bonus task: if you have a Paid account you can create a Workflow!

•	All naming rights owned and trademarked by Disney.
 







How to use this file with LaunchDarkly Feature Flags 
(Note: if you are used IKEA diagrams please be prepared for words :)
1. Open the index.html file.  
    * Find <Client_side_ID> on line 75 & 103...replace it with YOUR Client-side ID key from your LaunchDarkly dashboard: Account settings>Projects.
2. Next, you have to create a feature flag named “Sith” in the dashboard, click the Create flag button.
    * The Key field should be “sith”
    * Check the box "SDKs using Client-side ID"
    * Click save flag
3. Now open the “Sith” flag by clicking it.
    * Click on "+ Add user targets"
    * Under false click on "Add users..." and select Luke Skywalker.
    * Under true click on "Add users..." and select Han Solo.
    * At the top right is “save changes” click to save
4. We have to create another feature flag, click Create flag again and call this one “Jedi” in the Name field.
    * The Key field should be “jedi”
    * Check the box "SDKs using Client-side ID"
    * Click save flag
5. Now open the “Jedi” flag by clicking it. 
    * Click on "+ Add user targets"
    * Under true click on "Add users..." and select Han Solo.
    * Under false click on "Add users..." and select Luke Skywalker.
    * Click on “save changes” to save
6. You are all Set. Now you can turn on or off the two feature flags to see what messages you get.



Workflows and Segments anyone
(Workflows are not allowed in a free account.  I am unable to create one)
Workflows allow you to create multi-step/multi-stage processes around your flags.  They can be as simple or detailed as you need.  It allows better control for your teams to build, run, and control you apps/software.  Workflows can be defined by starting at a certain time or by having an approver.
You can even select who can or can’t do something by using “Segments” with Workflows.  Let’s create a segment for Han and Luke.

1.	In the dashboard click on “Segments” & “Create segments” at the top right.
2.	Give your segment a name “Dev User” & a key “dev-user”
3.	Click on “Dev User” under Included users add Han Solo & exclude Luke SkyWalker
4.	Repeat this and create another Segment called “Admin-user” & for key use “”admin-user”
5.	Click on “Admin-user” under Included users add Luke SkyWalker & exclude Han Solo 


If you have access to Workflows you can create a Workflow under the “Jedi” or “Sith” flag to test the multi-step process.  The possibilities are endless with LaunchDarkly.  LaunchDarkly opens the door to a new world called Feature Management.
![image](https://user-images.githubusercontent.com/32644865/154846567-ad75f390-35cc-4f16-8d6f-7c706f26d152.png)

