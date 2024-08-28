Name: Olga Foox
Date Created:09/28/2024

Program Description:This application allows users to pre-purchase cinema tickets. It limits the total number of tickets sold to 20 and restricts each buyer to a maximum of 4 tickets. The program continuously prompts users for their desired ticket quantity until all tickets are sold, displaying the remaining tickets and the total number of buyers at the end.

Logical Steps:
Step 1: Initialize the total number of tickets available (20) and a counter for the total number of buyers (0).
Step 2: Start a loop that continues until all tickets are sold.
Step 3: Prompt the user to input the number of tickets they wish to buy.
Step 4: Validate the user input.
Step 5: If the input is valid, update the total tickets available and increment the number of buyers.
Step 6: Display the number of tickets purchased and the remaining tickets.
Step 7: Once all tickets are sold, display the total number of buyers.

Variables:
total_tickets: An integer that tracks the total number of tickets available (initially set to 20).total_buyers: An integer that counts the number of buyers who have made a purchase (initially set to 0).desired_tickets: An integer that holds the number of tickets a user wants to buy (input from the user).

Functions:
sell_tickets(): This function manages the ticket selling process, including user input, validation, updating counts, and displaying the remaining tickets.
