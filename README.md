# Ex-07-CSS

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
