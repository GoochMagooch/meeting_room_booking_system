# meeting_room_booking_system
You’ve been asked to develop a simple meeting room booking system for a company. The system will allow users to book a meeting room by specifying the room, date, and time. It should also allow users to check availability and cancel existing bookings.

Challenge Requirements:
Data Structure:
Create a data structure (e.g., a dictionary) that stores meeting rooms and their respective bookings (e.g., room names as keys, and lists of booked dates and times as values). You should initialize this with at least 3 meeting rooms and no bookings.

Book a Room:
Write a function book_room(room_name, date, time) that books a room for a given date and time, ensuring the room is available at that time. If the room is already booked at the specified time, print an error message.

Check Availability:
Write a function check_availability(room_name, date, time) that checks if a specific room is available at a given date and time and returns True if available, otherwise False.

Cancel a Booking:
Write a function cancel_booking(room_name, date, time) that cancels a booking for a specific room, date, and time. Print an error message if there’s no booking to cancel.

Main Program:
Write a simple main program that:

Displays a menu with options to book a room, check room availability, cancel a booking, or exit.
Repeats until the user chooses to exit.
Additional Parameters:
Input Validation: Ensure that the user inputs valid room names, dates, and times.
Edge Cases: Handle cases where the user tries to book a room that doesn’t exist, or cancel a booking that doesn’t exist.
Clear Output: Ensure that all actions, such as successful bookings or cancellations, are clearly communicated to the user.

Example Usage:
Welcome to the Meeting Room Booking System

1. Book a Room
2. Check Room Availability
3. Cancel a Booking
4. Exit

Please choose an option (1-4):
Option 1: User can book a room by specifying the room, date, and time.
Option 2: User can check if a room is available at a given date and time.
Option 3: User can cancel an existing booking.
Option 4: Exits the program.

Expected Outcome:
This challenge tests your ability to work with dictionaries, write multiple functions, handle user input, and implement a basic system that mirrors a real-life corporate need: managing room bookings.