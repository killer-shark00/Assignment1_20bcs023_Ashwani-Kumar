# Assignment1_20bcs023_Ashwani-Kumar
Problem-I
An extra day is added to the calendar almost every four years as February 29, and the day is called a leap day. It corrects the calendar for the fact that our planet takes approximately 365.25 days to orbit the sun. A leap year contains a leap day.
In the Gregorian calendar, three conditions are used to identify leap years:
The year can be evenly divided by 4, is a leap year, unless:
The year can be evenly divided by 100, it is NOT a leap year, unless:
The year is also evenly divisible by 400. Then it is a leap year.
Write function to decide whether it is a leap year. If it is a leap year, return the Boolean True, otherwise return False.
Problem-II
Given an integer ‘n’, write a python code to perform the following conditional actions:
If ‘n’ is odd, print Weird
If ‘n’ is even and in the inclusive range of 2 to 5, print Not Weird
If ‘n’ is even and in the inclusive range of 6 to 20, print Weird
If ‘n’ is even and greater than 20, print Not Weird
Problem-III
The following list represents a party with 7 guests, in which ‘Hardik’ showed up first and ‘Rahane’ was the last to arrive:
 
    Arrivals = ['Hardik', 'Rahul', 'Virat', 'Rishabh’, ‘Mahi’ 'Rohit', 'Rahane']
 
A guest is considered 'fashionably late' if they arrived after at least half of the party's guests. However, they must not be the very last guest (that's taking it too far). In the above example, ‘rishabh’, ‘Mahi’ and ‘Rohit’ are the only guests who were fashionably late.
 
Write the function which takes a list of party attendees as well as a person, and tells us whether that person is fashionably late.
 
 
 
 
Problem-IV
A researcher has gathered thousands of news articles. But she wants to focus her attention on articles including a specific word. Write a function to help her filter her list of articles.
Your function should meet the following criteria:
Do not include documents where the keyword string shows up only as a part of a larger word. For example, if she were looking for the keyword “closed”, you would not include the string “enclosed.”
She does not want you to distinguish upper case from lower case letters. So the phrase “Closed the case.” would be included when the keyword is “closed”
Do not let periods or commas affect what is matched. “It is closed.” would be included when the keyword is “closed”. But you can assume there are no other types of punctuation.
 
Assume, doc_list = ["The Learn Python Challenge Rohit.", "They bought a car", "bangalore"]
 
Problem-V
An Employee's Basic Pay (BP) is to be read from user. DA is 40% of BP, HRA is 20% of BP, and write a function to calculate the Gross Pay (GP) GP is computed as BP + DA + HRA.
