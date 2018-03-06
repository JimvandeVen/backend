# Alternatives to Express

## Introduction  
Here I will check if there are any viable alternatives to Express. ALternatives that are workable for me.  
I will look at a few different points to make my case:  
* What alternatives are there?
* How do alternatives and Express compare to each other in features, popularity, funding, ease of use, or other factors?
* Which of those factors do or do not matter to you?  

##  What alternatives are there?  
For this little research I decided to not look for to many alternatives. As I have never worked with Express it is rather difficult  
for me to really see a destinct difference between the framework tools. I decided to compare Express vs. Koa vs. Hapi.  
But there are many more!  

## Express vs. Koa vs. Hapi  
Express has been around the longest 8 years already. Followed by Hapi (7 years) and then Koa (4 years).  
Furthermore Express is the most popular Node.js web application, followed by Koa and Hapi. You can see this in the table below. [Source(2015)](https://www.airpair.com/node.js/posts/nodejs-framework-comparison-express-koa-hapi)


| Web Application| Popularity| Release Date|Github Stars|Dependent packages|
| -------------  |:---------:|:-----------:|:----------:|:----------------:|
| Express        | 5         | 2010        |16.158      |3.828             |
| Koa            | 4         | 2013        |4.846       |99                |
| Hapi           | 4         | 2011        |3.283       |102               |

### Routing
Express has a variety of built in methods that are used to handle the routing functionality, which is usefull for me as I have no 
experience with frameworks. With Koa it is slightly different, here the use of methods is a little more advanced in my opinion.
To understand this you need a bit more knowledge of the material. With Hapi the Routing is done in a more WYSIWYG manner, which
could work for me.  

## The Good and the Bad  
### Express  
The Good:
* Biggest Community out there
* Has a lot of development behind it
* Simple way of creating a server  

The Bad:
* A lot of manual tasks
* No built in error handling
* Epress is opinionated  

### Koa  
The Good:
* Small footprint 
* Makes writing middleware easier
* Embraces ES6  

The Bad:
* You may need to write a lot of your own middleware

### Hapi  

The Good:
* Based on configuration over code
* Backed by large companies  

The Bad:
* Tailored towards bigger or more complex applications
* A lot less examples or open source code  

## Conclusion  
For me ease of use is the most important thing, when it comes to choosing a framework. As I lack experience in working with a framework.
After reading [this](https://www.airpair.com/node.js/posts/nodejs-framework-comparison-express-koa-hapi) article I am more inclined to 
choose the one with the biggest library of open source code. The framework where the need to develop is less then with the others is 
more interesting to me at this moment. So express seems to be the one I will most likely choose.
