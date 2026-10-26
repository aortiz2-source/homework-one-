Hi, I'm Aymber
This is my first website, and I’m excited to share a little about myself.

My name is Aymber, and I’m someone who enjoys creativity, learning, and making things that feel personal and fun.

I like iced coffee because it is refreshing, cozy, and the perfect drink for a chill day.

Some of the things I enjoy are spending time with friends, listening to music, trying new things, and being inspired by people who work hard and dream big.

I’m still growing, learning, and figuring out my path, but I’m excited about where it’s going.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aymber's Webpage</title>
    <style>
        /* Global Reset & Box Model setup */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #121212; /* pink and black */
            color: #f5f5f5;            /* Off-white text for readability */
            font-family: Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
        }

        /* Header applying the Box Model (Margin, Border, Padding) */
        header {
            background-color: #000000;
            color: #ff1493;            /* Deep Pink / Hot Pink */
            padding: 30px;
            margin-bottom: 25px;
            border: 3px solid #ff1493;
            border-radius: 8px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            letter-spacing: 1px;
        }

        /* Main Content Box */
        main {
            max-width: 800px;
            margin: 0 auto;
            background-color: #1e1e1e;   /* Dark gray container */
            padding: 40px;
            border: 2px solid #333333;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(255, 20, 147, 0.2); /* Subtle pink glow */
        }

        section {
            margin-bottom: 20px;
        }

        h2 {
            color: #ff69b4;            /* Lighter Pink for subheadings */
            margin-bottom: 10px;
            border-bottom: 1px solid #ff1493;
            padding-bottom: 5px;
        }

        p {
            margin-bottom: 15px;
        }

        /* Styled Button using Box Model principles */
        .btn {
            display: inline-block;
            background-color: #ff1493;
            color: #000000;
            font-weight: bold;
            padding: 12px 24px;
            margin-top: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.2s ease;
        }

        .btn:hover {
            background-color: #ff69b4;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Aymber's Page</h1>
    </header>

    <main>
        <section>
            <h2>About the Box Model</h2>
            <p>Every element in CSS is represented as a rectangular box. The box model consists of four core areas: <strong>content</strong>, <strong>padding</strong>, <strong>border</strong>, and <strong>margin</strong>.</p>
        </section>

        <section>
            <h2>Design Theme</h2>
            <p>This page features a high-contrast <strong>black and pink</strong> color scheme to make components stand out cleanly using proper spacing and borders.</p>
            <a href="https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model" class="btn" target="_blank">Learn More on MDN</a>
        </section>
    </main>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aymber's Webpage</title>
    <!-- Requirement: Separate CSS file linked via <link> tag -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- ID Selector + Box Model -->
    <header id="main-header">
        <h1>Welcome to My Webpage</h1>
    </header>

    <main>
        <!-- Class Selector + Box Model -->
        <section Web Development="box-card">
            <h2>About This Assignment</h2>
            <p>This page uses an external stylesheet with a high-contrast pink and black color theme.</p>
            
            <!-- ID Selector + Box Model -->
            <div id="special-note">
                <p><strong>Note:</strong> Box model properties (margin, padding, and border) are applied to three distinct elements.</p>
            </div>

            <a href="#" class="btn">Click Here</a>
        </section>
    </main>

</body>
</html>
