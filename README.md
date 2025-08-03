<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Sharaj Club Registration</title>
    </head>
    <body>
        <h1>Welcome to SHANKHADEEP CLUB</h1>
        <h2>Fill this form to register for the club</h2>
        <br><br><br>
        <form action="Registration" method="past">
            <label for="Name" class="question">Name</label>
            <input type="text" id="Name" class="input_button" name="Name"  required>
            <br><br>
            <input type="radio" class="input_button" name="male">
            <label for="male" class="question">Male</label>
            <input type="radio" class="input_button" name="female">
            <label for="female" class="question">Female</label>
            <br><br>
            <label for="age" class="question">Age</label>
            <input type="number" class="input_button" id="age" name="age">
            <br><br>
            <label for="email" class="question">Email</label>
            <input type="email" class="input_button" id="Email" name="Email" required>
            <br><br>
            <label for="phone" class="question">Phone Number</label>
            <input type="tel" class="input_button" id="phone" name="phone" rquired>
            <br><br>
            <label for="roll_no" class="question">Institute Roll Number</label>
            <input type="text" class="input_button" id="roll_no" name="roll_no" required>
            <br><br><br>
            <input type="checkbox" class="input_button" id="terms" name="terms" required>
            <label for="terms" class="question" id="checkboxz">I Agree with the Terms and Conditions and is ready to join the club</label>
            <br><br><br>
            <button onclick="window.open('https://64.media.tumblr.com/6cd748e2e6368a698a638b896f3f4765/tumblr_inline_nz2nmgQ5lQ1qmsm5v_500.gifv')" type="Submit" id="Submit">Submit</button>
        </form>
        <style>
            body{
                background-image: url(https://t3.ftcdn.net/jpg/00/20/13/60/240_F_20136083_gk0ppzak6UdK9PcDRgPdLjcuAdo7o1LK.jpg);
                background-size: cover;
                opacity:1;
            }
            .question{
                font-size: 22px;
                font weight: bold;
                font-family:checkmark;
                color: white;
                display: inline-block;
                text-align: center;

            }
            h1{
                text-align: center;
                color: rgb(208, 213, 238);
                font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                font-size: 50px;
            }
            h1:hover{
                color: rgb(122, 162, 241);
                transition: 1s;
                font-size: 55px;
            }
            h2{
                text-align: center;
                color: rgb(237, 208, 238);
                font-family:cursive;
                font-size: 39px;
            }
            h2:hover{
                color: pink;
                transition: 1s;
                font-size: 41px;
            }
            form{
                align-content: center;
                text-align: center;
                font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                font-color: white;
                font-size: 25px;
            }
            button{
                background-color: transparent;
                color: rgb(255, 255, 255);
                font-size: 27px;
                font-weight: bold;
                border: 2px solid rgb(192, 189, 189);
                border-radius: 20px;
                padding: 10px 20px;
                cursor: pointer;

            }
            button:hover{
                background-color: white;
                color: black;
                transition: 2s;
                font-size: 30px;
            }
            #checkboxz{
                font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                font-size: 20px;
                font-style: italic;
                font-weight: bold;
                color: white;
                

            }
            input{
                border-radius: 19px;
                border-color: rgb(97, 97, 242);
                border-width: 3px;
                background-color: grey;
                opacity: 0.4;
                font-size: 20px;
                padding: 10px;
            }
            input:hover{
                background-color: white;
                border-color: blue;
                color: black;
                transition: 0.5s;
                font-size: 20.5px;
                border-radius: 70px;
            }
            

            

        </style>
    </body>
</html># Registration-page
This is a registration page
