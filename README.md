<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HALAL WORK With ZORO TRADER</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b0b0b;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 420px;
            background: linear-gradient(180deg, #141414 0%, #080808 100%);
            border-radius: 20px;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.8);
            border: 1px solid #222;
        }

        .logo-container {
            width: 130px;
            height: 130px;
            margin: 0 auto 20px auto;
            border-radius: 24px;
            padding: 4px;
            background: linear-gradient(135deg, #ff7b00, #ff4500);
            box-shadow: 0 0 20px rgba(255, 123, 0, 0.4);
        }

        .logo-container img {
            width: 100%;
            height: 100%;
            border-radius: 20px;
            object-fit: cover;
            display: block;
        }

        .channel-subtitle {
            font-size: 11px;
            letter-spacing: 2px;
            color: #ff7b00;
            font-weight: 700;
            text-transform: uppercase;
            margin-bottom: 8px;
        }

        .channel-title {
            font-size: 22px;
            font-weight: 800;
            color: #ffffff;
            margin-bottom: 15px;
            line-height: 1.3;
        }

        .description {
            font-size: 13px;
            color: #b0b0b0;
            line-height: 1.6;
            margin-bottom: 25px;
            padding: 0 10px;
        }

        .join-btn {
            display: block;
            width: 100%;
            background: linear-gradient(90deg, #ff7b00 0%, #ff5500 100%);
            color: #ffffff;
            font-weight: 700;
            font-size: 15px;
            padding: 16px;
            border-radius: 14px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            box-shadow: 0 5px 20px rgba(255, 115, 0, 0.4);
            transition: all 0.3s ease;
            margin-bottom: 25px;
        }

        .join-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(255, 115, 0, 0.6);
        }

        .timer-box {
            background-color: #1a1410;
            border: 1px solid #331f12;
            border-radius: 14px;
            padding: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            margin-bottom: 30px;
        }

        .time-block {
            text-align: center;
        }

        .time-digits {
            font-size: 28px;
            font-weight: 700;
            color: #ffffff;
            font-family: monospace;
        }

        .time-label {
            font-size: 10px;
            color: #ff7b00;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .time-colon {
            font-size: 24px;
            font-weight: bold;
            color: #ff7b00;
            margin-top: -10px;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 12px;
            font-size: 11px;
            color: #888;
            margin-bottom: 15px;
        }

        .footer-links a {
            color: #888;
            text-decoration: none;
            transition: color 0.2s;
        }

        .footer-links a:hover {
            color: #ff7b00;
        }

        .copyright {
            font-size: 10px;
            color: #666;
            border-top: 1px solid #1a1a1a;
            padding-top: 15px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo / Image -->
        <div class="logo-container">
            <img src="https://i.ibb.co/hR4N03xk/IMG-20261112-171323-482.jpg" alt="Zoro Trader Logo">
        </div>

        <!-- Title & Subtitle -->
        <div class="channel-subtitle">Telegram Channel</div>
        <h1 class="channel-title">HALAL WORK With ZORO TRADER 📊</h1>

        <!-- Description -->
        <p class="description">
            Trusted market insights, disciplined research and honest updates — straight from the desk to your phone.
        </p>

        <!-- Join Button -->
        <a href="https://t.me/+dFhqMDkbdmZmMzc1" target="_blank" class="join-btn">
            ✈️ Join Telegram Channel
        </a>

        <!-- Countdown Timer -->
        <div class="timer-box">
            <div class="time-block">
                <div class="time-digits" id="minutes">04</div>
                <div class="time-label">Min</div>
            </div>
            <div class="time-colon">:</div>
            <div class="time-block">
                <div class="time-digits" id="seconds">56</div>
                <div class="time-label">Sec</div>
            </div>
        </div>

        <!-- Footer / Legal Links -->
        <div class="footer-links">
            <a href="#">Privacy Policy</a>
            <a href="#">Terms & Conditions</a>
            <a href="#">Disclaimer</a>
            <a href="#">Contact Us</a>
        </div>

        <div class="copyright">
            © 2026 HALAL WORK With ZORO TRADER. All rights reserved.
        </div>
    </div>

    <script>
        // Simple countdown timer script loop
        let totalSeconds = 4 * 60 + 56;
        const minEl = document.getElementById('minutes');
        const secEl = document.getElementById('seconds');

        setInterval(() => {
            if (totalSeconds > 0) {
                totalSeconds--;
                let m = Math.floor(totalSeconds / 60);
                let s = totalSeconds % 60;
                minEl.textContent = m < 10 ? '0' + m : m;
                secEl.textContent = s < 10 ? '0' + s : s;
            }
        }, 1000);
    </script>
</body>
</html>
