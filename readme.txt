window.onload = $(window).load VERSUS $(document).ready
_window.onload OR $(window).load will execute the code inside after everything is loaded (included images)
_$(document).ready will execute the code inside after everything is loaded (excluded images)

=> I have used Google Chrome Browser Developer Tools to simulate the slow speed internet to see the differences

Note: uncomment on the event you want to test, and comment out the other