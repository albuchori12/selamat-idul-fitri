<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Hari Raya Idul Fitri</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            background: url('https://images.unsplash.com/photo-1623920720184-760478cf87f0?q=80&w=2070&auto=format&fit=crop') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
        }

        .container {
            position: relative;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .text {
            color: white;
            text-shadow: 0 0 10px #00ff99, 0 0 20px #00ff99, 0 0 30px #00ff99;
            font-size: 3em;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 20px;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #00ff99, 0 0 20px #00ff99, 0 0 30px #00ff99;
            }
            to {
                text-shadow: 0 0 20px #00ccff, 0 0 30px #00ccff, 0 0 40px #00ccff;
            }
        }

        .star {
            position: absolute;
            border-radius: 50%;
            background: white;
            animation: twinkle 2s infinite;
        }

        @keyframes twinkle {
            0% { opacity: 0; transform: scale(0); }
            50% { opacity: 1; transform: scale(1); }
            100% { opacity: 0; transform: scale(0); }
        }

        .watermark {
            position: absolute;
            bottom: 10px;
            right: 10px;
            color: white;
            font-size: 1em;
            text-shadow: 0 0 5px black;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">
            Selamat Hari Raya Idul Fitri<br>Mohon Maaf Lahir dan Batin
        </div>
        <div class="watermark">by anak pengkor</div>
    </div>

    <script>
        // Membuat bintang-bintang secara acak
        function createStars() {
            const container = document.querySelector('.container');
            for (let i = 0; i < 100; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                
                // Ukuran acak
                const size = Math.random() * 3 + 1;
                star.style.width = `${size}px`;
                star.style.height = `${size}px`;
                
                // Posisi acak
                star.style.left = `${Math.random() * 100}vw`;
                star.style.top = `${Math.random() * 100}vh`;
                
                // Durasi animasi acak
                star.style.animationDuration = `${Math.random() * 2 + 1}s`;
                
                // Delay acak
                star.style.animationDelay = `${Math.random() * 2}s`;
                
                container.appendChild(star);
            }
        }

        // Panggil fungsi saat halaman dimuat
        window.onload = createStars;
    </script>
</body>
</html>
