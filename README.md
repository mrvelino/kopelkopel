# kopelkopel
learning coding
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tugas pwm</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
   
    <nav>
        
        <div class="brand">
            <a href="">PWM</a>
        </div>
        <ul class="menu">
            <li><a href="">menu</a><ul >
    
            </ul></li>
           <button class="btnlogin-popup" id="form-open">Register</button>
            <li><a href="">about</a><ul class="dropdown">
                <li><a href="">me</a></li>
                <li><a href="">school</a></li>
                <li><a href="">degree</a></li>
            </ul></li>
            <li><a href="">contact</a></li>
            
        </ul>
    </nav>
    
    <div class="parallax intro">
            <div class="wrapper">
                <span class="icon-close">
                    <ion-icon name="close"></ion-icon>
                </span>
                <div class="formbox login">
                    <h2>Register</h2>
                    <form action="#">
                        <div class="input-box">
                            <span class="icon">
                                <ion-icon name="person"></ion-icon>
                            </span>
                            <input type="text" required>
                            <label>Username</label>
                        </div>
                        <div class="input-box">
                            <span class="icon">
                                <ion-icon name="mail"></ion-icon>
                            </span>
                            <input type="email" required>
                            <label>Email</label>
                        </div>
                        <div class="input-box">
                            <span class="icon">
                                <ion-icon name="lock-closed"></ion-icon>
                            </span>
                            <input type="password" required>
                            <label>Password</label>
                        </div>
                        <div class="input-box">
                            <span class="icon">
                                <ion-icon name="lock-closed"></ion-icon>
                            </span>
                            <input type="password" required>
                            <label>Validasi Password (ketik ulang sandi)</label>
                        </div>
                        <div class="remember-forgot">
                            <label><input type="checkbox"> Setuju dengan syarat dan ketentuan</label>
                        </div>
                        <button type="submit" class="btn">Register
                        </button>
                        <div class="login-register">
                            <p>punya akun?<a href="#" class="register-link">Login</a></p>
                        </div>
                    </form>
                </div>
            </div>

            
            
        <div class="cta">
            <div class="cta title">WELCOME TO MY PAGE</div>       
            
        </div>
    
      
    </div>
    <div class="parallax content"></div>
    <div class="parallax footer"></div>

    <script src="script.js"></script>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>
</html>
