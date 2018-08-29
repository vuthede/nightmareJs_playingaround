# GET LIWC FEATURES 
This project do 2 things:
- First:  Using the nightmareJS to mimic user actions, which are:
             +  Go to LIWC website
             +  Type a text into the box in the website
             +  Click the "Analyze" button to receive the result of LIWC features from their server
- Second: Create simple API, so that users or developers can get the "analyzed" result - LIWC features by passing the text as parameter

# Prequisite
- You need install NodeJs, Nightmarejs

# How to run demo
- Ensure all neccessary library to be installed.
- Run "node test_basic_nightmare.js" to run Server on localhost:8877. You can adjust other host and port in this file as well.
- Goto the browser and call URL like that: "localhost:8877:/?text=< Put - Your - text - need - to - analyze -here>"