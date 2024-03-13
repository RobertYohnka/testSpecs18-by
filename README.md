# testSpecs18-yohnka
Write instructions for test specifications. Specs are split between Unit and Functional Tests.

This project encourages students to develop scenarios based on Unit and Functional tests.  Specific prompts are provided.  

<b>Unit Tests</b><br>
Prompt: A function called "multiplication" that returns the product of the two input numbers<br>
1. Expect <button>multiply(2,3)</button> to be a number<br>
2. Expect <button>multiply(2,3)</button> to be equal to 6<br>
3. Expect <button>multiply("z",3)</button> to be equal to error<br>


Prompt: A function called "concatOdds" that takes two arrays of integers as arguments.  It should return a single array that<br>only contains the odd numbers, in ascending order, from both of the arrays.<br>
1. Expect 2 arrays, containing integers, are received as arguments.<br>
2. Expect 2 separate arrays will be combined into one array.<br>
3. Expect a pushed array of odd values.<br>
4. Expect the new array of values to be sorted smallest to largest.<br>
5. If user enters a typeof value other than int. Return error.<br>
6. If a user enters multiple iputs containing the same number.  That number should only shown once in the final ascended array.<br>

<b>Functional Tests</b><br>
Prompt: A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged in<br>user.  They should be allowed to do either, but should be asked if they want to create an account or log in if they <br> check out as a guest<br>
1. If the cart is empty, show side bar of recent purchases.<br>
2.  If user status is 'guest', prompt to log in || create an id || neither...continue to checkout<br>
3.  <i><b>What behaviors of this feature does the prompt miss or gloss over?</b></i><br>
    *Is user prompted to sign-up or login upon entering the site?<br>  
    *Is there a benefit to signing up? (Publix.com offers $5 if you sign up instead of proceeding as guest)<br>


<i>I started playing with the 'markdown' language so it would look better in the Preview.  This is an example of markdown which is a lightweight markup language that describes how text should appear on a page.</i>


***Created by Bob Yohnka - 3/13/2024***
