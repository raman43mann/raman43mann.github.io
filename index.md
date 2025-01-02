<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramanjeet Singh Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #ff8c42, #ff7043);
            color: white;
            padding: 40px 20px;
            text-align: center;
            position: relative;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 5px solid white;
            position: absolute;
            left: 50%;
            transform: translate(-50%, 50%);
        }

        header h1 {
            margin: 100px 0 10px;
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            margin: 0;
        }

        main {
            padding: 60px 20px 20px;
        }

        section {
            margin-bottom: 40px;
        }

        section h2 {
            font-size: 1.8em;
            margin-bottom: 20px;
            color: #ff8c42;
            position: relative;
        }

        section h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background: #ff8c42;
            margin-top: 5px;
        }

        .ticket {
            padding: 15px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border: 1px dashed #ff8c42;
            margin-bottom: 20px;
            position: relative;
        }

        .ticket:before, .ticket:after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background: #fff;
            border: 3px solid #ff8c42;
            border-radius: 50%;
            top: 50%;
            transform: translateY(-50%);
        }

        .ticket:before {
            left: -10px;
        }

        .ticket:after {
            right: -10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #ff8c42;
            color: white;
        }

        a {
            color: #ff8c42;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <img src="assets/IMG_0803 Medium.png" alt="Ramanjeet Singh">
        <h1>Ramanjeet Singh</h1>
        <p>Senior iOS Developer | Swift & Objective-C Expert</p>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <div class="ticket">
                <p>With over 6.5 years of experience in mobile software development, I specialize in creating high-performance iOS applications. My expertise lies in Swift, Objective-C, and various iOS frameworks and tools, delivering robust and scalable solutions tailored to client needs.</p>
            </div>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="ticket">
                <p><strong>Programming Languages:</strong> Swift, Objective-C</p>
                <p><strong>Frameworks:</strong> UIKit, AVFoundation, Core Location, MapKit, HealthKit, Core Animation, In-App Purchases, Push Notifications</p>
                <p><strong>Tools:</strong> Xcode, Interface Builder, Accessibility Inspector, Git</p>
                <p><strong>APIs and Integrations:</strong> RESTful APIs, JSON, Firebase, Payment Gateways, Third-party SDKs (CocoaPods, SPM)</p>
                <p><strong>Database:</strong> Core Data, Realm, User Defaults, Keychain</p>
                <p><strong>App Distribution:</strong> App Store, TestFlight, Diawi</p>
            </div>
        </section>

        <section id="experience">
            <h2>Professional Experience</h2>
            <div class="ticket">
                <p><strong>Senior iOS Developer - 6.5 Years</strong></p>
                <p>Developed and maintained iOS applications using Swift and Objective-C.</p>
                <p>Implemented features like MapKit, HealthKit, Firebase integration, and payment gateways.</p>
                <p>Published multiple applications on the App Store and handled updates and bug fixes.</p>
                <p>Collaborated with cross-functional teams to ensure project success.</p>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="ticket">
                <p><strong>Red Precision:</strong> A roof tracing measurement app. <a href="https://apps.apple.com/us/app/red-precision/id6447519133" target="_blank">App Store Link</a></p>
                <p><strong>Wrkout:</strong> A gym workout app. <a href="https://apps.apple.com/sa/app/wrkout/id6466780571" target="_blank">App Store Link</a></p>
                <p><strong>Straight Trippin:</strong> A travel planning platform. <a href="https://apps.apple.com/lt/app/straight-trippin/id6469703433" target="_blank">App Store Link</a></p>
                <p><strong>Deer’s Eye View:</strong> An app showcasing animal vision. <a href="https://apps.apple.com/us/app/deers-eye-view/id6446702733" target="_blank">App Store Link</a></p>
            </div>
        </section>

        <section id="education">
            <h2>Education</h2>
            <div class="ticket">
                <p><strong>Bachelor of Technology in Computer Science</strong></p>
                <p>Graduated with distinction, focusing on mobile and software development.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <div class="ticket">
                <p>Email: ramanjeet.singh@example.com</p>
                <p>Phone: +91-12345-67890</p>
                <p>LinkedIn: <a href="https://linkedin.com/in/ramanjeetsingh" target="_blank">linkedin.com/in/ramanjeetsingh</a></p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Ramanjeet Singh. All rights reserved.</p>
    </footer>
</body>
</html>
