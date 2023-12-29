# Ex-07-CSS

# AIM
Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)

# DESIGN STEPS: 7(i)
# Step 1:
Start Define the document type as HTML.

# Step 2:
Open the HTML structure with the necessary head and body sections. In the head section, set the title of the webpage and define the styles for the webpage. The styles include: -->Default color scheme for the webpage. -->Adaptations for small screen sizes. -->Adaptations for users who prefer a dark color scheme.

# Step 3:
In the body section, create a division with the text “Saveetha Engineering College”. Also in the body section, create a list with links to the SEC Home Page, My Camnu, and GitHub.

# Step 4:
Close the HTML structure.

# CODE:7(i)
```
<!DOCTYPE html>
<html>
<head>
<style>
    /* Default Color Scheme */
    body {
            background-color: #f4f4f4;
            color: #333;
        }
        
        a {
            color: #007bff;
        }
        
        /* Small Screen Adaptation */
        @media (max-width: 600px) {
            body {
                background-color: #333;
                color: #f4f4f4;
            }
        
            a {
                color: #28a745;
            }
        }
        
        /* Dark Mode Preference */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #000;
                color: #fff;
            }
        
            a {
                color: #17a2b8;
            }
        }

</style>
</head>
<body>
    <div>
    Online Compiler For Computer Programming Languages 
  </div>
    <ul>
        <li><a href="https://colab.research.google.com/">Python</a></li>
        <li><a href="https://www.onlinegdb.com/">C- Language</a></li>
        <li><a href="https://www.jdoodle.com/online-java-compiler/">JavaScript</a></li>
  </body>
  </html>

```

  # Output
  ![Screenshot 2023-12-29 155817](https://github.com/sumanguna/ODD2023-WT-Ex-07-CSS/assets/146914442/8c3985b8-6e67-49d1-9dfd-8c292cbb709e)
![Screenshot 2023-12-29 155847](https://github.com/sumanguna/ODD2023-WT-Ex-07-CSS/assets/146914442/0d9e7621-f594-4c51-a917-a2dc6dce9c45)

# Ex-07(ii)-CSS
# AIM
To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.

# DESIGN STEPS:7(ii)
# Step 1:
Start the HTML document and create the root element.

# Step 2:
Inside , create the element and include a < style > element for CSS rules.

# Step 3:
Define CSS rules for desktop devices. Use a media query to define CSS rules for mobile devices.

# Step 4:
Create the element inside , which will contain the webpage content

# Step 5:
Inside , create a

for the heading and an for the list of hyperlinks.

# Step 6:
End the HTML document by closing all open tags.
# CODE: 7(ii)
```
<!DOCTYPE html>
<html>
<head>
<style>
    /* Default Color Scheme */
    body {
            background-color: #ff0000;
            color: #fa0000;
        }
        
        a {
            color: #a6ad58;
        }
        
        /* Small Screen Adaptation */
        @media (max-width: 600px) {
            body {
                background-color: #ff0000;
                color: #f4f4f4;
            }
        
            a {
                color: #28a745;
            }
        }
        
        /* Dark Mode Preference */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #f0e800;
                color: #fff;
            }
        
            a {
                color: #17a2b8;
            }
        }

</style>
</head>
<body>
     <div>
    Online Compilers For  Programming Languages 
  </div>
    <ul>
        <li><a href="https://www.online-python.com/">Python</a></li>
        <li><a href="https://www.programiz.com/">C- Language</a></li>
        <li><a href="https://www.jdoodle.com/online-java-compiler">JavaScript</a></li>
  </body>
  </html>
```
        
# OUTPUT
![Screenshot 2023-12-29 162543](https://github.com/sumanguna/ODD2023-WT-Ex-07-CSS/assets/146914442/47fff6c6-4ee1-4d59-8640-dd6f24a65760)
![Screenshot 2023-12-29 162557](https://github.com/sumanguna/ODD2023-WT-Ex-07-CSS/assets/146914442/7882478c-74a6-40bf-bf38-4d0e6659bdc4)
![Screenshot 2023-12-29 162617](https://github.com/sumanguna/ODD2023-WT-Ex-07-CSS/assets/146914442/66927ccc-19c7-400f-8516-14f73256093c)

# Ex-07(iii)-CSS Orientation-based Media Query
# AIM
To explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

# DESIGN STEPS:7(iii)
# Step 1:
Identify the section in your HTML file where you want to add the CSS. This is typically within the < style > tags in the section.

# Step 2:
Define a CSS media query for each orientation. The syntax for a media query is @media (orientation: value), where value can be either portrait or landscape.

# Step 3:
Within each media query, specify the CSS rules you want to apply. In this case, you want to change the background color of the body.

# Step 4:
Close the media query with a }.

# Step 5:
Repeat steps 2-4 for the other orientation.

# Step 6:
Save your HTML file.

# Step 7:
Open your HTML file in a web browser and change the orientation of your device to see the different styles applied.

# CODE:7(iii)
```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    @media (orientation: portrait) {
        body {
            background-color: rgb(228, 236, 192);
        }
    }

    @media (orientation: landscape) {
        body {
            background-color: rgb(235, 144, 238);
        }
    }
</style>
</head>
<body>
     <div>
    Online Compilers For  Programming Languages 
  </div>
    <ul>
        <li><a href="https://www.online-python.com/">Python</a></li>
        <li><a href="https://www.programiz.com/">C- Language</a></li>
        <li><a href="https://www.jdoodle.com/online-java-compiler">JavaScript</a></li>
  </body>
  </html>
```
# OUTPUT:7(iii)

