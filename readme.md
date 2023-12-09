////   EZY NOTES   ////
////              ////

Test Zone...
* Create your own Web page using HTML and CSS



/// What is HTML ?
HTML (HyperText Markup Language) is a fundamental language in web development, serving as the standard for creating and structuring content on the internet. Utilizing a system of markup tags enclosed in angle brackets, HTML defines elements such as headings, paragraphs, links, and images. An HTML document typically comprises a head for meta-information and a body for actual content. Elements are represented by tags, and additional information can be provided through attributes. For instance, the <a> tag creates a hyperlink, and the <href> attribute specifies the URL. This simplicity and structure enable web browsers to interpret and render content consistently. HTML forms the backbone of the web, facilitating the creation of diverse and interactive online experiences.



/// Paragraphs in HTML 
We could specify a paragraph using <P> and close it using </p>
<p>Hey there what's up</p>



/// Void Elements 
Void elements in HTML are elements that do not have any content and, therefore, do not require a closing tag. Instead, they are self-closing, with a slash before the closing angle bracket. Void elements are used to embed media, line breaks, or other standalone elements in an HTML document.
<img src="images/Demo-icon.png" alt="My test image" />



/// Anatomy of HTML Document 
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>

* <!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However, these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.

*<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.

*<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

*<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this, and it can help avoid some problems later on.

*<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.

*<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.

*<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

/// Heading's in HTML

<h1> Main   
<h2> Top level
<h3> My subheading
<h4> Sub-heading
