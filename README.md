# practise1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML tags (first 55)</title>
    <link rel="stylesheet" href="style.css">
    <!-- <base href="https://www.thedailystar.com/"> -->
</head>

<body>


    <header>This is the header section</header>

    HTML headings:
    <h1>Lorem ipsum dolor sit.</h1>
    <h2>Lorem ipsum dolor sit.</h2>
    <h3>Lorem ipsum dolor sit.</h3>
    <h4>Lorem ipsum dolor sit.</h4>
    <h5>Lorem ipsum dolor sit.</h5>
    <h6>Lorem ipsum dolor sit.</h6>
    <br><br>


    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique nesciunt repellendus necessitatibus
        dicta rem, quod error, eum debitis optio autem nobis aperiam mollitia blanditiis fugit iure inventore.
        Nobis enim doloribus facilis autem aperiam, nostrum necessitatibus,
        velit id magnam optio omnis. Nulla harum suscipit animi, ab beatae veritatis similique ducimus voluptate.
    </p>
    <br><br>



    <details>
        <summary>Click for more detalis</summary>
        <p>Lorem ipsum <del>dolor sit amet consectetur adipisicing elit</del>. Veritatis sequi nostrum asperiores,
            cum veniam laboriosam deserunt dolore illo <ins>voluptas nam et enim debitis</ins>! Velit perspiciatis, ea
            quasi, officia
            nihiltur <i>officiis</i> earum!
        </p>
    </details>
    <br><br>

    <!--comment-->


    <hr>
    hyperlink: <a href="https://www.facebook.com/T4sneem.Shah66/">Facebook Profile</a>
    <br><br>


    <abbr title="Defines an abbreviation or an acronym">DAA</abbr>
    <br><br>


    <!-- <acronym>	acronym. -->


    contact information for the owner of a document<address>Sector 13, Uttara, Dhaka</address>
    <br><br>


    <!-- <applet>an embedded applet</applet> -->

    <hr>


    <br><br>
    an area inside an image map: <br>
    move the mouse to the circle or rectangle<br>
    <img src="https://miro.medium.com/max/688/1*xRRF-PLCcIITBiXzTScwGQ.png" usemap="#shapes" alt="Geometrical shapes">
    <map name="shapes">
        <area shape="circle" coords="97,70,50"
            href="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Red_circle.svg/2048px-Red_circle.svg.png"
            alt="circle">
        <!--(center x),(center y),(raduis)-->
        <area shape="rectangle" coords="351,45,494,118"
            href="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Rectangle_example.svg/1280px-Rectangle_example.svg.png"
            alt="rectangle">
        <!--(left-top x),(left-top y),(right top x + width),(height y + height)-->
    </map>
    <br><br>

    <article>
        <h2>Title</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias aliquam excepturi adipisci deleniti
            dolorum repellendus fugit assumenda nesciunt doloremque facilis?</p>
    </article>
    <br><br>


    <aside>
        <h1>Lorem ipsum dolor sit.</h1>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore, eos.</p>
    </aside>
    <br><br>


    <audio controls>
        <source src="The Chainsmokers - Paris (Lyric)_160k.mp3">
    </audio>

    <hr>

    Lorem ipsum <b>dolor</b> sit. Lorem ipsum <em>emphasized</em> sit amet.
    <br><br>


    Uncomment in the head to activate these links <br><br>
    Set base link in the head section:
    <a href="sports/">Sports</a>
    <a href="events/#/">Events</a>
    <br><br>


    Bi-Directional Isolation: <bdi>مظلة</bdi> or Umbrella
    <br><br>


    Bi-Directional Override: <br>
    <bdo dir="rtl">Bi-Directional Override</bdo>
    <br><br>



    Using cite to quote: <br>
    <blockquote cite="https://en.wikipedia.org/wiki/Bird">Birds are a group of warm-blooded vertebrates
        constituting the class Aves, characterised by feathers, toothless beaked jaws, the
        laying of hard-shelled eggs, a high metabolic rate, a four-chambered heart, and a strong yet lightweight
        skeleton.
    </blockquote>
    <br><br>



    <button><a
            href="https://media.istockphoto.com/photos/75mpix-panorama-of-beautiful-mount-ama-dablam-in-himalayas-nepal-picture-id1341288649?b=1&k=20&m=1341288649&s=170667a&w=0&h=tGS0ne3HTBPt-6CltooB9ChBtNHHvfFEbby-OP--MeY=">Click
            the button</a></button>
    <br><br>



    <table>
        <caption>Students Database</caption>
        <colgroup>
            <col style="background-color:red">
            <col style="background-color:yellow">
        </colgroup>
        <tr>
            <th>Name</th>
            <th>Roll</th>
        </tr>
        <tr>
            <td>XXX</td>
            <td>0011</td>
        </tr>
        <tr>
            <td>YYY</td>
            <td>0012</td>
        </tr>
    </table>
    <br><br>


    <dl>
        <caption>Descriptive list:</caption>
        <dt>Clove</dt>
        <dd>Used as a spice</dd>

        <dt>Cinnamon</dt>
        <dd>Used as a spice</dd>
    </dl>
    <br><br>


    <ol>
        <li><data value="A15">apple</data></li>
        <li><data value="B16">banana</data></li>
    </ol>
    <br><br>

<dialog open>dialog box</dialog>
    <br><br><br><br>




    <dfn>CSS</dfn> means Cascading Style Sheets
    <br><br>
     
    <p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>
    <br><br>

    This <code>background-color</code> is for CSS or HTML
    <br><br>




    embedded element:
    <br>
    <embed type="image/webp" src="https://static.wikia.nocookie.net/dota2_gamepedia/images/f/fa/Vahdrak_render.png"
        width="300">
    <br><br>



    <figure>
        <img src="mount_fuji.jpg" alt="mountain">
        <figcaption>Fig-1.1 Mount Fuji, Japan</figcaption>
    </figure>
    <br><br>



    <iframe src="https://www.pexels.com/" title="Free Images Website" ></iframe>


    <div>
        <fieldset>
            <legend>Form:</legend>
            <form>
                <label for="name">Name: </label>
                <input type="text" style="width: 300px;"><br><br>
                <label for="text">Gender:</label><br>
                <input type="radio">Male
                <input type="radio">Female<br><br>



                <label for="text">Choose your country from the list:</label>

                <input list="country" title="Select the Country" name="Country_Name">
                <datalist id="country">
                    <option value="Bangladesh">
                    <option value="India">
                    <option value="Pakistan">
                    <option value="SriLanka">
                </datalist>
                <br><br>
                <input type="submit" value="Submit">
            </form>
        </fieldset>
    </div>
    <br><br>

    <footer>
        This is the footer section
    </footer>
    
    <!-- <basefont>Specifies a default color, size, and font for all text in a document</basefont> -->


    <!-- <big>big text</big> -->


    <!-- <canvas></canvas> -->


    <!-- <center>centered text</center> -->


    <!-- <dir>a directory list</dir>  -->


    <!-- <font>font, color, and size for text</font>  -->


    <!-- <frame>a window (a frame) in a frameset</frame>  -->

    <!-- <frameset>a set of frames</frameset>  -->

    
</body>

</html>
