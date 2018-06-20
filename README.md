# PicReduce
An add-on to your browser to reduce the images to lower resolution. The aim of this project is to achieve low data usage by lowering the image resolution. The service used to reduce the image resolution is from (http://rsz.io/). Please read their privacy policy before using this add-on. 

How to use:
This programme require third-party add-on that can run custom-made script on any website.
Being tested on Mozilla, the script can be copied into the extension Greasemonkey. You can find the extension online.
Lastly, create a new user script from Greasemonkey and then paste everything inside. 
You can disable the script anytime by visiting the script list and uncheck this script.


Remarks:
The build is unsuccessful because while the DOM is completing, for some reason, the request of the original image has been sent and cannot be cancelled. This results in parallel requesting with the resized image and instead of reducing the bandwidth, this increases the usage of bandwidth. Will try to implement this using another platform in the future.
