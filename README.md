<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NMIT Project</title>
    <style>
        
        body {
            background: linear-gradient(-45deg, #380707, #021a45, #5d0c52, #571515);
            background-size: 400% 400%;
            color: white;
           
            animation: gradientShift 15s ease infinite;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }


    

        .nmit {
            background: rgb(9, 244, 72);
            text-align: center;
            width: 220px;
            border: none;
            
            font-family: 'Times New Roman', Times, serif;
            font-size: 60px;
            font-weight: bold;
            cursor: pointer;
            border-radius: 58px;
            transition: 0.3s;
            box-shadow: 0px 10px 20px rgba(0,0,0,0.3);
      
            
        }

        .nmit:hover {
            background: linear-gradient(45deg, #0e904f, #00c8ff);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.6); 
            transform: skew(-10deg) translateY(-5px) scale(1.02);
            color: #f0f0f0; 
        }

        .desc {
            max-width: 1200px;
            font-size: 20px;
            color: #ffffff;
            font-weight: normal;
            border-right: 2px solid #ffffff;
            white-space: normal;
            overflow: hidden;
            padding: 10px;
            line-height: 1.5;
            animation: typing 6s steps(120,end) forwards, blink 0.6s step-end infinite alternate; 
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        h1, h2, .title-large {
            color: rgb(0,200, 255);
            text-shadow: 0 0 10px rgba(0,200,255, 0.8);
            font-size: 36px;
            font-weight: bold;
        }

        .lin {
            border-radius: 26px;
            background-color: rgb(23, 164, 53);
            padding: 20px 60px;
            font-size: 40px;
            color: white;
            cursor: pointer;
            box-shadow: 0px 15px 40px 1px rgba(0, 0, 0, 0.5);
            display: inline-block;
            text-align: center;
            text-decoration: none;
            transition: 0.3s;
        }

        .lin:hover { transform: translateY(-10px); }

        .bu {
            border-radius: 16px;
            background-color: aqua;
            padding: 30px;
            width: 80%;
            max-width: 800px;
            font-size: 40px;
            display: inline-block;
            text-align: center;
            text-decoration: none; 
            color: black;
            border: none;
            box-shadow: 0px 10px 20px rgba(0,0,0,0.3);
            transition: 0.3s;
            font-weight: bold;
        }

        .bu:hover { transform: translateY(-5px); }

        .instagram {
            width: 400px;
            height: 100px;
            background: radial-gradient(circle at 30% 110%, #ffdb8b 0%, #ee653d 25%, #d42e81 50%, #a237b6 75%, #3e57bc 100%);
            border-radius: 37px;
            box-shadow: 0px 15px 40px 1px rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            transition: .2s linear;
            text-decoration: none;
            color: white;
            font-size: 30px;
            font-weight: bold;
            position: relative;
        }

        .instagram:hover { transform: translateY(-10px); }

        .startup{
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            border-radius: 20px;
            padding: 40px;
            color: #333;
            font-size: 34px;
            font-weight: bold;
            text-align: center;
            box-shadow: 0px 10px 20px rgba(0,0,0,0.2);
            transition: 0.3s;
        }

        .startup:hover {
            background: linear-gradient(45deg, #a18cd1, #fbc2eb);
            transform: translateY(-5px);
            color: #222;
        }
    </style>
</head>
<body>
    
     <div class="logo-container">
       <img src="https://via.placeholder.com/250x100?text=NMIT+LOGO" alt="NMIT Logo" class="main-logo">
      </div>

      <button class="nmit">NMIT</button>

      <p class="title-large">VISION OF FOUNDERS</p>
      
      <p style="font-size: 20px; text-align: center; max-width: 900px;">
        N.M.I.T gives you freedom to share your vibrant thoughts and creatively express yourself with stickers, GIFs, and using AI. We also provide study materials in our official WhatsApp channel "Nmit students".
    </p>

    <p class="desc">
        N.M.I.T is a vibrant student-led group created with the vision of bringing students together beyond academics.
        It is a space where fun, sports, learning, and emotional well-being go hand in hand. The group not only
        encourages students to explore their interests in games, activities, and creative events but also provides a supportive 
        environment to share thoughts and overcome challenges like stress and depression. At N.M.I.T, we believe that college life 
        should be a balance of growth, enjoyment, and self-care. Through teamwork, open discussions, and engaging activities,
        the group fosters a sense of belonging where students can learn, relax, and thrive together.
    </p>

    <br><br>

    <p class="title-large">WHY JOIN N.M.I.T?</p>

    <div style="font-size: 20px; text-align: left; max-width: 900px;">
        <p>Joining N.M.I.T means becoming part of a supportive and energetic student community where you're never alone. Here, you’ll find a space to:</p>
        <p>🎉 Have Fun – Take part in exciting events, games, and creative activities that make college life memorable.</p>
        <p>🏆 Stay Active – Engage in sports and competitions that keep you fit, motivated, and full of team spirit.</p>
        <p>💬 Find Support – Share your thoughts freely and get encouragement during tough times like stress or depression.</p>
        <p>📚 Learn & Grow – Gain new skills, explore ideas, and learn from peers in a collaborative environment.</p>
        <p>🤝 Build Friendships – Meet like-minded students, make lasting connections, and be part of a family that grows together.</p>
    </div>

    <br>
    <br>

    <br>
    <a class="startup" href="https://sthanamitra.vercel.app"><strong>OUR STARTUP</strong></a>
    <br>
    <br>
    <br>
        <a href="https://bithub.co.in/index.html" class="bu">NOTES FROM SENIORS</a>
    <br>
    <br>
    <p class="title-large">Contacts</p>
    <br>

    <a class="lin" href="https://chat.whatsapp.com/FfkFriVgOM66YPAt5Lnst0?mode=ems_copy_t">WhatsApp</a>

    <br><br>
    <p style="font-size: 20px;"><strong>EMAIL-ID: nanhimutthi@gmail.com</strong></p>
    <br>

    <a class="instagram" href="https://www.instagram.com/bitd.matchmaking?igsh=MXh0NmRuZzFlN3VjcQ==">
        <strong>INSTAGRAM</strong>
    </a>
    


</body>
</html>
