<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- meta tags are used for SEO purpose -->
    <meta property="og:description"
        content="Beebom is a new media company that covers technology news, reviews and produce quality tech videos.">
    <title>Basics</title>
    <link rel="shortcut icon" href="./img/pngwing.com pichu.png" type="image/x-icon">



    <!-- 1. Styling using style tag  -->
    <style>
        * {
            /* background-color: rgb(197, 255, 127); */
        }

        h2 {
            color: red;
        }




        /* table formatting  */
        table,
        th,
        td {
            border: 1px solid black;
            border-collapse: collapse;
        }

        thead th,
        tfoot th {
            font-family: "Rock Salt", cursive;
        }

        th {
            letter-spacing: 2px;
        }

        td {
            letter-spacing: 1px;
        }

        tbody td,
        tfoot td {
            text-align: center;
        }

        tfoot th {
            text-align: right;
        }

        caption {
            font-family: "Rock Salt", cursive;
            padding: 20px;
            /* font-style: italic; */
            /* caption-side: bottom; */
            color: #666;
            /* text-align: right; */
            letter-spacing: 1px;
        }
    </style>

    <!-- 2. Styling by using external cascading style sheet  -->
    <link rel="stylesheet" href="./css/style.css">



</head>

<body>



    <!-- Headings in CSS  -->
    <h1 id="main-heading">Heading 1</h1>
    <h2 style="color: blueviolet;">Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

    <img src="./img/header-logo.png" alt="html-css-header"> <br>
    <a href="https://www.google.com/" target="_blank">Open to Google</a>
    <a href="#frameworks">Click to go to Frameworks form</a>



    <!-- Paragraph tag foer writing para  -->
    <!-- em used for emphasize - i.e. italicize  -->
    <!-- strong is used for bold  -->
    <!-- span is used to target a specific group of word -->

    <!-- 3. Styling using inline styling has the highest precerdence -->

    <p> <strong>Lorem</strong> <br>ipsum</br> <em>Voluptate</em> <i>dolor</i> sit amet consectetur, adipisicing elit.
        Cumque facilis fugiat iure. Iste ad et doloribus autem
        ipsum facere, placeat dolorum aliquam sapiente culpa, perspiciatis quibusdam ea nulla odio porro nesciunt
        repellendus tempore labore blanditiis. , <span id="target">quisquam</span> a. Dicta fuga ipsum voluptatibus
        magnam quasi ratione
        velit, cumque molestias, laborum quos nemo iusto accusantium quaerat, rerum nisi a quas totam nesciunt?</p>


    <h2>HTML Tables</h2>
    <!-- https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics -->
    <table>
        <caption>Dog food habits</caption>
        <thead>
            <tr>
                <th>&nbsp;</th>
                <th>Knocky</th>
                <th>Flor</th>
                <th>Ella</th>
                <th>Juan</th>
            </tr>
            <thead>
            <tbody>
                <tr>
                    <td>Breed</td>
                    <td>Jack Russell</td>
                    <td>Poodle</td>
                    <td>Streetdog</td>
                    <td>Cocker Spaniel</td>
                </tr>
                <tr>
                    <td>Age</td>
                    <td>16</td>
                    <td>9</td>
                    <td>10</td>
                    <td>5</td>
                </tr>
                <tr>
                    <td>Owner</td>
                    <td>Mother-in-law</td>
                    <td>Me</td>
                    <td>Me</td>
                    <td>Sister-in-law</td>
                </tr>
                <tr>
                    <td>Eating Habits</td>
                    <td>Eats everyone's leftovers</td>
                    <td>Nibbles at food</td>
                    <td>Hearty eater</td>
                    <td>Will eat till he explodes</td>
                </tr>
            </tbody>

        <tfoot>
            <tr>
                <th colspan="3">Total Dogs</th>
                <td colspan="2">4</td>
            </tr>
        </tfoot>
    </table>

    <!--  
        The <div> tag defines a division or a section in an HTML document. 
        The <div> tag is used as a container for HTML elements
        -->
    <div>
        <h2 id="frameworks">Some popular forntend Frameworks</h2>
        <!-- Lists  -->
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br />Est officia dolorem exercitationem odit
            obcaecati ducimus nihil voluptatem facere excepturi deleniti.</p>
        <!-- unordered list  -->
        <ul>
            <li>React</li>
            <li>Vue</li>
            <li>Angular</li>
        </ul>

        <!-- ordered list  -->
        <ol>
            <li>React</li>
            <li>Vue</li>
            <li>Angular</li>
        </ol>
    </div>

    <div>

        <!-- input tags -->
        <!-- https://www.w3schools.com/html/html_form_input_types.asp -->
        <fieldset>
            <legend><strong>Feedback Form</strong></legend>
            <form action="www..." method="post">
                <div>
                    <label for="name">Name</label><br>
                    <input type="text" name="name" id="name" placeholder="Enter Your Full Name" />
                </div>
                <div>
                    <label for="birthday">DOB:</label><br>
                    <input type="date" id="birthday" name="birthday" placeholder="Enter your date of birth">
                </div>

                <!-- 10 digit number -->
                <div>
                    <label for="phone">Phone Number</label><br>
                    <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
                        placeholder="9-999-999-999">
                </div>

                <div>
                    <label for="degree">Degree Duration</label><br>
                    <input type="number" name="degree" id="degree" />
                </div>

                <div>
                    <label for="email">Email</label><br>
                    <input type="email" name="email" id="email" required />
                </div>

                <div>
                    <label for="pasword">Password</label><br>
                    <input type="password" name="pasword" id="pasword" required />
                </div>


                <!-- Dropdown  -->



                <div>
                    <h5>Select Your Favourite Language</h5>
                    <!-- Radio Buttons  -->
                    <!-- if all the radio buttons have the same name then only one can be selected at a time -->
                    <!-- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio -->
                    <div>
                        <label for="java">Java</label>
                        <input type="radio" name="fav-language" id="java" value="Java 8">
                    </div>

                    <div>
                        <label for="python">Python</label>
                        <input type="radio" name="fav-language" id="python" value="Python">
                    </div>

                    <div>
                        <label for="js">Java Script</label>
                        <input type="radio" name="fav-language" id="js" value="js" checked>
                    </div>
                    <input type="hidden" id="custId" name="custId" value="3487">
                </div><br>




                <div>
                    <label for="ide">Choose your Favourite IDE</label>
                    <select name="ide" id="ide">
                        <option value="as">Android Studio</option>
                        <option value="in">IntelliJ Idea</option>
                        <option value="py">Pycharm</option>
                        <option value="ecl">Eclipse</option>
                    </select>
                </div><br>

                <div>
                    <!-- Auto Complete Input  -->
                    <label for="editor">Enter your Favourite Editor</label>
                    <input list="editors" id="editor">
                    <datalist id="editors">
                        <option value="fleet"></option>
                        <option value="Notepad"></option>
                        <option value="Notepad ++">Notepad ++</option>
                        <option value="VS Code"></option>
                    </datalist>
                </div><br>

                <div>
                    <!-- file upload input -->
                    <label for="file">Upload your Resume</label><br>
                    <input type="file" name="file" id="file">
                </div>

                <div>
                    <!--  checkbox input -->
                    <h5>Select your course preference</h5>
                    <input type="checkbox" id="mern" name="mern" value="mern">
                    <label for="mern">MERN stack</label><br>

                    <input type="checkbox" id="java-fullstack" name="java-fullstack" value="java-fullstack">
                    <label for="java-fullstack">Java Full Stack</label><br>

                    <input type="checkbox" id="elk" name="elk" value="elk">
                    <label for="elk">ELK stack</label>
                </div>



                <br>
                <div>

                    <label for="feeback">Feedback</label><br>
                    <textarea name="" id="feeback" cols="50" rows="3"
                        placeholder="Enter your feeback in max 100 words"></textarea>

                </div>

                <br>
                <!-- submits the whole form to the server URL action="...."  -->
                <input style="border-radius: 5px; background: whitesmoke;" type="submit" value="SUBMIT">
                <!-- resets the whole form  -->
                <input style="border-radius: 5px; background: rgb(237, 185, 185);" type="reset">


            </form>
        </fieldset>

    </div>
</body>

</html>
