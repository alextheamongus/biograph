<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blazepack Modpack</title>

    <style>
        /* Basic Reset and Body Styling */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #121212;
            color: #f0f0f0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        /* Page Container */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 30px auto;
            text-align: center;
        }

        /* Header Section */
        .header {
            padding: 40px;
            background: linear-gradient(135deg, #FF5733, #FF704D);
            color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            margin-bottom: 50px;
        }

        .header h1 {
            font-size: 3rem;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .header p {
            font-size: 1.4rem;
            margin-bottom: 25px;
            font-weight: 300;
        }

        .header .download-btn {
            display: inline-block;
            margin: 10px 15px;
            padding: 14px 30px;
            font-size: 1.1rem;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 8px;
            border: 2px solid #FF5733;
            transition: all 0.3s ease-in-out;
        }

        /* Fiery Hover and Tap Effect */
        @keyframes fireyGlow {
            0% {
                box-shadow: 0 0 5px #FF5733, 0 0 10px #FF5733, 0 0 20px #FF5733;
                transform: scale(1);
            }
            50% {
                box-shadow: 0 0 20px #FF704D, 0 0 40px #FF704D, 0 0 60px #FF704D;
                transform: scale(1.05);
            }
            100% {
                box-shadow: 0 0 5px #FF5733, 0 0 10px #FF5733, 0 0 20px #FF5733;
                transform: scale(1);
            }
        }

        .header .download-btn:hover,
        .download-btn.clicked {
            background-color: #FF5733;
            color: #222;
            animation: fireyGlow 1s ease-in-out infinite;
        }

        /* Help Section */
        .help {
            margin: 50px 0;
            text-align: center;
        }

        .help h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #FF5733;
            font-weight: bold;
        }

        .help p {
            margin-bottom: 35px;
            font-size: 1.1rem;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 25px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .contact-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
            border: 1px solid #333;
            border-radius: 12px;
            background-color: #222;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease-in-out;
        }

        /* Fiery Hover and Tap Effect for Contact Items */
        .contact-item:hover,
        .contact-item.clicked {
            transform: translateY(-5px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
            animation: fireyGlow 1.5s ease-in-out infinite;
        }

        .contact-item img {
            width: 70px;
            height: 70px;
            margin-bottom: 15px;
        }

        .contact-item span {
            font-size: 1.1rem;
            font-weight: 500;
            color: #FF5733;
        }

        /* Footer Section */
        .footer {
            margin-top: 50px;
            padding: 20px;
            font-size: 1rem;
            background: #2a2a2a;
            color: #aaa;
            border-radius: 10px;
            text-align: center;
        }

        .footer span {
            color: #FF5733;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <!-- Main Content Container -->
    <div class="container">

        <!-- Header Section -->
        <div class="header">
            <h1>Blazepack Modpack</h1>
            <p>Experience Minecraft like never before!</p>
            
            <!-- Download Buttons -->
            <div>
                <a href="https://drive.google.com/file/d/1IY5ZwZMy14Djg9J0nlsX_QcaH3fP7z7V/view?usp=sharing" class="download-btn">
                    Download for 1.19.4
                </a>
                <a href="https://drive.google.com/file/d/1ypdym0zaWsAMD2Fce7jWQkIjBzrq1AqF/view?usp=sharing" class="download-btn">
                    Download for 1.12.2
                </a>
            </div>
        </div>

        <!-- Help Section -->
        <div class="help">
            <h2>Need Assistance?</h2>
            <p>We're here to help! Contact us through Discord or Telegram:</p>

            <!-- Contact Grid -->
            <div class="contact-grid">

                <!-- Contact 1 -->
                <div class="contact-item">
                    <a href="https://discord.com/users/blazeywazey120" target="_blank">
                        <img src="https://cdn.icon-icons.com/icons2/1476/PNG/96/discord_101785.png" alt="Discord Icon">
                        <span>Blaze (Discord)</span>
                    </a>
                </div>

                <!-- Contact 2 -->
                <div class="contact-item">
                    <a href="https://discord.com/users/cookiesrbest" target="_blank">
                        <img src="https://cdn.icon-icons.com/icons2/1476/PNG/96/discord_101785.png" alt="Discord Icon">
                        <span>Cookie (Discord)</span>
                    </a>
                </div>

                <!-- Contact 3 -->
                <div class="contact-item">
                    <a href="https://t.me/livelaughlovetako" target="_blank">
                        <img src="https://cdn.icon-icons.com/icons2/923/PNG/96/telegram_icon-icons.com_72055.png" alt="Telegram Icon">
                        <span>Blaze (Telegram)</span>
                    </a>
                </div>

                <!-- Contact 4 -->
                <div class="contact-item">
                    <a href="https://t.me/cookie9666" target="_blank">
                        <img src="https://cdn.icon-icons.com/icons2/923/PNG/96/telegram_icon-icons.com_72055.png" alt="Telegram Icon">
                        <span>Cookie (Telegram)</span>
                    </a>
                </div>

            </div>
        </div>

        <!-- Footer Section -->
        <div class="footer">
            <p>Created with ❤️ by <span>Blaze</span> and <span>Cookie</span>.</p>
        </div>

    </div>

    <!-- JavaScript for Mobile Click Effect -->
    <script>
        // Add event listeners to buttons and contact items for tap/click
        const downloadButtons = document.querySelectorAll('.download-btn');
        const contactItems = document.querySelectorAll('.contact-item');

        // Function to add the "clicked" class for tap/click effects
        function addClickedClass(event) {
            event.preventDefault();
            this.classList.add('clicked');
            setTimeout(() => this.classList.remove('clicked'), 1000); // Remove class after animation duration
        }

        // Attach click event listeners
        downloadButtons.forEach(button => button.addEventListener('click', addClickedClass));
        contactItems.forEach(item => item.addEventListener('click', addClickedClass));
    </script>

</body>

</html>
