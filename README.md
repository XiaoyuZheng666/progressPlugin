# progressPlugin- A Native IOS Progress Plugin for Cordova

##Requirements

 - IOS 7 or higher

##Installation

    cordova plugin add cordova-plugin-xyprogress
    
##Simple Usage
show atomatically:

       cordova.plugins.progressPlugin.showProgress(function(success){
        },function(error){
        },["加载中...",4]);

show normally:

           cordova.plugins.progressPlugin.showProgress(function(success){
        },function(error){
        },["加载中...",4]);
        
 dismiss:       
     
         cordova.plugins.progressPlugin.dismissProgress()
##Screenshoot         
  ![Alt text](https://github.com/XiaoyuZheng666/progressPlugin/raw/master/Screenshots/1.png)
##LICENSE
The MIT License (MIT)

Copyright (c) 2018 bluebluesky

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


   
 

    
    
