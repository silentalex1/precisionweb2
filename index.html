<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Precision Store</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            background: linear-gradient(135deg, #0d0d2b, #1c1c3d, #31318a);
            font-family: 'Poppins', sans-serif;
            color: #ffffff;
            transition: all 0.3s ease;
            scroll-behavior: smooth;
        }

        .navbar {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            width: 90%;
            max-width: 1200px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 15px 20px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(15px);
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.15);
            z-index: 1000;
        }

        .navbar-text {
            font-size: 28px;
            font-weight: 700;
            color: #f5f5f5;
            text-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            letter-spacing: 1px;
        }

        .navbar button {
            background: linear-gradient(135deg, #4e54c8, #8f94fb);
            color: #ffffff;
            border-radius: 12px;
            padding: 10px 20px;
            font-size: 14px;
            margin-left: 10px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            border: none;
        }

        .navbar button:hover {
            background: linear-gradient(135deg, #8f94fb, #4e54c8);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
            transform: scale(1.05);
        }

        .navbar button:active {
            transform: scale(0.95);
        }

        .container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            width: 100%;
            max-width: 1200px;
            margin: 120px auto 0;
            padding: 0 20px;
        }

        .section {
            padding: 80px 0;
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 0.8s ease, transform 0.8s ease;
        }

        .section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .image-container {
            flex: 1;
            max-width: 550px;
            margin-right: 20px;
            perspective: 1000px;
        }

        .image-container img {
            width: 100%;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.6);
            transition: transform 0.4s ease, box-shadow 0.4s ease, opacity 0.3s ease;
            opacity: 0;
        }

        .image-container img:hover {
            transform: scale(1.03);
            box-shadow: 0 15px 60px rgba(0, 0, 0, 0.8);
        }

        .image-container img.loaded {
            opacity: 1;
        }

        .faq-container {
            flex: 1;
            max-width: 500px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 50px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(20px);
        }

        .faq-container h2 {
            font-size: 26px;
            font-weight: 700;
            color: #ffffff;
            margin-bottom: 20px;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            text-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }

        .faq-item {
            background: rgba(255, 255, 255, 0.15);
            border-radius: 12px;
            margin-bottom: 15px;
            padding: 20px;
            cursor: pointer;
            transition: background 0.3s ease, transform 0.3s ease;
            font-size: 18px;
            color: #f0f0f0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }

        .faq-item:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-3px);
        }

        .faq-answer {
            display: none;
            margin-top: 10px;
            color: #d0d0d0;
            font-size: 16px;
            line-height: 1.6;
        }

        .faq-item.active .faq-answer {
            display: block;
        }

        .showcase-video {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 100px 20px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            box-shadow: 0 10px 50px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(20px);
            max-width: 1200px;
            margin: 50px auto;
        }

        .showcase-video h2 {
            font-size: 28px;
            font-weight: 700;
            color: #ffffff;
            text-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            margin-bottom: 10px;
            text-align: center;
        }

        .showcase-video p {
            font-size: 16px;
            color: #d0d0d0;
            margin-bottom: 30px;
            text-align: center;
        }

        .showcase-video video {
            width: 80%;
            max-width: 900px;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.6);
        }

        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }

            .image-container, .faq-container {
                max-width: 100%;
                margin-right: 0;
                margin-bottom: 20px;
            }

            .navbar {
                top: 10px;
                width: 95%;
                padding: 8px 12px;
            }

            .navbar-text {
                font-size: 24px;
            }

            .navbar button {
                padding: 8px 12px;
                font-size: 12px;
                margin: 5px 0;
            }

            .faq-container h2 {
                font-size: 24px;
            }

            .faq-item {
                font-size: 16px;
                padding: 10px;
            }

            .faq-answer {
                font-size: 14px;
            }

            .showcase-video h2 {
                font-size: 24px;
            }

            .showcase-video p {
                font-size: 14px;
            }

            .showcase-video video {
                width: 95%;
            }
        }

        @media (max-width: 480px) {
            .navbar-text {
                font-size: 20px;
            }

            .navbar button {
                padding: 6px 10px;
                font-size: 10px;
            }

            .faq-container h2 {
                font-size: 22px;
            }

            .faq-item {
                font-size: 14px;
                padding: 8px;
            }

            .faq-answer {
                font-size: 12px;
            }

            .showcase-video h2 {
                font-size: 20px;
            }

            .showcase-video p {
                font-size: 12px;
            }

            .showcase-video video {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="navbar-text">Precision Store</div>
        <div>
            <button onclick="window.location.href='https://discord.gg/sewS6cAyD3'">Discord Invite</button>
            <button onclick="window.location.href='https://www.youtube.com/@ThatNormalExploiter'">Showcase</button>
            <button onclick="window.location.href='tos.html'">TOS</button>
            <button onclick="window.location.href='feedback.html'">Feedback</button>
        </div>
    </div>

    <div class="container">
        <div class="section image-container">
            <img src="https://raw.githubusercontent.com/silentalex1/precisionweb2/main/precision.png" alt="Precision Image" loading="eager">
        </div>

        <div class="section faq-container">
            <h2>FAQ</h2>
            <div class="faq-item">
                <div>What is this for?</div>
                <div class="faq-answer">This is a Roblox cheating script, for you to cheat on Roblox and be unfair. This script is a paid script which only costs $5 as of right now, which may change in the future.</div>
            </div>
            <div class="faq-item">
                <div>What is the price of the script?</div>
                <div class="faq-answer">As of right now the universal script costs $5. In the future, or if the script gets well-known, the price may change.</div>
            </div>
            <div class="faq-item">
                <div>How do I buy the script?</div>
                <div class="faq-answer">Join the discord server, create a ticket and ping the owner one time and wait for more instructions.</div>
            </div>
            <div class="faq-item">
                <div>What do I do after I buy the script?</div>
                <div class="faq-answer">After you buy the script, join the Discord server and verify your ID Auth key from your email or from our upcoming discord bot.</div>
            </div>
            <div class="faq-item">
                <div>I can't execute the script, why is that?</div>
                <div class="faq-answer">Your executor might not be supported or you might have been blacklisted.</div>
            </div>
        </div>
    </div>

    <div class="section showcase-video">
        <h2>Showcase Video</h2>
        <p>No video yet, but this is where it will be.</p>
        <video controls autoplay muted loop>
            <source src="upcomingvid.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>

    <script>
        const sections = document.querySelectorAll('.section');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.3 });

        sections.forEach(section => {
            observer.observe(section);
        });

        document.querySelectorAll('.faq-item').forEach(item => {
            item.addEventListener('click', () => {
                item.classList.toggle('active');
            });
        });

        document.querySelector('.image-container img').addEventListener('load', function() {
            this.classList.add('loaded');
        });

        document.querySelector('.image-container').addEventListener('mousemove', (e) => {
            const container = e.currentTarget;
            const rect = container.getBoundingClientRect();
            const x = (e.clientX - rect.left - rect.width / 2) / rect.width * 30;
            const y = (e.clientY - rect.top - rect.height / 2) / rect.height * 30;

            container.querySelector('img').style.transform = `rotateY(${x}deg) rotateX(${-y}deg)`;
        });

        document.querySelector('.image-container').addEventListener('mouseleave', (e) => {
            e.currentTarget.querySelector('img').style.transform = 'rotateY(0deg) rotateX(0deg)';
        });
    </script>
</body>
</html>
