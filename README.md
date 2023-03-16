# QR Code Component

This is my first Frontend Mentor challenge. I have beeen struggling with CSS and I am working to better understand the inner workings of CSS. The syntax of CSS is easy for me to understand, but trying to center an element has been a challenge. Centering horizontally was lulled me into a false sense of confidence. Centereing an element both vertically and horizontally has been the bane of my existence recently.

I have found two solutions:

This solution uses flexbox to center, but there is scrolling that I could not fix by using 'vh', 'svh', or, 'dvh'
'body{
     ...
     display: flex;
     align-items: center;
     justify-content: center;
     height: 100vh;
}'


This solution worked better, but is more difficult for me to understand and seems unelegant.
'.card {
   margin: 0;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%, -50%);
}'

I learned a lot in this challenge, but there is still so much more to learn...


