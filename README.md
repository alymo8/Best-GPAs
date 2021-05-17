# Best-GPAs
C program that reads a file with student information, changes its format and outputs the 5 best GPAs' student information

This C program takes student information from a csv file (attached GPAsInfo), creates a student struct out of each line, then adds this struct to its corresponding place in a linked list, ordered in terms of decreasing GPA. Then it takes the best five GPAs and outputs them to the output file.

Here is a picture showing how the incoming record from GPAsInfo.csv

![Screenshot (394)](https://user-images.githubusercontent.com/76274266/118423902-c6d07300-b6ce-11eb-8539-5649e20b0af2.png)

And here is how it was sorted giving the top 5 CGPAs to the output file topcgpas.csv

![Screenshot (395)](https://user-images.githubusercontent.com/76274266/118423968-df408d80-b6ce-11eb-8d33-2eea5a345955.png)
