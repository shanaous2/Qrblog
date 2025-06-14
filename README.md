<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A blog website featuring the latest articles on technology, lifestyle, and more.">
    <meta name="keywords" content="blog, technology, lifestyle, articles, news">
    <meta name="author" content="Your Blog Name">
    <meta name="robots" content="index, follow">
    <title>Your Blog Name - Latest Articles</title>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .navbar {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo h1 a {
            color: #fff;
            text-decoration: none;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 1.5rem;
            margin: 0;
        }

        .nav-links li a {
            color: #fff;
            text-decoration: none;
        }

        .hamburger {
            display: none;
            flex-direction: column;
            cursor: pointer;
        }

        .hamburger span {
            background: #fff;
            height: 3px;
            width: 25px;
            margin: 4px 0;
        }

        .hero {
            text-align: center;
            padding: 2rem;
            background-color: #f4f4f4;
        }

        .blog-posts {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .post {
            background: #fff;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .post img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .read-more {
            color: #007BFF;
            text-decoration: none;
            font-weight: bold;
        }

        .sidebar {
            padding: 2rem;
        }

        .ad-slot {
            margin: 1rem auto;
            text-align: center;
            max-width: 728px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }

        .footer-links {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            padding: 0;
        }

        .footer-links li a {
            color: #fff;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
                flex-direction: column;
                width: 100%;
                position: absolute;
                top: 60px;
                left: 0;
                background: #333;
            }

            .nav-links.active {
                display: flex;
            }

            .hamburger {
                display: flex;
            }

            .blog-posts {
                grid-template-columns: 1fr;
            }

            .sidebar {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="logo">
                <h1><a href="index.html">Your Blog</a></h1>
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="#category">Categories</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </nav>
        <!-- Ad Slot 1: Header Banner -->
        <div class="ad-slot">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="1234567890"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </header>

    <main>
        <section class="hero">
            <h2>Welcome to Our Blog</h2>
            <p>Discover the latest insights on technology, lifestyle, and more.</p>
        </section>

        <!-- Ad Slot 2: Below Hero Section -->
        <div class="ad-slot">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="1234567891"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>

        <section class="blog-posts">
            <article class="post">
                <img src="https://via.placeholder.com/300" alt="Blog post image">
                <h3><a href="post.html">Blog Post Title 1</a></h3>
                <p>Published on <time datetime="2025-06-14">June 14, 2025</time> by Author Name</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                <a href="post.html" class="read-more">Read More</a>
            </article>
            <!-- Ad Slot 3: Between Posts -->
            <div class="ad-slot">
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                     data-ad-slot="1234567892"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
            </div>
            <article class="post">
                <img src="https://via.placeholder.com/300" alt="Blog post image">
                <h3><a href="post.html">Blog Post Title 2</a></h3>
                <p>Published on <time datetime="2025-06-13">June 13, 2025</time> by Author Name</p>
                <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                <a href="post.html" class="read-more">Read More</a>
            </article>
        </section>

        <!-- Ad Slot 4: Sidebar -->
        <aside class="sidebar">
            <div class="ad-slot">
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                     data-ad-slot="1234567893"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
            </div>
        </aside>
    </main>

    <footer>
        <!-- Ad Slot 5: Footer Banner -->
        <div class="ad-slot">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="1234567894"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        <p>© 2025 Your Blog Name. All rights reserved.</p>
        <ul class="footer-links">
            <li><a href="#privacy">Privacy Policy</a></li>
            <li><a href="#terms">Terms of Service</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const hamburger = document.querySelector('.hamburger');
            const navLinks = document.querySelector('.nav-links');

            hamburger.addEventListener('click', () => {
                navLinks.classList.toggle('active');
            });
        });
    </script>
</body>
</html>
