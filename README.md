## Raipur Campus Website

This code creates a simple campus website with a homepage, news, council, and gallery pages. It uses basic HTML, CSS, and embedded YouTube video.

**index.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campus Page</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="council.html">Council Members</a></li>
            <li><a href="gallery.html">Gallery</a></li>
          </ul>
        </nav>
      </header>
    
      <section class="home" id="home">
        <h1>Welcome to Our Raipur Campus</h1>
        <div class="video">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_YOUTUBE_VIDEO_ID" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </section>

      <footer>
        <div class="footer-content">
            <p>&copy; 2023 Raipur Campus. All rights reserved.</p>
        </div>
      </footer>
</body>
</html>
```

**news.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raipur campus news</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="news.html">News</a></li>
                <li><a href="council.html">Council Members</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>

    <section class="news" id="news">
        <h2>News Updates</h2>
        <div class="news-item">
            <h3>News Headline 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed
                leo a diam finibus ullamcorper. </p>
        </div>
        <div class="news-item">
            <h3>News Headline 2</h3>
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                accusantium doloremque laudantium.</p>
        </div>
        </section>
</body>
</html>
```

**council.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>student council members</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="council.html">Council Members</a></li>
            <li><a href="gallery.html">Gallery</a></li>
          </ul>
        </nav>
      </header>
    <section class="council" id="council">
        <h2>Student Council Members</h2>
        <div class="member">
            <img src="images/member1.jpg" alt="Member 1">
            <h3>Member Name 1</h3>
            <p>Position</p>
        </div>
        <div class="member">
            <img src="images/member2.jpg" alt="Member 2">
            <h3>Member Name 2</h3>
            <p>Position</p>
        </div>
        </section>
</body>
</html>
```

**gallery.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gallery</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="council.html">Council Members</a></li>
            <li><a href="gallery.html">Gallery</a></li>
          </ul>
        </nav>
      </header>
      <section class="gallery" id="gallery">
        <h2>Campus Gallery</h2>
        <div class="gallery-item">
            <img src="images/campus1.jpg" alt="Campus Image 1">
        </div>
        <div class="gallery-item">
            <img src="images/campus2.jpg" alt="Campus Image 2">
        </div>
        </section>
</body>
</html>
```

**index.css:**

```css
/* Basic Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
    text-align: center;
}

h1, h2, h3 {
    color: #333;
}

/* Home Section */
.home {
    background: url("images/campus_background.jpg") no-repeat center center fixed;
    background-size: cover;
    min-height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #fff;
}

.home h1 {
    font-size: 3em;
    margin-bottom: 0.5em;
}

.video {
    margin-top: 2em;
}

/* News Section */
.news-item {
    background: #fff;
    padding: 1em;
    margin-bottom: 1em;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Council Section */
.council .member {
    display: inline-block;
    margin: 1em;
    text-align: center;
}

.council .member img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
}

/* Gallery Section */
.gallery .gallery-item {
    display: inline-block;
    margin: 1em;
}

.gallery .gallery-item img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```

Remember to:

* Replace `"YOUR_YOUTUBE_VIDEO_ID"` with the actual ID of your YouTube video.
* Replace placeholder images (`"images/member1.jpg"`, `"images/campus1.jpg"`, etc.) with your own images.
* Place all images in an "images" folder in the same directory as your HTML files.
* Create more detailed content and styling for each section as needed. 

This setup provides a basic framework for your Raipur campus website. You can customize it further by adding more sections, styling, and interactive elements. 
