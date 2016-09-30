# Introduction to APIs

Guest lecture for UC Berkeley [CP255 Urban Informatics](https://github.com/waddell/urban-informatics-and-visualization)  
October 3, 2016 (revised from 2015)

This demo introduces [APIs](https://en.wikipedia.org/wiki/Application_programming_interface), which are code-based interfaces that allow outside developers to interact with a piece of software. We'll focus primarily on data-access APIs that operate over the web. In class we'll use Python to connect to a variety of APIs, from earthquake feeds and geocoders to public social media posts.


### Before class

1. **Save the notebook file to your computer**

2. **From the command line, install this Python package for connecting to Twitter APIs:**  
   `pip install TwitterAPI`  
     
   There are several different package managers for Python. We're using "pip install" instead of "conda install" because Conda doesn't include this package in its index. 

3. **Make sure `keys.py` is in the same directory as the notebook**  
     
   `keys.py` (provided separately) contains demo authentication keys for the Twitter APIs. If you stumbled across this demo independently, you can sign up for your own API credentials and paste them into the `keys-example.py` file.  

4. **OPTIONAL: Sign up for your own Twitter API credentials (5 minutes)**  
     
   Twitter limits the number of simultaneous connections from a single account, so if you're willing to sign up for your own credentials, it may help the in-class demo go more smoothly!  
     
   * Log into Twitter or create an account: http://twitter.com  
     
   * Register a new developer project: https://dev.twitter.com/apps/new  

     (The form is geared toward people making smartphone apps or web apps, but you still have to fill it out... You can call the app an in-class exercise and give the URL of these demo instructions, for example)  
     
   * Submit the form, go to the "Keys and Access Tokens" tab, and click on "Create my access token" at the bottom of the page  
     
   * Copy these four codes into the `keys.py` file, replacing the demo credentials:  
     (a) consumer key, (b) consumer secret, (c) access token, (d) access token secret  
