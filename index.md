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
        <img src="_assets/IMG_0803 Medium.png" alt="Ramanjeet Singh">
        <h1>Ramanjeet Singh</h1>
        <p>Senior iOS Developer | Swift | Objective-C | SwiftUI </p>
    </header>
    
    <main>
        <section id="about-me">
    <h2>About Me</h2>
    <div class="ticket">
        <p>I am an accomplished <strong>Senior iOS Developer with over 6 years of experience</strong> in mobile app development, specializing in Swift and Objective-C. My career has been shaped by my passion for building high-quality, user-friendly applications across various domains, including health, fitness, e-commerce, and entertainment. I pride myself on my ability to work efficiently with teams to deliver solutions that meet both user needs and business goals.</p>
        <p>I have extensive experience working with Apple frameworks, API integration, payment gateways, and cloud services like Firebase and AWS. Additionally, I am well-versed in version control systems such as Git and GitHub, as well as using modern architectures like MVVM, MVC, and VIPER. My focus is always on writing clean, efficient code, and I believe in continuously learning to stay up-to-date with the latest mobile development trends and tools.</p>
        <p>As a developer, I enjoy problem-solving and creating innovative solutions that impact users in meaningful ways. I am always looking for new challenges that push me to grow professionally and personally.</p>
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

        <section id="professional-experience">
    <h2>Professional Experience</h2>
    <div class="ticket">
        <p><strong>Accomplished Sr. iOS Developer</strong> with 6 years of progressive experience in mobile development, API integration, and user interface design. Proven track record at Cepoch, Chicmic, RV Technologies, and WebAstral in delivering high-quality applications on time, such as Red Precision, Wrkout, Africa Moko, and Better Together. Adept in Swift programming, Objective-C, and proficient in Xcode. Skilled in utilizing version control systems like Git and GitHub. Demonstrated expertise in Apple subscriptions, Stripe payment gateway integration, Firebase Remote Config, and AWS-S3 media upload. Career goal: to leverage technical skills and innovative solutions to drive impactful mobile application development projects.</p>
        <ul>
            <li>Worked on various architectures such as MVC, MVVM, and VIPER.</li>
            <li>Experienced with SwiftUI, RxSwift framework for creating and building mobile products.</li>
            <li>Basic knowledge of other languages: C, C++, Java.</li>
        </ul>
        <h3>Key Skills:</h3>
        <ul>
            <li>Proficient in Swift, Objective-C, and SwiftUI</li>
            <li>Expertise in MVVM, MVC, and VIPER architectures</li>
            <li>Extensive experience in API integration (Apple HealthKit, Firebase, Stripe, etc.)</li>
            <li>Familiar with RxSwift for reactive programming</li>
            <li>Payment gateway integration (Apple Pay, Stripe, PayPal, etc.)</li>
            <li>AWS-S3 media upload and Firebase Remote Config</li>
            <li>Version control systems: Git, GitHub</li>
            <li>Knowledge of other languages: C, C++, Java</li>
        </ul>
    </div>
</section>


