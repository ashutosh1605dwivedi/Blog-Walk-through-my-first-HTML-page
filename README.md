<!DOCTYPE html>
<html>
  <title>Coding Ninjas Blog Page 0.1</title>
</head>
<body>
    <header>
        <a href="http://blog.codingninjas.in/"><img src="https://ninjasfiles.s3.amazonaws.com/0000000000001394.png" alt="coding ninjas logo"></a>

        <div>
          <a href="http://blog.codingninjas.in/">blog.codingninjas.in</a>
          <p>Coding Ninjas Official Blog</p>
        </div>

        <a href="http://blog.codingninjas.in/"><img
          src="https://ninjasfiles.s3.amazonaws.com/0000000000001395.png"
          alt="I love coding"
        /></a>
    </header>

    <main>
        <header>
            <h1>A step-by-step walk through of your first HTML page</h1>
        </header>
        
        <article>
            <img
          src="https://ninjasfiles.s3.amazonaws.com/0000000000001491.png"
          alt=""
        />
        <p>
          HTML is short for HyperText Markup Language.Basically, it’s the “code”
          behind every webpage – even this one. If you’re just beginning to learn
          HTML, let us tell you that it’s a fairly easy task. HTML, without
          styling, can’t do anything more than setting a layout, drawing a table,
          or creating frames – but it is handy as it helps you structure the
          content correctly, which is important when you sit down to add style to
          your HTML.
        </p>
  
        <img
          src="https://ninjasfiles.s3.amazonaws.com/0000000000001486.jpeg"
          alt="" width="50%" height="50%"
        />
        <p>
          However simple this might seem, it is a mighty useful tool when it comes
          to full-fledged web development. Various tools easily eliminate the HTML
          coding from your work process – but if you want to be in full control of
          your web-page, you’ll need to have some command over HTML.
        </p>
        <p>
          Through this article, we aim to give you the essential HTML building
          blocks that’ll help you get up and running. Reading this, you’ll be able
          to understand an HTML source code and even modify it for your own good!
        </p>
  
        <h3>Step One - TAGS</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/0000000000001485.png"
          alt="" width="50%" height="50%"
        />
        <p>Tags are what you’ll see the most when you look at any HTML source code. A tag can ideally be seen as a wrapper to any item on your HTML document. Tags tell what magic is to be done on the content enclosed by them.</p>
        <p>Let’s look at two types of tags:</p>
        <ol>
          <li>&lt;tag-example-1 &gt;I need a closign tag&lt;tag-example-1&gt;
          <li>&lt;tag-example-2/&gt;I don't need a cloding tag.</li>
        </ol>
        <p>In the first example, the sentence is wrapped by two tags. The first one is called the opening tag and the second one is called the closing tag. Everything in between is affected by the properties of the tag. Very commonly used examples of such tags are &lt;html&gt;, &lt;head&gt;, &lt;body&gt;, &lt;strong&gt;, etc.
        </p>
        </p>
        The second example tags about loner tags – as in, they don’t need a closing tag to function. Although it’s not required, these type of tags are often written as &lt;tag/> to make the debugging of code easier. Common examples of such tags are &lt;hr/> – used for horizontal line, &lt;br/> – to break the line, etc.
        <p>

            <h3>Step Two – HTML, HEAD, and BODY: The three pillars of your document</h3>
            <img src="https://ninjasfiles.s3.amazonaws.com/0000000000001488.jpg" alt="">
            <p>These tags are essential for any HTML document. They parcel out the significant parts of your HTML code.
            </p>
            <ul>
                <li>&lt;BODY> &lt;/BODY> is placed below your &lt;HEAD> tag, and everything that you want to be displayed on your screen comes under this tag. Text, images, links, and pretty much anything you can see in your browser live inside this tag.</li>

                <li>&lt;HTML> &lt;/HTML> wraps your entire code. Everything else in your HTML document needs to come inside these tags.</li>

                <li>&lt;HEAD> &lt;/HEAD> includes things like title, styles, and scripts. Head is usually present at the top (hah!), just inside the &lt;/HTML> tag.</li>
            </ul>

            <section>
                <h3>Step three – A few tags that’ll make your page pretty</h3>
            <p>Now that you know how to set up the skeleton of your document, let’s proceed with the things that will go inside your <BODY> tag and do some magic!
            </p>
            <p>Some basic text formatting tags:</p>
            <ul>
                <li>&lt;b> &lt;/b> makes your text look bold</li>
                <li>&lt;i> &lt;/i> makes you write in cursive</li>
                <li>&lt;u> &lt;/u> <u> underlines </u> what you just wrote</li>
            </ul>
            <p>For example, this piece of code</p>
            <hr>
            <code>
                &lt;html> 
                <br>
                <br>
                &lt;head> &lt;/head>
                <br>
                <br>
                &lt;body>
                 <br>
                 <br>

                  &lt;i> I am italics! &lt;/i> &lt;br/> <br>
                 &lt;b> I am bold! &lt;/b> &lt;br/> <br>
                  &lt;u> And me, well, I'm underlined! &lt;/u> &lt;br/>  
                  <br>
                  <br>
                &lt;/body>
                <br>
                <br>
                &lt;/html>
            </code>
            <hr>
            
            <br>
            <br>

            <p>
                Should produce something like this on your browser: Don’t fret too much about the &lt;br/>. It’s just for breaking the line so that you can start from the next line. Enter key does little when it comes to changing lines in your HTML document.
            </p>
            <img src="https://ninjasfiles.s3.amazonaws.com/0000000000001490.png" alt="" width="90%" height="90%">

            <p><Strong>Tags to help you structure your content:</Strong></p>
            <ul>
                <li>&lt;br/> breaks the line, making you continue to the next line</li>
                <li>&lt;p> stands for paragraph. It divides your content into paragraphs</li>
            </ul>

            <p><i>Note: you need to use these tags as space and enter keys do very little when it comes to formatting content inside an HTML document.
            </i></p>

            <h4>Heading Tags:</h4>
            <p>HTML provides you with six tags, from &lt;H1> &lt;/H1> to &lt;H6> &lt;/H6> to help you create different sized headers quickly.
            </p>
            <img src="https://ninjasfiles.s3.amazonaws.com/0000000000001487.png" alt="" width="40%" height="40%"> 
            
            <h4>Inserting an Image:</h4>
            <p> All that’s good, but what fun without images on the webpage? Don’t worry, <IMG/> to the rescue! The image tag has a mandatory attribute called “source”. Basically, it tells the browser where it should look for the image. The syntax goes something like:
            </p>
            <p><i>&lt; img src = “path_to_your_image” /></i></p>
            <p>  Furthermore, it also has attributes like height and width that let you specify the height and width you want your image to take.
            </p>

            <h4>Lists:</h4>
            <p> HTML has two types of lists – ordered and unordered. Each item of your list has to be enclosed in a tag. The syntax for creating a list is fairly simple.
            </p>
            <p> Suppose you want to create a list like:</p>
            <ul>
                <li>Item 1</li>
                <li>Item 2</li>
                <li>Item 3</li>
            </ul>
            <p>The following code will easily do the job for you:</p>
            <hr>
            <code>
                &lt;ul> <br>
                &lt;li> Item 1 &lt;/li><br>
                &lt;li> Item 2 &lt;/li> <br>
                &lt;li> Item 3 &lt;/li><br>
                &lt;/ul>
            </code>
            <hr>
            <br>
            <br>

            <p> This, by the way, was an example of an unordered list. For an ordered list, all you need to do is replace &lt;ul> with &lt;ol> and &lt;/ul> with &lt;/ol>.
            </p>
            <p>Let’s see what the following code does: </p>
            <hr>
            <code>
                &lt;html> <br>
                <br>
          &lt;head> &lt;/head> <br>
          <br>
          &lt;body> <br>
          <br>
            &lt;ul> <br>
            <br>
              &lt;li> I am unordered list's item 1! &lt;/li> <br>
              &lt;li> I am unordered list's item 2! &lt;/li> <br>
              &lt;li> I am unordered list's item 3! &lt;/li> <br>
              &lt;li> I am unordered list's item 4! &lt;/li><br>
              <br> 
            &lt;/ul> <br>
            <br>
            &lt;ol> <br>
            <br>
              &lt;li> I am ordered list's item 1! &lt;/li><br> 
              &lt;li> I am ordered list's item 2! &lt;/li><br> 
              &lt;li> I am ordered list's item 3! &lt;/li><br> 
              &lt;li> I am ordered list's item 4! &lt;/li><br> 
              <br>
            &lt;/ol> <br>
            <br>
          &lt;/body> <br>
          <br>
        &lt;/html>
            </code>
            <hr>
            <hr>
            <br>
            <img src="https://ninjasfiles.s3.amazonaws.com/0000000000001489.png" alt="">
            <p>All of these tags, when arranged coherently, will provide you with a simple webpage consisting of images, headings, and lists. Further, there are various tags that HTML supports, and we thoroughly recommend you to check them out and play with them!
            </p>
            </section>

            <h2>In Conclusion</h2>
            <p>You now know enough to skim through and understand any part of an HTML code. We request you to go ahead and try skimming through the source code of any website (you’ll find some tags you don’t know, but that’s how you learn!). Oh, and welcome to the world of web development. With HTML under your belt, your next stop should be making your page look beautiful using CSS.
            </p>
            <p>Let us know if you had any problems in the article, and don’t forget to have a look at a source code or two!</p>
        </article>
        
    </main>
  </body>
</html>
# Blog-Walk-through-my-first-HTML-page
