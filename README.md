# Web-development
Starting with HTML


<!DOCTYPE html>
<html lang="en-US">
  
  <head>
    <title>This is First Webpage</title>
  </head>
  
  <body>
    <h1> This is My First Heading. </h1>
    <p> This is first Paragraph. </p>
    <p> Now, we will see how we can attach links to the web page, using "a" tags</p>
    <a href = "https://www.w3schools.com"> Learn to Code here. </a>
    <br>
    <img src="https://www.w3schools.com/w3images/streetart5.jpg" alt="Image" width="500" height="350">
    <br>
    <p style="background-color: red">We use the attributes as - name = "value" <br> The syntax of the "style" attribute is [ tagname style="property:value;" ] </p>
    <p>This is how we insert an image using "img" tag with "src", "alt", "width", and "height" attributes.</p>
    <p style="color:purple;"> This is how we style our paragraph using "style" attribute.<br> </p>
    <p title="Tooltip"> This is title attribute used to show extra info about the element.<\p>
    <h1 style="font-size:40px;">We can adjust the font size using "font-size:__px;" </h1>
    <p> We use the horizontal rule i.e "hr" tag for a thematic break. "hr" element is used to separate the content in an HTML Page.</p>
    <hr>
    <p> In "hr" tag we need not to specify the end tag, as it is an empty tag.</p>
    <pre>
    Secondly, we use "pre" tags.
    These are used to write preformatted text.
    It preserves both the spaces and line breaks.
    It usually writes in "courier" font.
    </pre>
    <p style="background-color: powderred"> We can set the background colors using style attribute.</p>
      <h2 style="font-family:Verdana;">The font-family property defines the font to be used.</h2>
      <p style="font-family:Courier;">Again we changed the font of this element.</p>
      <h2 style="text-align:center;">We can align the text accordingly using "text-align" property.</h2>
      <p>Let's see some of the formatting elemnts in the HTML.<br>
        <b>This is bold text</b> <br>
        <i>This is italic txt.</i> <br>
        <strong>This is important txt.</strong> <br>
        <em>This is emphasized txt.</em> <br>
        <mark>This is marked txt.</mark> <br>
        <small>This smaller text.</small> <br>
        <del>This shows the deleted txt.</del> <br>
        <ins>This shows inserted text.</ins> <br>
        We see <sub>Subscripted</sub> txt. <br>
        We see <sup>Superscripted</sup> text. <br>
      </p>
      <p>
        We use abbreviations with "abbr" tag like <abbr title="World Health Organizations">WHO</abbr>.<br>
        Now we'll see how to write address, that might contain contact details like postal address, email, etc.
        <address>
          Sharandeep Singh <br>
          Western Street 1 <br>
          Visit @ deep.sharan <br>
        </address>
        The bdo txt defines the text direction <bdo dir="rtl">Right to Left</bdo>. <br>
        The blockquote tag defines a section that is quoted from another source <blockquote>Gravitation is not responsible for people falling in Love.</blockquote> <br>
        The cite tag defines the title of a work, like <cite> Learning Web development. </cite> jus before the end of my degree.</br>
        The "q" tag is used for <q>short inline quotations</q>. <br>
    </p>
     
        <!-- comment are used to understand the document easily, can be used anywhere whether in between the tags to omit some txt. -->
    <p style="border:2px solid tomato;" >
      We can set border by using "style" attribute.
    </p>
    <h2 style="border:2px solid dodgerblue"> Border Styles </h2>
    <p>We can set the color values using RGB, HSL, HEX, and 50% transparent using RGBA & HSLA.</p>
    <p style="background-color:rgb(255, 99, 71);">This is tomato color equivalent to rgb(255, 99, 71).</p>
    <p style="background-color:#ff6347;"> This is tomato color equivalent to hex value #ff6347. </p>
    <p style="background-color:hsl(9, 100%, 64%);">This also a tomato color equivalent to hsl value hsl(9, 100%, 64%). </p>
    <p style="background-color:rgba(255, 99, 71, 0.5);">This is also tomato color but with 50% transparency.</p>
    <p style="background-color:hsla(9, 100%, 64%, 0.5);">This is also tomato color but with 50% transparency.<br>
    The color can be specified using RGB values as rgb(red, green, blue).<br>
    Each parameter defines the intensity of color b/w 0 to 256.<br>
    <br>
    The RGBA is extended version of RGB where A specifies Alpha value, that sets the opacity of color. <br>
    RGBA color value is specified with rgba(red, green, blue, alpha). <br>
    Alpha parameter is between 0.0(fully transparent) to 1.0(not transparent at all).</p>
    <p>The colors can also be specified using hexadecimal values as #rrggbb, where: <br>
      rr(red), gg(green), bb(blue) are hexadecimal values between 0 to ff(same as decimal value 0 to 255).<br>
      #000000 value specifies black color. <br>
      #ffffff value specifies white color.</p>
    <p> HSL values are used as hsl(hue, saturation, lightness). <br>
      Hue is color value between 0 to 360. <br>
      Saturation is color percentage 0 to 100%. <br>
      Lightness is also a color percentage between 0 to 100%. 
    </p>
    
      
    
    
        
  </body>
</html>
