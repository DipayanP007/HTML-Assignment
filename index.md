<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Assignment</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        
        .heading {
            overflow: hidden;
            background-color: #333;
        }
        
        .heading a {
            float: left;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }
        
        .heading a:hover {
            background-color: #04AA6D;
            color: black;
        }
        
        .heading a.active {
            background-color: #04AA6D;
            color: white;
        }
        
        #table {
            font-family: arial, sans-serif;
            border-collapse: collapse;
            width: 100%;
        }
        
        .heading1,
        .heading2 {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        
        .row-table:nth-child(even) {
            background-color: #dddddd;
        }
        
        .align-body {
            padding-left: 50px;
            padding-right: 50px;
        }
        
        .web-image {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
        }
              
        @media screen and (max-width: 600px) {
            .logo {
                width: 300px;
            }
            .form {
                width: 200px;
            }
        }
    </style>
</head>

<body>
    <header>
        <!--Logo-->
        <div class="logo">
            <p>
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/W3Schools_logo.png" alt="W3Schools" style="height: 30px; width: 250px; margin-bottom: 0px;">THE WORLD'S LARGEST WEBDEVELOPER SITE
            </p>
            
        </div>

    </header>
    <!--Logo-->

    <hr>
    <nav>
        <!--Navigation Bar-->
        <div style="font-size: 30px; " class="heading">
            <b><u><a href="https://www.w3schools.com/html/">HTML</a></u></b>
            <b><u><a href="https://www.w3schools.com/w3css/defaulT.asp">CSS</a></u></b>
            <b><u><a href="https://www.w3schools.com/js/">JAVASCRIPT</a></u></b>
            <b><u><a href="https://www.w3schools.com/python/">PYTHON</a></u></b>
        </div>
    </nav>
    <!--Navigation Bar-->
    <hr>
    <div class="align-body">
        <div>
            <section>
                <div>
                    <!--Bookmarks-->
                    <table>
                        <tr>
                            <td>
                                <h1>HTML Introduction</h1>
                            </td>
                        </tr>
                        <tr>
                            <td>HTML is the standard markup language for creating Web Pages.</td>
                        </tr>
                        <tr>
                            <td>
                                <ol>
                                    <li><a href="#Content1">What is HTML</a></li>
                                    <li><a href="#Content2">What is HTML Element</a></li>
                                    <li><a href="#web">Browser</a></li>
                                </ol>
                            </td>
                        </tr>
                    </table>
                </div>
                <!--Bookmarks-->
                <div id="Content1">
                    <!--Content 1-->
                    <table>
                        <tr>
                            <td>
                                <h2>What is HTML?</h2>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <ul>
                                    <li>HTML stands for Hyper Text Markup Language</li>
                                    <li>HTML is the standard markup language for creating Web pages</li>
                                    <li>HTML describes the structure of a Web page</li>
                                    <li>HTML consists of a series of elements</li>
                                    <li>HTML elements tell the browser how to display the content</li>
                                    <li>HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.</li>
                                </ul>
                            </td>
                        </tr>
                    </table>
                </div>
                <!--Content 1-->

                <div id="Content2">
                    <!--Content 2-->
                    <table>
                        <tr>
                            <td>
                                <h1>What is an HTML Element?</h1>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <p>An HTML element is defined by a start tag, some content, and an end tag:</p>
                                <p style="font-size: 20px;">&lt;tagname&gt;Content goes here...&lt;/tagname&gt;</p>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <p>The HTML element is everything from the start tag to the end tag:
                                    <p style="font-size: 20px;">&lt;h1&gt;My First Heading&lt;/h1&gt;</p>
                                    <p style="font-size: 20px;">&lt;p&gt;My first paragraph.&lt;/p&gt;</p>
                                </p>
                            </td>
                        </tr>
                    </table>
                </div>
                <!--Content 2 -->

                <div>
                    <!--Content 2 table -->

                    <table id="table">
                        <tr class="row-table">
                            <th class="heading1">
                                <h3>Start tag</h3>
                            </th>
                            <th class="heading1">
                                <h3>Element content</h3>
                            </th>
                            <th class="heading1">
                                <h3>End tag</h3>
                            </th>
                        </tr>
                        <tr class="row-table">
                            <td style="width: 100px;" class="heading2">&lt;h1&gt;</td>
                            <td style="width: 180px;" class="heading2">My First Heading</td>
                            <td style="width: 90px;" class="heading2">&lt;/h1&gt;</td>
                        </tr>
                        <tr class="row-table">
                            <td style="width: 100px;" class="heading2">&lt;p&gt;</td>
                            <td style="width: 180px;" class="heading2">My First Paragraph</td>
                            <td style="width: 90px;" class="heading2">&lt;/p&gt;</td>
                        </tr>
                        <tr class="row-table">
                            <td style="width: 100px;" class="heading2">&lt;br&gt;</td>
                            <td style="width: 180px;" class="heading2"><i>none</i></td>
                            <td style="width: 90px;" class="heading2"><i>none</i></td>
                        </tr>

                    </table>

                </div>
                <!--Content 2 table-->


                <div id="web">
                    <!--Web Browsers-->
                    <p style="font-size: 32px;">Web Browsers</P>
                    <p>The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
                    </p>

                    <p>A browser does not display the HTML tags, but uses them to determine how to display the document:
                    </p>


                    <img src="Images/img_chrome.png" alt="Image" class="web-image">




                </div>
                <!--Web Browsers-->


                <!--Review Form-->
                <div class="form">
                    
                    <h1>Submit Review</h1>
                    <form action="/action_page.php" method="POST">
                        <label for="name">Name:</label>
                        <input type="text" value="John" required />
                        <input type="radio" name="gender" value="Male" />Male
                        <input type="radio" name="gender" value="Female" />Female
                        <input type="radio" name="gender" value="Other" />Other
                        <br>
                        <br>
                        <label for="rate">rate it:</label>
                        <select id="rateIt" name="Very Good">
                          <option value="Very Good">Very Good</option>
                          <option value="Good">Good</option>
                          <option value="bad">bad</option>
                          <option value="worst">Worst</option>
                        </select>
                        <br>
                        <br>
                        <textarea cols="30" rows="10">Please add a review</textarea>
                        <br><br>
                        <button type="submit">Submit</button>
                    </form>

                </div>
        </div>
        <!--Review Form-->
        </section>
    </div>
    <!--  -->
    <!--  -->
    </div>
</body>

</html>
