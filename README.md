# blogspoon

![](http://www.pngplay.com/wp-content/uploads/2/Single-Spoon-Transparent-Background.png)
A minimal blogging service made with PHP and MySQL

## How to Install:

1. Use a service like XAMPP and start PHPMyAdmin. 
2. Create a database, then insert the SQL. 
- You can insert the SQL by pressing the SQL tab and copypasting everything from the blog.sql.
- ***I DO NOT RECOMMEND DELETING THE USER DATA. IT WILL INDICATE IF YOUR INSTALLATION WORKED, BUT IDK GO WILD***
3. Alter iframe.php to your database settings (your default username and password is root and the password is blank.)
- Example: $link = mysqli_connect("localhost", "user", "password", "db");
4. Blog away! You can change the theme using the style.css, or keep it as the plain Chicago Skyline theme.

## How to Get Blogging:

1. Go to your new table, and go to the "Insert" tab. 
- Insert your data there BUT leave reg_date and id as-is.

### Other:

I made this because the CMS from Softaculous was...really dry.
You can see the blogging in action at[ blog.luaaa.cf](blog.luaaa.cf)
