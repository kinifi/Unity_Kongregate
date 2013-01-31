Unity_Kongregate
================
This is very easy to do. The biggest problem is you MUST use javascript due to Kongregate's API only allowing this. 

How to Use: 
- Attach the Kongregate.js script to whatever object you want. I chose an empty and named it "KongregateAPI"

Q & A: 

1. Q: I want to change how things are displayed on screen how do I do that? 
    A: The GUILayout.Label variables must stay in order to be displayed correctly but you can change the GUILayout.BeginArea and its size to make it look however you want. 

2. Q: Can I do this in C#? 
    A: No, Kongregate does not allow you to do this because they wrote their API mostly for native games and/or flash games. 

3. Q: Can I submit my own Highscores? 
    A: Yes, just use the variables in the SubmitStatistic function. 

4. Q: Why are my highscores not posting in my game? 
    A: Kongregate needs a minimum amount of data before it can be displayed. The best is to just play it a few times and get enough data and it will eventually show up. 



