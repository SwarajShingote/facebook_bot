## **Python-based automated bot (facebook)**

`Task Performed by bot :`
* Login to a Facebook account using ID and Password.
* Adding 1 friend from the same location as the location of the ID.
* Updating account status (text based).
* Commenting on the most recent post of the friend.

`Prerequisties` :
* Python
* Selenium [(Install selenium)](https://pypi.org/project/selenium/).
* Webdriver [(Download latest webdriver)](https://chromedriver.storage.googleapis.com/index.html?path=89.0.4389.23/)

`Steps to use the script:`
* `Initial setup :`
  * [Download the latest chrome webdriver](https://chromedriver.storage.googleapis.com/index.html?path=89.0.4389.23/)
  * Add the current path of chrome webdriver to the script. Edit the variable 'path'.
  
* `Clone this repository locally.` 
* `Upload the facebook_bot.ipynb file to jupyter notebook and run the code.`

  [How to use Jupyter Notebook](https://jupyter.org/)
  
  `Functions used`:
  
   1.**log_in(id_,pass_)** - Login to Instagram using your Id and Passsword, you need to pass your id ans password as arguement of the function.
   
       How it works ==> locates 'ID' box >> types your ID >> locates 'Password' box >> types your password >> press on login button

   2.**add_friend()** - Adds one friend as the location of you ID.
   
       How it works ==> visits profile page >> extract location of ID >> search for same location >> then click on people >> add friend which is at top of list of people
   
   3.**account_status(quote)** - Updates the account status with text of your choice,you need to pass your text as arguement of the function.
   
       How it works ==> visits home page >> click on 'Create a story' >> types in text box >> share a story

   4.**comment(com)** - Comments on the most recent post of your friend, you need to pass your comment as arguement of the function. 
   
       How it works ==> visits profile page >> click on 'Friends' >> click on friend name >> scrolls down >> drops a comment in the comment box

       

