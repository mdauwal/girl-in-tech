<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Girl's in Tech</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sacramento&display=swap" rel="stylesheet">
    <style>
        /* Internal CSS */
        * {
            margin: 0;
            box-sizing: border-box;
        }
        
        body {
            background: #FFD0D0;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        .heading {
            text-align: left;
            background: red;
            color: #ffffff;
            max-width: 300px;
            position: relative;
            left: 35%;
            
        }
        .heading h1{
            font-family: sans-serif;
            color: #ffffff;
            padding: 0%;
        }
        .heading .para{
            text-align: center;
        }

        .bold-para {
            font-weight: bolder;
            font-size: 20px;
        }

        .para {
            font-family: "Sacramento", cursive;
            font-weight: 400;
            font-size: large;
        }

        .i-para {
            font-style: italic;
            font-weight: bolder;
            text-decoration: underline;
            font-size: 18px;
        }

        .main-contents {
            background: #ffffff;
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        .main-contents h3, h2, h1{
            color: red;
            padding: 10px 0;
        }

        .content-flex {
            display: flex;
            justify-content: space-between;
        }
        table, th, td {
            border: 1px solid #CA8787;
            padding: 8px;
            text-align: left;
        }
        .left-column{
            width: 40%;
        }
        .right-column{
            padding: 10px;
            line-height: 1.5;
            width: 35%;
        }

        form {
            display: flex;
            flex-direction: column;
            padding: 0%;
            margin: 0%;
        }
        form label {
            margin-bottom: 2px;
            font-weight: bold;
            
        }

        form button {
            padding: 8px;
            background-color: #E72929;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100px;
            align-self: flex-start;
            margin-top: 4px;
        }


        form label {
            font-weight: bold;
            font-size: 12px;
        }

        .gender-options {
            display: flex;
            gap: 10px;
            margin-bottom: 10px;
        }
        input{
            background: #f4dfe2;
            width: 200px;

        }
        .gender-options input {
            width: auto;
            margin-right: 5px;
        }


        .list {
            border: 2px solid #CA8787;
            background: #FFD0D0;
            padding: 15px 30px 15px;
        }

        .list ul {
            list-style:disc;
            padding: 0;
        }

        .list ul ul {
            margin-left: 20px;
            list-style-type:circle;
            color: blue;
            text-decoration: underline;
        }

        .social {
            text-align: center;
            margin-top: 20px;
        }

        .red-div {
            width: 100%;
            height: 5px;
            background: red;
            margin: 5px 0;
        }
            </style>
</head>
<body>
    <div class="main-contents">
        <div class="heading">
            <h1>Girl Develop It</h1>
            <p class="para">don't be shy, develop it</p>
            
        </div>
        <h2>About</h2>
        <p>It can be intimidating for women to learn and ask questions when they are in an <span class="bold-para">extreme <br> minority.</span> 
            While open and welcoming, today's budding developer community is up to <span class="bold-para">91% <br> male.</span> If we can empower more females with the confidence in their technological capabilities, <br> <span class="i-para">we can begin to change this landscape</span>.</p>
        
        <h3>Upcoming Classes</h3>
        
        <div class="content-flex">
            <div class="left-column">
                <table border="1">
                    <tr>
                        <th>Location</th>
                        <th>Topic</th>
                    </tr>
                    <tr>
                        <td>New York</td>
                        <td>JavaScript & JQuery</td>
                    </tr>
                    <tr>
                        <td>New York</td>
                        <td>HTML & CSS</td>
                    </tr>
                </table>
                
                <h3>Sign Up!</h3>
                <form>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <label for="location">Location:</label>
                    <select name="location" id="addr">
                        <option value="SN">San Francisco</option>
                        <option value="NY">New York</option>
                    </select>
                    
                    <label for="sex">Gender:</label>
                    <div class="gender-options">
                        <label><input type="radio" name="sex" value="female"> Female</label>
                        <label><input type="radio" name="sex" value="male"> Male</label>
                    </div>
                    
                    <label for="exp">Experience:</label>
                    <textarea name="exp" id="years"></textarea>
                    
                    <button>Sign Up!</button>
                </form>
            </div>
            <div class="right-column">
                <div class="list">
                    <h3>Projects</h3>
                    <ul>
                        <li>USA
                            <ul>
                                <li>New York</li>
                                <li>Columbus</li>
                                <li>Austin</li>
                                <li>Philly</li>
                            </ul>
                        </li>
                        <li>World
                            <ul>
                                <li>Ottawa</li>
                                <li>Sydney</li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="social">
            <a href="#">Twitter</a> |
            <a href="#">Facebook</a> |
            <a href="#">Flickr</a>
        </div>
        
        <div class="red-div"></div>
    </div>
</body>
</html>
