# **_INCEPTION_**

## What is the difference between Library and Framework 

Framework - A framework is like the foundation upon which developers build applications for specific platforms. It includes reusable pieces of code written to perform common tasks and uses code provided by a developer for custom functionality.

Library - A library is a collection of prewritten code that can be used to simplify tasks. The term library simply refers to a collection of code that is reused repeatedly.


## What is emmet?
Emmet is shorthand to write a basic code structure. Like we use “!” in vs code and it automatically writes the whole basic code for us. It gives us the boilerplate. 


## What is a CDN?
Content Delivery Network. It is geographically distributed servers that works together to deliver data such as images, videos, static files and dynamic file. These servers are widely-spreaded. So the closest server to the requesting client delivers the data to it. Reducing the serving time. 

## What is crossorigin
It is a scenario in which a website or a web application that is running on one origin requests resources from another origin. For eg - a website hosted on example.com making a request from another webite  hosted on anotherexample.com. 

## Can we have multiple root element?
No, we can't have multiple roots in react. It is advised to have a single element with id root.
Basically react only renders in root div. 
We can have n numbers of elements along with root div. 
Simply think of it as, we can't have multiple html elements with same id. 

## What is the difference between async and differ 
These both tags are used to load and execute the script. 

**async** - In this method, the html ans script file downloads at the same time. But executes it seperately as soon it is ready. This means that the script will execute no matter whether our whole page is rendered or not. This is used when the order of execution didn't matter or our script isn't dependent on rendered part. 

**defer** - In this method, the html and script files are downloaded at the same time. But the script is only executed after the whole page is rendered. 

Async is good when we want to load and execute the script files quickly and don't care about the order of execution. And defer is good when we want the script to execute in an order. 

## What if there is some html element already present in root div. 
React will overwrite all the elements that are present in the root. And will render only those elements that are rendered using react only. 


