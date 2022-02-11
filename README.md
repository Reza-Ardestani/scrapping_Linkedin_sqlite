
# Scrap It!

**! Disclaimer:**
1. THIS CODE HAS BEEN IMPLEMENTED IN PARTIAL FULFILLMENT OF THE REQUIREMENTS FOR THE INTERVIEW PROCESS OF MCI.IR  AND INTERVIEWEES WERE SUPPOSED TO PUSH THE CODE ON THEIR GITHUB. CONTACT ME TO REMOVE THIS REPOSITORY, IN CASE IT IS AGAINST YOUR TOS.
2.  IF ANY CONNECTION IS NOT OK TO THEIR CONTACT INFO BE HERE, CONTACT ME TO REMOVE THEM ASAP.

# Functionalities:

This script automatically:
+  opens your Linkedin profile
+  accesses your connections page
+  crawls the page for grabbing their profile links
+  scraps each person's information and dumps it to Sqlite db
+  and simultaneously logs all necessary level of info into Linkedin.log 

# Enlisted desing patterns are (but not limited to):
+ Creator
+ Low Coupling
+ High Cohesion 
+ Indirection
+ Modularization
+ Information Expert

# Log/DB files:
![db](/pics/db.png "db")

# Further develepments notes:
+ Check out other DBs that supports multithreading which anable us dumpping all information rows at once
+ change IP per request (You can find its code on my "Social Media Computing course" repository)
+ Sometimes you need to scroll down manually when "connection" page is being loaded. You can add one line code to scroll down for you.


# References:
> https://www.linkedin.com/pulse/how-easy-scraping-data-from-linkedin-profiles-david-craven

> https://www.geeksforgeeks.org/scrape-linkedin-using-selenium-and-beautiful-soup-in-python/

> https://stackoverflow.com/questions/28883769/remove-odd-indexed-elements-from-list-in-python#:~:text=Fun%20fact%3A%20to%20remove%20all,remove(x)%20.

> https://stackoverflow.com/questions/34759787/fetch-all-href-link-using-selenium-in-python

> https://www.tutorialspoint.com/fetch-all-href-link-using-selenium-in-python

> https://stackoverflow.com/questions/64717302/deprecationwarning-executable-path-has-been-deprecated-selenium-python

> https://chromedriver.chromium.org/home

> https://www.youtube.com/watch?v=-ARI4Cz-awo
