<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kinu's Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #1c1c1c;
            color: #f0f0f0;
        }
        .container {
            width: 500px;
            margin: 50px auto;
            padding: 20px;
            background: #292929;
            border: 1px solid #505050;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.5);
        }
        /* Icon */
        .icon img {
            border-radius: 50%;
            border: 2px solid #208bff;
        }
        /* Title and Subtitle */
        .title {
            font-size: 1.8rem;
            margin: 15px 0;
            color: #208bff;
        }
        .subtitle {
            font-size: 1rem;
            margin-bottom: 20px;
            color: #cccccc;
        }
        .skills h2, .connect h2 {
            font-size: 1.5rem;
            color: #f39c12;
            margin-bottom: 10px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s, transform 0.2s;
        }
        .btn.discord {
            background: #5865F2;
        }
        .btn.telegram {
            background: #0088cc;
        }
        .btn:hover {
            transform: scale(1.05);
            filter: brightness(1.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="icon">
            <img src="https://kys.confusing.wtf/r/iFdBKN.png" alt="Icon" width="100">
        </div>
        <h1 class="title">Hello, I'm Kinu! ฅ^•ﻌ•^ฅ</h1>
        <p class="subtitle">I'm a <strong>developer</strong> with a passion for coding. (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧</p>
        <div class="skills">
            <h2>💖 Skills</h2>
            <p><strong>Python</strong> (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧</p>
            <p><strong>Cybersecurity</strong> ☆*: .｡. o(≧▽≦)o .｡.:*☆</p>
        </div>
        <div class="connect">
            <h2>🌟 Connect</h2>
            <a href="https://discord.com/users/1216192858550304880" class="btn discord">Discord</a>
            <a href="https://wtf.confusing.wtf/u/JFoyUy.txt" class="btn telegram">Telegram</a>
        </div>
    </div>
</body>
</html>
