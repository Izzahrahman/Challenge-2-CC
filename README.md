The purpose of this system is to check whether or not a hotel room booking system should accept a request from user depends on four factors:
1.	Whether there is at least one hotel that are available based on user’s preferred date
2.	Whether there is at least one hotel that are available based on user’s preferred place
3.	Whether the user fill in all details and submit the information for booking confirmation
4.	Whether the user pay for the booked room

When user runs the code, first thing that the system will ask the user is to enter the date for hotel room booking. If the date that user enter has available hotel room, it will proceed to the next step. If there is no available hotel room, the user needs to enter different date.
Next, user needs to enter the preferred destination to book the hotel room. If the chosen destination is available, it will proceed to the next step. If there is no available hotel room, user needs to choose new date again.
After that, user need to enter their name to confirm their booking. If the length of the user's name is less than 4, the system will ask the user to enter their full name. If the length of the user's name is more than 4, then it will proceed to the last part which is payment.
Lastly, the system will ask the user whether to pay or not. If user choose yes, then the booking process will be complete. But if the user choose no, then the system will cancel the booking and the user needs to start again from the top to book a hotel room.

To enter the date for booking, user can enter any date with dd/mm/yyyy format. 
Acceptance input: 08/04/2021 or 09/04/2021 or 10/04/2021 or 12/04/2021 
Rejection input: 11/04/2021 or 21.03.2020

To enter the preferred destination, user can enter any state in Malaysia.
Acceptance input: Johor or Kedah or Kelantan or Penang or Selangor or Terengganu
Rejection input: Kelantan (when the date is 10/04/2021)

To enter the user's name, user can enter any name as long as the name is more than 4 characters.
Acceptance input: izzah
Rejection input: izz

To choose whether to pay or not, user needs to enter either yes or no.
Acceptance input: yes or Yes or YES or no or No or NO
Rejection input: djf or sdknfdg or anything other than acceptance input

