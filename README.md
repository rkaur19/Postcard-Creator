# Postcard-Creator
For the Konica Minolta Web Developer position exam, I chose to do the first project called Postcard Creator beacsue it is something different and unique and challening at the same time. In my school career, I did projects for user authentication and I did a project with Twitter but this seemed something that would require me to use mutiple languages and plugins and most importantly it seemed something different from everything that I ahve done in the past.
 
Postcard Creator is a web application that takes an image as an input (Upload image option) from the user, asks the user to crop the image and then sends the modified image via email to anyone.

This project was done with assistance from few tutuorials like:
- https://stackoverflow.com/questions/51371492/how-to-select-area-of-an-image-for-cropping
 
 ### Languages used
- HTML / CSS
- JavaScript (Jquery) 
- PHP
 
 ### Plugin used in this project
- Name: ImageAreaSelect
- Version: 0.9.10
- Purpose: jQuery plugin that allows the user the use the crop an image functionality.
- License: Dual licensed under the MIT (MIT-LICENSE.txt) and GPL (GPL-LICENSE.txt) licenses
- Website: http://odyniec.net/projects/imgareaselect/jquery.imgareaselect.dev.js

### Library used in this project
- Name: Intervention Image
- Version: 2.x
- Purpose: HP library to create and edit images
- License: under the MIT License (https://opensource.org/licenses/MIT)
- Website: http://image.intervention.io/

### Steps for the project
1. Download XAMPP for PHP development environment: https://www.apachefriends.org/index.html
2. Download Composer v1.7.2, dependency Manager for PHP which will pull all the required libraries and manage them in one place (https://getcomposer.org/).
3. Open command line in htdocs of your project (Konicaminolta) in XAMPP and run "composer require intervention/image"
4. Create a new folder called CSS in your project folder
5. Downlaod ImageAreaSelect plugin, extract it and copy (border-h, border-v, imageareaselect file) into the CSS folder.
6. Create a new folder called JS in your project folder
7. From the extraced from in your downloads, copy "jquery.imgareaselect.min" into the JS folder
8. Create index.html which will have the client side code
9. Create Crop.php which will have the server side code
