<!DOCTYPE HTML>
<html>
    <head>
        <title>MY WEB PAGE</title>
    
    <style>
        * {
            box-sizing: border-box;

        }
        .topnav {
            overflow:hidden;
            background-color: aqua;


        }
        .topnav a{
            float: left;
            display: block;
            color: bisque;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        @media screen and (max-width: 600px){
            .topnav a{
                float: none;
                width:100%
            }
        }
        @media print{
            #one{
                display: none;
            }
        }
        @media screen and (min-width: 500px){
            body{
                font-size: 25px ; 
                background-color: lightgreen;
                color: blue;
            }
        
        }
        @media screen and (min-width: 1440px){
            body{
                font-size: 55px;
                background-color: black;
                color: antiquewhite;
            }
        
        }
        @media screen and (max-width:600px){
            .topnav a{
                float: none;
                width: 100%
            }
        }
        .topnav :hover{
            background-color: black;
            color:blanchedalmond;
        }

        </style>
    </head>
<body>
    <div id="one">
        he @media rule is used in media queries to apply different styles for different media types/devices
        media queries are a apopular technique for delivering tailored style sheets to desktops, laptop s
        and mobile devices 
    WE CAN ALSO SPECIFY THAT A CERTAIN MEDIA TYPE IS AVAILABLE ONLY FOR A PARTICULAR DEVICE FOR 
    INSTANCE WE CAN SPECIFY THE STYLES ON
    </div>    
    <div class="topnav">
            <a href="#">Link</a>
            <a href="#">Link</a>
            <a href="#">Link</a>
          </div>
          
</body>


</html>

<!--the @media rule is used in media queries to apply different styles for different media types/devices
    media queries are a apopular technique for delivering tailored style sheets to desktops, laptop s
    and mobile devices 
WE CAN ALSO SPECIFY THAT A CERTAIN MEDIA TYPE IS AVAILABLE ONLY FOR A PARTICULAR DEVICE FOR 
INSTANCE WE CAN SPECIFY THE STYLES ONLY FOR CERTAIN SCREEN READERS OR PRINTED DOCUMENTS



!!!IDEA-- ADD A FOOTER WHICH IS ONLY VISIBLW WHEN WE PRINT SO THAT WE CAN INCLUDE COPYRIGHTS TO THE 
WE CONTENT EVEN IF ITS PRINTED



the dot before the classname of the css selector indicates that we have selected all the 
classes that have the name or belong to the class as mentioned here it is the class screen_only
here we have not allowed the contents of the website to be printed so that we have set the 
display attribute to none in the print media
whilst in the screen only mode we have added a few modfications via the media tag where we can
actually change the response of the webpage according to the size of the screen and various other stuff


-->
