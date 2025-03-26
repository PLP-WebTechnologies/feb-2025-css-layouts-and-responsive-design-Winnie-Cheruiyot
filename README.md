# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Winnies' Webpage</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            color: #333;
        }

        /* Navigation Bar */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #f3ed7f;
            padding: 15px;
            color: rgb(6, 66, 244);

        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: rgb(202, 167, 224);
            text-decoration: none;
            font-weight: bold;
        }

        /* Layout using Grid */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .box {
            background: #c1d688;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                text-align: center;
            }

            nav ul {
                flex-direction: column;
                padding: 10px 0;
            }

            nav ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <nav>
        <h1>Explore Our Robots</h1>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="media.html">Products</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Testimonials</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <div class="box">"Courage doesn’t always roar. Sometimes courage is the quiet voice at the end of the day saying, ‘I will try again tomorrow.’" — Mary Anne Radmacher</div>
        <div class="box">Happy  Learning at PLP</div>
        <div class="box">"Do not go where the path may lead, go instead where there is no path and leave a trail." — Ralph Waldo Emerson</div>
        <div class="box">"Happiness is not something ready-made. It comes from your own actions." — Dalai Lama</div>
        <div class="box">"What lies behind us and what lies before us are tiny matters compared to what lies within us." — Ralph Waldo Emerson</div>
    </div>
</body>
</html>


>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨
