<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Omar Adham's personal webpage for Web Programming.">
    <title>Omar Adham - Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #222;
            line-height: 1.6;
        }

        nav {
            background-color: #222;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        h1, h2 {
            color: #333;
        }

        section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background-color: white;
        }

        caption {
            font-weight: bold;
            margin-bottom: 10px;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #e8e8e8;
        }

        @media (max-width: 600px) {
            body {
                padding: 10px;
            }

            nav a {
                display: inline-block;
                margin: 5px;
            }

            th, td {
                padding: 6px;
                font-size: 14px;
            }
        }
    </style>
</head>

<body>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">My Skills</a>
        <a href="#schedule">Class Schedule</a>
    </nav>

    <section id="about">
        <h1>Welcome to My Personal Webpage</h1>

        <p>
            Hello, my name is Omar Adham.
            I am an undergraduate student studying Data Science
            and Artificial Intelligence.
        </p>

        <img
            src="profile.jpg"
            alt="Profile picture of Omar"
            width="250"
            height="250"
        >
    </section>

    <section>
        <h2>My Setup</h2>

        <picture>
            <source
                media="(max-width: 600px)"
                srcset="setup-mobile.jpg"
            >

            <img
                src="setup-desktop.jpg"
                alt="Computer workspace setup"
                width="800"
                height="400"
            >
        </picture>
    </section>

    <section id="skills">
        <h2>Technical Skills</h2>

        <ul>
            <li>Python</li>
            <li>JavaScript</li>
            <li>SQL</li>
        </ul>
    </section>

    <section>
        <h2>Daily Steps</h2>

        <ol>
            <li>Review programming concepts</li>
            <li>Complete assignments</li>
            <li>Work on personal projects</li>
        </ol>
    </section>

    <section id="schedule">
        <h2>Weekly Class Schedule</h2>

        <table>
            <caption>University Weekly Schedule</caption>

            <thead>
                <tr>
                    <th scope="col">Day</th>
                    <th scope="col">10:00 AM</th>
                    <th scope="col">12:00 PM</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>Sunday</td>
                    <td>Web Programming Lecture</td>
                    <td rowspan="2">Computer Lab</td>
                </tr>

                <tr>
                    <td>Monday</td>
                    <td>Data Science Basics</td>
                </tr>

                <tr>
                    <td>Tuesday</td>
                    <td colspan="2">Library Self-Study</td>
                </tr>
            </tbody>
        </table>
    </section>
</body>
</html>
