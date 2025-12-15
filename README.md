# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
    <head>
        <title>sample</title>
        <link rel="stylesheet" href="style.css" >

    </head>
    <body>
        <div class="bg">
        <div class="border">
       <h1>ABOUT THE BOOK</h1>
       <div><hr class="line"></div>
       
       <div><h2 class="text">Next-Generation Cybersecurity Technologies</h2></div>
       <div class="border1">
       <div><h3 class="text1">introduces modern security solutions designed to counter evolving cyber threats. The book explores advanced concepts such as Zero Trust Architecture, AI-driven threat detection, cloud and IoT security, blockchain-based security, and post-quantum cryptography. It provides a systems-oriented view of how emerging technologies strengthen digital defense in todays interconnected world.</h3></div>
       </div>
       <div class="border2">
        <h3>"The only way to be safe is never to be secure."</h2>
       </div>
       <div class="about">
        
           <div class="image">
           
           <div class="aboutme">
           <h3>Mr.J.Parameshwaran (25005306)</h3>
           </div>
           <div class="aboutme1">
            <p>Mr.J.Parameshwaran is a college going student and he has very much interest in Cybersecurity and he wrote many books related to Cybersecurity.</p>
           </div>
           </div></div>
        <div class="border4">
            <span class="ending">
                SEC Publishers <br>
            </span>
            <span class="ending1">
                Printed in India
            </span>
            <div class="price">
                Price: Rs. 99
            </div>
        </div>  
        </div>
        </div>
    </body>
</html>

style.css

body
{
    background: #111827;
}
.bg{
    width: 500px;
    height: 800px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 3cm;
    padding: 20px;
    background-image:url('bg.jpg');
    background-size: cover;
        
}
.border{
    margin-top: 0.2cm;
    margin-left: 1px;
    margin-right: 1px;
    margin-bottom: 5px;

   
    height:780px;
    border: solid 5px rgb(21, 0, 255);
    background-size: cover;
    
}
h1{
    margin-top: 0.5cm;
    margin-left:0.2cm;
    font-style: bold;
    font-size: x-large;
    font-weight:bolder;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color:darkblue;
}
.line
{
    height: 3px;
    background-color: darkblue;
}
.text{
    background-color:#0EA5E9;
    font-size: medium;
    text-align: center;

}
.text1{
   color: black; 
   margin-left: 0.2cm;
   font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
   font-weight: 500;
   font-size: medium;
}
.border1{
   margin-left: 5px;
   margin-right: 5px;
    border: 2px solid darkblue;
    background-color: gray;
}
.border2{
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;
    border-left: 5px solid darkcyan;
    background-color: #0EA5E9;
    font-style:italic;
    font-weight: lighter;
    text-align: center;
    
}
.about
{

    background-color:gray;
    height: 180px;
    margin-top: 5px;
    margin-left: 5px;
    margin-right: 5px;
    border-top: 5px solid darkblue;
    border-left: 5px solid #06B6D4;
    border-right: 5px solid darkblue;
    border-bottom: 5px solid #06B6D4;
    text-align: right;
}
.image
{  
    background-image:url('me.jpg') ;
     background-size: cover;
     height: 142px;
     width: 100px;
     margin-top: 15px;
     margin-left: 15px;
}
.aboutme
{
    margin-left: 120px;
    flex: 1;
}
.aboutme1{
    margin-left: 100px;
    width: 300px;
    margin-top:-14px;
    display: inline-block;
    word-break: normal;
    font-weight: lighter;
    font-size:medium;
    font-style: italic;
}
.border4
{
    background-color: grey;
    border: 5px solid darkblue;
    height: 40px;
    width: 460px;
    margin-top: 35%;
    margin-left: 8px;

}
.ending{
    text-align: left;
    color: rgb(255, 255, 255);
    font-weight: bold;
    margin-left: 4px;
}
.ending1{
    text-align: left;
    margin-left: 5px;
}
.price{
    text-align: right;
    font-weight: bold;
    margin-top: -25px;
    
    margin-right: 30px;
}
```


## OUTPUT:
![alt text](<Screenshot (35).png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