<section id="work-history">
    <h2>Work History</h2>
    
    <div class="ticket">
        <p><strong>Sr. iOS Developer -- Cepoch LLC </strong> <em> - Sahibzada Ajit Singh Nagar (Mohali), PB</em><br>
        March 2023 to July 2024<br>
        </p>
        
        <ul>
            <li>Worked on Zoho Bug Tracker</li>
            <li>Worked on MapKit (Apple maps) and Google Map with direction APIs</li>
            <li>Worked on WebKit view with custom event (JavaScript evaluate functions for method passing)</li>
            <li>Integrated Apple Subscriptions / Stripe Payment Gateway</li>
            <li>Worked on chat with Socket.io</li>
            <li>Worked on AWS S3 media upload</li>
        </ul>
        
        <h3>Projects:</h3>
        <ul>
            <li><strong>Red Precision</strong>: A RoofTracing measurement app with Apple/Google maps integration, allowing users to calculate roof dimensions and other metrics.<br>Technologies: iOS, iPad, MVVM, Swift, WebView JS, Storkit.<br><a href="https://apps.apple.com/us/app/red-precision/id6447519133" target="_blank">App Store Link</a></li>
            <li><strong>Wrkout</strong>: A Gym Workout app where users can book trainers and schedule sessions, with chat features for premium members.<br>Technologies: iOS, MVVM, Swift, StoreKit.<br><a href="https://apps.apple.com/sa/app/wrkout/id6466780571" target="_blank">App Store Link</a></li>
            <li><strong>Straight Trippin</strong>: A travel planning platform with filters for attractions, hotels, food stops, and more.<br>Technologies: iOS, iPad, MVVM, Storkit.<br><a href="https://apps.apple.com/lt/app/straight-trippin/id6469703433" target="_blank">App Store Link</a></li>
            <li><strong>Deer’s Eye View</strong>: An app that simulates how animals see the world, offering pet owners a unique view.<br>Technologies: iOS, iPad, MVC, Swift.<br><a href="https://apps.apple.com/us/app/deers-eye-view/id6446702733" target="_blank">App Store Link</a></li>
        </ul>
    </div>
    
    <div class="ticket">
        <p><strong>iOS Developer -- Chicmic </strong><em> - Sahibzada Ajit Singh Nagar (Mohali), PB</em><br>
        Sep 2021 to Jan 2023<br>
        </p>
        
        <ul>
            <li>Worked on Health and Fitness features with Apple HealthKit, Fitbit APIs</li>
            <li>Worked on Apple TV app development</li>
            <li>Worked with RxSwift, RxCocoa framework and Coordinator pattern</li>
            <li>Integrated Apple Subscriptions / In-App Purchases</li>
            <li>Worked with Firebase Remote Config</li>
            <li>Used Adapty SDK for In-App Purchases</li>
            <li>Worked on Storyly SDK for Insta-like stories</li>
        </ul>
        
        <h3>Projects:</h3>
        <ul>
            <li><strong>Better Together (Weight Loss)</strong>: A weight loss app that syncs with Apple HealthKit and Fitbit for tracking challenges and health metrics.<br>Technologies: iOS, iPad, MVVM, Swift, RxSwift, Firebase, Storyly SDK, Adapty Paywall SDK, HealthKit, Fitbit, StoreKit.<br><a href="https://apps.apple.com/us/app/bettertogether-weight-loss/id1503465416" target="_blank">App Store Link</a></li>
            <li><strong>Urban Soccer</strong>: An Apple TV app providing live soccer scores in real time using sockets.<br>Technologies: tvOS, MVVM, Swift, Sockets.</li>
            <li><strong>Blyott Tracker</strong>: An app that tracks asset locations in hospitals via Bluetooth tags and Beacons.<br>Technologies: iOS, MVC, Swift.<br><a href="https://apps.apple.com/to/app/blyott/id1514589378" target="_blank">App Store Link</a></li>
        </ul>
    </div>
    
    <div class="ticket">
        <p><strong>iOS Developer -- RV Technologies </strong><em> - Sahibzada Ajit Singh Nagar (Mohali), PB</em><br>
        Aug 2018 to Aug 2021<br>
        </p>
        
        <ul>
            <li>Worked on multiple payment gateways including Apple Pay, Stripe, PayPal, Venmo, Braintree</li>
            <li>Worked with Firebase and Firestore real-time database</li>
            <li>Designed applications using AutoLayouts, MVVM pattern, and Codable protocols</li>
            <li>Modified existing software to correct coding errors and upgrade interfaces</li>
            <li>Worked on an Apple Watch application using an extension</li>
        </ul>
        
        <h3>Projects:</h3>
        <ul>
            <li><strong>From Auntie</strong>: An app that allows users to transfer money with an E-Gift card.<br>Technologies: iOS, MVVM, Swift, ApplePay, Venmo, Stripe.<br><a href="https://apps.apple.com/us/app/from-auntie/id1447798824" target="_blank">App Store Link</a></li>
            <li><strong>S.E.R.V.D</strong>: An app focused on restaurants, customers, and servers.<br>Technologies: iOS, MVVM, Swift, Sockets.<br><a href="https://apps.apple.com/us/app/s-e-r-v-d/id1469004372" target="_blank">App Store Link</a></li>
            <li><strong>CashWod</strong>: An app for daily routine exercise and gym competitions.<br>Technologies: iOS, iPad, MVC, Objective-C.<br><a href="https://apps.apple.com/us/app/cash-wod/id1446876525" target="_blank">App Store Link</a></li>
            <li><strong>MySocialstats</strong>: A social entertainment app where users can upload videos, comment, and make friends.<br>Technologies: iOS, iPad, MVC, Objective-C, Firebase.</li>
        </ul>
    </div>
    
    <div class="ticket">
        <p><strong>iOS Developer -- WebAstral </strong><em> - Sahibzada Ajit Singh Nagar (Mohali), PB</em><br>
        Jul 2017 to Aug 2018<br>
        </p>
        
        <ul>
            <li>Created new software as per client requirements</li>
            <li>Upgraded old Objective-C code to Swift</li>
            <li>Used frameworks like Alamofire and ObjectMapper</li>
            <li>Worked with Firebase and Firestore methods</li>
        </ul>
        
        <h3>Projects:</h3>
        <ul>
            <li><strong>Africa Moko</strong>: An entertainment app focused on Afro music (French version).<br>Technologies: iOS, MVC, Swift.</li>
            <li><strong>SweetGreet</strong>: A greeting app built in Objective-C.<br>Technologies: iOS, iPod, MVC, Objective-C.</li>
            <li><strong>TrueBoo</strong>: A dating app built in Objective-C.<br>Technologies: iOS, Objective-C.</li>
            <li><strong>Econtario</strong>: An educational app built in Swift 3.<br>Technologies: iOS, Swift.</li>
        </ul>
    </div>
    <div class="ticket">
    <h3>Custom Libraries (Pods)</h3>
    <ul>
        <li><strong>RJFloatingLabelTextField</strong>: A simple floating label library for easy integration in iOS apps.<br><a href="https://cocoapods.org/pods/RJFloatingLabelTextField" target="_blank">CocoaPods Link</a></li>
        <li><strong>RJMetronome</strong>: A metronome library to practice rhythm, complete with time signatures and subdivisions.<br><a href="https://github.com/raman43mann/RJMetronome" target="_blank">GitHub Link</a></li>
    </ul>
    </div>
</section>


        <section id="education">
    <h2>Education</h2>
    <div class="ticket">
        <p><strong>Master of Computer Applications (MCA) in Computer Science</strong></p>
        <p>College: Continental Group of Institutes, Fatehgarh Sahib/Sirhind, PB</p>
        <p>University: Punjabi University, Patiala</p>
        <p>Grade: First Division with Distinction (87% approx.)</p>
        <p>Industrial Training: 6-Month Industrial Training in iOS (Objective-C)</p>
    </div>
</section>


        <section id="contact">
    <h2>Contact</h2>
    <div class="ticket">
        <p>Email: <a href="mailto:rjmann43@gmail.com">rjmann43@gmail.com</a></p>
        <p>Phone: +91-86995-13960</p>
        <p>LinkedIn: <a href="https://in.linkedin.com/in/ramanjeet-singh-957201154" target="_blank">linkedin.com/in/ramanjeet-singh-957201154</a></p>
        <p>GitHub: <a href="https://github.com/raman43mann" target="_blank">github.com/raman43mann</a></p>
    </div>
</section>
    </main>

    <footer>
        <p>&copy; 2025 Ramanjeet Singh. All rights reserved.</p>
    </footer>
</body>
</html>
