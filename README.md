# Getting-things-done

In this post, I would like to share my workflow. This includes a short write-up and also my to-do list, created based on David Allen's Getting Things Done (GTD) philosophy- something I have adhered to over the past 3 years. I created the spreadsheet, with constant tinkering and modifications along the way. The spreadsheet contains many nifty vba codes/procedures that I wrote – often when I’m bored at work:) There’re definitely positive 'externalities' as I sometimes extract the code from this spreadsheet when I require relevant vba code in my work. The code written, I must admit is pretty messy and not written with a nice user interface since it's only meant for my own use!

#Background
Just to give you some background. When I was a fresh graduate 3 years ago, I never knew how different the life of a working professional could be. In school, often you would have the luxury in focusing only in at most 5-8 items (modules, cca, etc) at a time. But in work, the workload could be multiple times of that. The story goes… 3 months into my job, I was bombarded with work from all directions and from multiple sources. At that point of time, I was fortunate to attend an overseas conference. But when I returned, I was completely overwhelmed by the amount of work. In fact, I didn’t even know what’s on my 'plate'. At that point of time, I realised that this could not continue further. Hence, I tried to adopt a widely used productivity style -  7 Habits of Highly effective people with emphasis on the important – urgent matrix. In the end, however I realised that everything became important and urgent! Things went back to square one. I then try to search for a different style, and struck gold with David Allen’s book on ‘Getting Thing Done. The book could be aptly summarised by these 5 steps,

*	Capture everything
*	Clarify the things you have to do. Break down into actionable steps
*	Organize by category and priority
*	Reflect
*	Engage

In this post, I will not elaborate each of these points. But rather I will relate to them (in particular only the first 3 points) as I explain my workflow process.

i. Capture everything
This is an important part of the GTD process. When an item enters into your ‘realm’, capture it! What I do is to go to the ‘Getting things done tab’, and enter the item under Column B. In my item folder in desktop, I will create a subfolder to store the relevant items such as emails, pdf, doc in chronological order (using index of 1,2,… in the name of doc). Then I would copy address of the folder and paste it under column A in the tab.

ii. Clarify the things you have to do. Break down into actionable steps
In each of the items, I always clarify what’s the next actionable step.  An actionable step could be ‘Picking up the phone and call person xxx’. David Allen espouses that this is more likely to prompt you to act upon than merely stating an item (i.e. arrange a meeting). In my spreadsheet, this would be keyed under column G onwards. As I felt that as many a time, certain items require concurrent or sequential actions, hence I try to list my actions in a pseudo-gantt chart format (see spreadsheet for eg). 
As I also wanted to view it in a non-sequential style, I wrote a procedure (shortcut ctrl+L) to push the actions to column E. 

iii. Organize by category and priority
From i and ii, I’m able to break down the item into actionable steps, but I’m still unable to view my items from a single glance. Therefore, to make life simple, I proceed to write a procedure (press SORT orange box) under ‘Directory tab’ to collate the list of items. From the directory tab, you can key in an item in E2, and you would be able to get back to corresponding item under ‘Getting things done’ tab.   


A feature that I added recently is the Deadlines procedure under ‘Deadlines’ tab. For this feature to work, you would have to first add the dates for action to be completed in Getting Things done tab under column C. So if you click the orange box in ‘Deadline’ tab, it will list the items with associated action and deadline in the same row.
To ‘bring out’ the deadlines, I wrote a code to activate this feature whenever I opened this spreadsheet - which is typically at the start of the day. So if the deadline happens to be today, a message box will pop out to remind me of that item & action. I had an earlier version that allows the programme to read out the task when it reaches the deadline. But I scrapped it when I find that it lags the system and seems to be more of a novelty.
I’ve also included categories of actions under column D (Getting things donetab): Next, Waiting and Completed. Filtering could be done with the following shortcuts so that I’m able to view the respective actions in 1 glance!

* Next: ctrl+shift+n
* Waiting: ctrl+shift+w
*	Completed:ctrl+shift+c

#After completing an item/project
After completion, I will move the entire section for item under ‘Getting things done tab’ tab to the ‘Completed’ tab for future references. For the corresponding documents/emails in my ‘Items ‘ folder as mentioned in i, I will shift it to a ‘Completed’ folder in the desktop categorised by quarters (i.e. 2016 Q1, 2016 Q2). The new folder address is also copied and pasted into the completed tab. 

#Pomodoro
While working, I also adopted Pomodoro method that caps my work intervals at 25 mins with 5 mins rest between sessions. This is akin to a boxer fighting hard in intervals and resting at the end of a round! I find this technique very useful, and hence wrote some code in Pomodoro tab. But using excel as a timer has its drawbacks. When you open or close a file, the timer in excel wil stop. Hence I prefer to use an Pomotodo Android app for this purpose. It’s a rather useful app that allows me to analyse my working patterns, interruptions and time allocated for different item!

This probably sums up my entire workflow process! I hope this is useful for anyone who wishes to adopt or adapt the process.



