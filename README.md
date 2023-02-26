# Login_Form
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Login</title>
        <link rel="stylesheet" href="style.css" />
    </head>
    <body>
        <div class="Login_Page">
            <div class="Login">Login</div>
            <form action="#">
                <div class="creds">
                    <label class="user">Username</label>
                    <input type="text" name="username" required />
                </div>
                <div class="creds">
                    <label class="passwd">Password</label>
                    <input type="password" name="password" required />
                </div>
                <input type="submit" value="Login" class="submit" />
            </form>
        </div>
    </body>
</html>
