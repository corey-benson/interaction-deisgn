#1 - The test requires more more CSS work on the display for smaller screens. Specifically the headings and table displays for bets and receipts.

#2 - With more time I would also add animations to the micro interactions. Firstly when the user selects/deselects a bet. Animate the cross and how the bet first appears in the bet slip. The same animation would alsobe used to display the receipt(s) as they appear and the error state, if required.

#3 - For code reuse, I would move the loading spinner into a mixin. I would also look at using the module pattern for the javascript. The module pattern would help with scoping with overcomplicating the program design. Keeping the code simple and easy to read.