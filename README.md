# Calculating-Hours-and-Minutes
This Python script converts a total number of minutes into hours and minutes using floor division (//) and modulus (%) operations.
How It Works 
1. The user inputs the total number of minutes.
2. The program calculates: - The number of *hours* by performing floor division (// 60). - The remaining *minutes* using the modulus operation (% 60).
3. The program outputs the total time in hours and minutes format.
4. ## Example ### Input: ``` Please Type the Number Of Minutes: 130 
Output: This Course is: 2 Hours and 10 Minutes Long
Code:
Total_Minutes = input('Please Type the Number Of Minutes: \n')
int_Minutes = int(Total_Minutes)
Hours = int_Minutes // 60
Minutes = int_Minutes % 60 
print("This Course is: " + str(Hours) + " Hours and " + str(Minutes) + " Minutes Long") 
