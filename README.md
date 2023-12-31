<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title> Home | Udemy Course Hub 🌟</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore free Udemy courses and enhance your skills!">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:400,700" />
    <link rel="icon" href="https://www.udemy.com/staticx/udemy/images/v6/favicon-96x96.png" type="image/x-icon" />
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            align-items: center;
            justify-content: center;
        }

        main {
            text-align: center;
            width: 100%;
            max-width: 600px;
        }

        h1 {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #FFA500; /* Orange color for header */
        }

        p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .enroll-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #FFA500; /* Orange color for button */
            color: #fff;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.5s ease-in-out;
        }

        .enroll-button:hover {
            background-color: #FF8C00; /* Darker orange on hover */
        }

        summary {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
            cursor: pointer;
            color: #2196f3; /* Blue color for summary */
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: #fff;
            margin-top: auto;
            width: 100%;
            border-radius: 5px;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            margin-right: 10px;
        }

        .footer-stamp {
            font-size: 14px;
            margin-top: 10px;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animated {
            animation-fill-mode: both;
        }

        .fadeInUp {
            animation-name: fadeInUp;
            animation-duration: 1s;
        }

        .emoji {
            font-size: 36px; /* Larger font size for emojis */
            margin-right: 10px; /* Add margin between text and emojis */
        }

        .countdown {
            font-size: 72px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #FFA500; /* Orange color for countdown */
            animation: pulse 1s infinite alternate;
        }

        @keyframes pulse {
            to {
                transform: scale(1.1);
            }
        }
    </style>
    <style>
        footer {
    text-align: center;
    padding: 20px 0;
    background-color: #2196f3; /* Blue background color for the footer */
    color: #fff; /* White text color */
    border-top: 2px solid #1e87db; /* Darker blue border on top */
}

.footer-links {
    margin-bottom: 10px;
}

.footer-links a {
    color: #fff;
    text-decoration: none;
    margin-right: 20px;
    font-weight: bold;
    font-size: 18px;
    transition: color 0.3s ease-in-out;
}

.footer-links a:hover {
    color: #1e87db; /* Darker blue color on hover */
}

.footer-stamp {
    font-size: 14px;
    margin-top: 10px;
}

    </style>
</head>

<body>
    <main>
        <h1 class="animated fadeInUp">🌟 Explore Free Udemy Courses 🚀</h1>
        <p class="animated fadeInUp">
            Supercharge your skills with our collection of free Udemy courses! 🆓
        </p>
        <p class="animated fadeInUp">
            Ready to embark on a learning adventure? Click the button below! 📚
        </p>
        <div class="countdown animated fadeInUp">10</div>
        <a href="tg://resolve?domain=udemy_robot" class="enroll-button animated fadeInUp" id="enrollButton" style="display:none;">Start Learning 🎉</a>
        <small>[ Disable adblocker to continue ]</small>
        <p class="animated fadeInUp">
            Join our community of 1 million+ learners who have already enrolled! 😍🤟
        </p>
        <details class="fade-in animated fadeInUp">
            <summary>
                <strong>🎁 Special Offer Inside! 🎉</strong>
            </summary>
            <p>
                Exciting news! We're giving away 💯% off coupons for our Udemy courses. Enroll for free and expand your knowledge! 🤩
            </p>
            <p>
                <strong>How to get the coupons?</strong><br> It's easy! Simply add our bot (
                <a href="https://t.me/udemy_robot?startgroup=true" target="_blank">@udemy_robot</a>) to your group. 🤗
            </p>
            <p>
                The bot will automatically send coupons to your group every 30 minutes. 🤖💰
            </p>
        </details>
    </main>

    <footer>
        <div class="footer-links">
            <a href="https://telegram.dog/TeleRoidGroup" target="_blank">Channel 💰</a>
            <a href="https://telegram.dog/TeleRoid14" target="_blank">Community 💬</a>
            <a href="https://telegram.me/MeARobo" target="_blank">Contact 🤖</a>
            <a href="javascript:alert('We don\'t store any cookies or your data, but we redirect you to a site that may have ads, and we are not responsible for them. You can check their privacy or terms on their website! (You are not allowed to scrape this site. Please respect our privacy agreement)')">Privacy 🔒</a>
        </div>
        <p class="footer-stamp">
            &copy; 2023 <a href="https://udemy.devpy.in" target="_blank">Udemy DevPY - @MrAbhi2k3</a> All rights reserved.
        </p>
    </footer>
    
    <script>
        window.addEventListener("DOMContentLoaded", () => {
            const animatedElements = document.querySelectorAll(".animated");
            animatedElements.forEach((element) => {
                element.classList.add("fadeInUp");
            });

            let countdownElement = document.querySelector('.countdown');
            let enrollButton = document.getElementById('enrollButton');

            let count = 10;
            let countdownInterval = setInterval(() => {
                count--;
                countdownElement.textContent = count;
                if (count === 0) {
                    clearInterval(countdownInterval);
                    countdownElement.style.display = 'none';
                    enrollButton.style.display = 'block';
                }
            }, 1000);
        });
    </script>
</body>

</html>
