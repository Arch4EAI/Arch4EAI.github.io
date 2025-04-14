<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workshop on Architecture Support for Embodied AI Systems</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 1600px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #1a3c6e;
            font-weight: bold;
            position: relative;
            padding-bottom: 10px;
        }
        h1 {
            font-size: 3em;
            color: #1a3c6e;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 1px;
            padding-bottom: 15px;
            border-bottom: 4px solid #1a3c6e;
            margin-bottom: 30px;
            text-align: center;
        }
        h2 {
            font-size: 1.8em;
            background: linear-gradient(to right, #e6f0ff, #ffffff);
            padding: 10px 15px;
            border-left: 5px solid #1a3c6e;
            margin-top: 30px;
        }
        h3 {
            font-size: 1.4em;
            color: #2a4b8c;
            margin-top: 20px;
            border-bottom: 1px solid #ccc;
            padding-bottom: 5px;
        }
        .submission-guidelines ul {
            margin: 10px 0;
            padding-left: 20px;
        }
        .submission-guidelines ul li {
            margin-bottom: 10px;
        }
        hr {
            border: 0;
            border-top: 1px solid #ddd;
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
        a {
            color: #1a3c6e;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Workshop on Architecture Support for Embodied AI Systems</h1>

    <p><strong>This workshop is in conjunction with <a href="https://iscaconf.org/isca2025/">ISCA 2025</a></strong></p>
    <p><strong>Please register for ISCA to get Zoom access to this event</strong></p>

    <ul>
        <li>🕡 <strong>Duration</strong>: Half Day</li>
        <li>📅 <strong>Date</strong>: Saturday, June 21, 2025</li>
        <li>⏰ <strong>Start Time</strong>: 1:00 PM JST</li>
        <li>🎫 <strong>Registration</strong>: <a href="https://www.iscaconf.org/isca2025/attend/register.php">Sign Up Here</a></li>
        <li>📆 <strong>Paper Submission Deadline</strong>: Tuesday Apr 29, 2025, 7:59:59 AM UT</li>
        <li>🛎️ <strong>Notification of Acceptance</strong>: May 5, 2025</li>
    </ul>

    <h2>Introduction</h2>
    <p>Robots are becoming increasingly intelligent, evolving into embodied AI systems powered by advanced machine learning models—and that's exactly what we want. However, the computing stack that supports these embodied AI robots is lagging behind. This workshop aims to take the first step in bridging the gap between the computer architecture and robotics communities.</p>

    <p>The goal of building an efficient computing stack for embodied AI robots echoes what our field has achieved over the past decades: faster, more energy-efficient chips. Yet the challenges here are fundamentally different. Workloads are evolving rapidly, model inference demands are novel, real-time constraints are stringent, safety and reliability requirements are critical, and robots run out of power fast. This emerging domain presents a host of new and exciting challenges. Through this workshop, we aim to highlight these topics and bring them to the attention of the computer architecture community.</p>

    <p>The program will feature a mix of invited talks and contributed posters. We welcome submissions from all related areas—please refer to the CFP below for more details.</p>

    <h2>Call For Papers</h2>
    <h3>Topics of Interest</h3>
    <p>In general, we welcome system designers and researchers on <code>robotic computing</code> to join this workshop and present their ongoing works. The topics we are interested in include but are not limited to:</p>

    <div class="submission-guidelines">
        <h3>1. Innovative Computer Architecture Design for Robotic Computing</h3>
        <ul>
            <li><strong>Accelerators for localization, navigation, path planning, and robotic control algorithms</strong></li>
            <li><strong>Accelerators for vision-language-action and vision-language-model inference on edge devices</strong></li>
            <li><strong>Accelerators for LLM inference on edge devices</strong></li>
            <li><strong>Accelerating robotic computing algorithms with general-purpose processors</strong></li>
        </ul>

        <hr>

        <h3>2. Detailed Benchmarking for Embodied AI Systems</h3>
        <ul>
            <li><strong>Benchmarking for localization, navigation, path planning, and robotic control algorithms</strong></li>
            <li><strong>Benchmarking for vision-language-action and vision-language models</strong></li>
            <li><strong>Benchmarking for real embodied AI workloads</strong></li>
            <li><strong>Advanced chip design methodology</strong></li>
        </ul>

        <hr>

        <h3>3. Cost-Driven Chip Design</h3>
        <ul>
            <li><strong>Design-and-technology co-optimization</strong></li>
            <li><strong>Agile chip design (HLS and AI for EDA)</strong></li>
            <li><strong>Multi-chiplet design methodology</strong></li>
        </ul>
    </div>

    <h3>Submission Guidelines</h3>
    <div class="submission-guidelines">
        <ul>
            <li><strong>Arc4EAI welcomes submissions of short papers</strong>, limited to 2 pages (excluding references), formatted in a double-column layout. Authors are encouraged to use the provided <a href="./file/template.tex">LaTeX template</a>.</li>
            <li><strong>Submissions must clearly define the research problem, its motivation, and technical contributions</strong>, written in English and submitted as a single PDF file.</li>
            <li><strong>Papers may include works in progress, exploratory or preliminary studies, or previously published research</strong>.</li>
            <li><strong>Submissions will be evaluated based on novelty, technical quality, potential impact, community interest, clarity, relevance to the workshop, and reproducibility</strong>.</li>
            <li><strong>Reviews will be non-blind</strong>; authors must include their names and affiliations in the PDF without anonymization.</li>
            <li><strong>Accepted papers will not appear in formal proceedings</strong> but will be published on the workshop website, allowing authors to further develop and submit their work elsewhere.</li>
            <li><strong>At least one author of each accepted paper must attend the workshop and present their work</strong>.</li>
        </ul>
    </div>

    <h3>Paper Submission System</h3>
    <p>https://arch4eai25.hotcrp.com</p>

    <h2>Organizing Chairs and Bios</h2>
    <ul>
        <li><a href="https://airs.cuhk.edu.cn/en/team/1136">Dr. Shaoshan Liu</a></li>
        <li><a href="https://yiminggan.com/">Dr. Yiming Gan</a></li>
        <li><a href="https://xinghu-cs.github.io/">Dr. Xing Hu</a></li>
    </ul>

    <h2>Organizing Committee</h2>
    <ul>
        <li><strong>Web Chair</strong>: Wenhao Sun<br>Email: sunwenhao23@mails.ucas.ac.cn</li>
        <li><strong>Publicity Chair</strong>: Yuhui Hao<br>Email: yuhuihao@tju.edu.cn</li>
        <li><strong>Registration Chair</strong>: Mengdi Wang<br>Email: wangmengdi@ict.ac.cn</li>
    </ul>

    <h2>Online Participation</h2>
    <p>We are planning to support online participation. All the invited presenters will share their slides and talks via Zoom or other online meeting software.</p>

    <h2>Invited Speakers</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Title</th>
            <th>Affiliation</th>
            <th>Talk Topic</th>
        </tr>
        <tr>
            <td><a href="https://engineering.uci.edu/users/jean-luc-gaudiot">Jean-Luc Gaudiot</a></td>
            <td>Distinguished Professor</td>
            <td>UC Irvine</td>
            <td>Programming Languages for Embodied AI Systems</td>
        </tr>
    </table>

    <h2>Contact Us</h2>
    <p>Any questions may be directed to: <a href="mailto:ganyiming@ict.ac.cn">ganyiming@ict.ac.cn</a></p>
</body>
</html>
