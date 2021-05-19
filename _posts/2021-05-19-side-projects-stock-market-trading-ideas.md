------------------
Stock Market Trading with help of Python Coding
------------------

# Initial Ask

I had a friend who i routinely chat about stock market trading.

One day he called me and asked a request that he has a little formula in his mind to try out in trading.

And for that to work necessity is that google sheets needs to be updated in one minute interval from yahoo finance.

I by my nature thought by  python coding , it could be done.And i started writing code.

He came around later saying that no necessity for coding because he find found about GOOGLEFINANCE function in sheets and that would be fine.

I stopped working on the task. Then after sometime he called me GOOGLEFINANCE function has failed to load the sheets properly.

So i realised and maybe probably he too realised that coding is the only way to do that.

So we arranged a google meet and started live coding.

In 3 hrs had a first cut of code that goes to Yahoo finance Website and then gets that webpage to laptop filters the table from webpage 

and that uploads to google sheet.

here is screenshot of command line output when u execute python code.
![Screenshot from 2021-05-19 23-16-58](https://user-images.githubusercontent.com/13809378/118860409-fcf13b00-b8f8-11eb-967e-1a22fd12072a.png)

Later also coded up things like how much stock has changed from month beginning and week beginning.

Currently automated this process for NIFTY 50 stocks.



# Programming Side of things 

First u need to have a google cloud developer account to access google sheets api.
Then we need to make requests library call to yahoo page and extract tables by observing html page of website 

![Screenshot from 2021-05-19 23-29-19](https://user-images.githubusercontent.com/13809378/118861696-6b82c880-b8fa-11eb-8f04-76550e925457.png)





