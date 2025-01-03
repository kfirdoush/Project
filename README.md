# Project
Firstly you have to create form by using html and then add the style by using css.
If you want to make your app page functional,use jvascript.
After that install Nodejs ,It helps the javascript program run outside the webbrowser.
It provide to environment to run javascript code.
create new file named index.js .This will be main file of your project.After that 
Create a new folder named models,controllers,routes and inside it, create another file named url.js.
After that install postman,mongodb,mongoose,express,shortid
Inside a model folder you require mongoose and declare a shortid property.
Every id should be unique and add totalclicks on a shortid and declare name of url.
After that exports the url.
Inside a controllers folder create url.js file and require shortid and require current directory model/url and declare the async function and two parameter req,res.User pass the original url in  body. if body is not equal then throw error with the help of status code and pass as a json format.By using await function to wait url.
After that give the shortid from user.And store the shortid and original url and total clicks on a database.After that exports shorturl
Inside a folder you have to create url.js file and require express ,controllers//url
and create router and give the path.
In mongoose.js firstly require mongoose and then declare function and return  the url
After that export the function.
Declare the all require file and also give port number,This port number helps the progrm to run the code. and connect mongodb .After connecting mongodb you show the message by using listener .then 
It helps the programmer mongodb is sucessfully connected or not
and then add middleware to pass the incoming body->url after that create urlroute for shorten the id.
You cange the port number it is not compulsory to give same number.
 In Postman you have to write it run the post http://localhost:8000/shorten then click ->body -> raw
 then give original url and click send then generate new shortid to user and paste the id
 by using get method.
 Generated  shortId you can paste the browser and directly fetch the official website like youtube.com,google.com,greeks.com and so on. And also put the website name in form then generate the shortId in form.
 After visiting the website store the time and clicks in Database
 
 
 
 




 




