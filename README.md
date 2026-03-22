<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Dulguun!</title>
    <style>
        body { 
            background: #fafafa; 
            font-family: 'Helvetica', sans-serif; 
            display: flex; 
            justify-content: center; 
            align-items: center; 
            height: 100vh; 
            margin: 0;
            color: #1a1a1a;
        }
        .container { 
            text-align: center; 
            border: 1px solid #eee;
            padding: 60px 40px;
            background: white;
            letter-spacing: 1px;
        }
        h1 { 
            font-size: 2.5rem; 
            text-transform: uppercase;
            margin-bottom: 10px;
            font-weight: 300;
        }
        .name {
            font-weight: 800;
            color: #d4af37; /* Gold touch */
            display: block;
            font-size: 3.5rem;
        }
        p { font-size: 0.9rem; color: #666; text-transform: uppercase; margin-top: 20px;}
        .emoji { font-size: 2rem; margin-top: 20px; display: block; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday</h1>
        <span class="name">DULGUUN</span>
        <p>Wishing you a year of cinematic moments and endless joy.</p>
        <span class="emoji">✨ 🎂 ✨</span>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
    <script>
        setTimeout(() => {
            confetti({
                particleCount: 150,
                spread: 70,
                origin: { y: 0.6 },
                colors: ['#d4af37', '#1a1a1a', '#ffffff']
            });
        }, 500);
    </script>
</body>
</html>
