
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata | Muhammad Hilmi Hudzakki</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            min-height: 100vh;
            background: linear-gradient(135deg, #071a38, #0b3d91, #1688d4);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 25px;
        }

        .container {
            width: 100%;
            max-width: 850px;
            background: rgba(255, 255, 255, 0.09);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(15px);
            animation: muncul 0.8s ease;
        }

        .header {
            text-align: center;
            padding: 40px 20px 30px;
            background: linear-gradient(
                135deg,
                rgba(0, 153, 255, 0.25),
                rgba(0, 64, 160, 0.15)
            );
        }

        .avatar {
            width: 115px;
            height: 115px;
            margin: 0 auto 20px;
            border-radius: 50%;
            background: linear-gradient(135deg, #60d5ff, #1769ff);
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 45px;
            font-weight: bold;
            color: white;
            border: 4px solid rgba(255, 255, 255, 0.8);
            box-shadow: 0 0 30px rgba(55, 174, 255, 0.5);
        }

        .header h1 {
            font-size: clamp(23px, 5vw, 34px);
            margin-bottom: 10px;
        }

        .header p {
            color: #c5e5ff;
            font-size: 15px;
        }

        .badge {
            display: inline-block;
            margin-top: 18px;
            padding: 8px 18px;
            border-radius: 30px;
            background: rgba(43, 173, 255, 0.2);
            border: 1px solid rgba(120, 207, 255, 0.4);
            font-size: 13px;
        }

        .content {
            padding: 30px;
        }

        .content h2 {
            font-size: 21px;
            margin-bottom: 22px;
            color: #8edaff;
        }

        .biodata {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 16px;
        }

        .item {
            padding: 20px;
            border-radius: 16px;
            background: rgba(5, 27, 65, 0.45);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: 0.3s;
        }

        .item:hover {
            transform: translateY(-5px);
            background: rgba(24, 117, 205, 0.35);
            border-color: rgba(113, 210, 255, 0.5);
        }

        .label {
            color: #9bcfff;
            font-size: 13px;
            margin-bottom: 10px;
            display: block;
        }

        .value {
            font-size: 16px;
            font-weight: 600;
            overflow-wrap: anywhere;
        }

        .hobby {
            grid-column: 1 / -1;
        }

        .footer {
            text-align: center;
            padding: 20px;
            color: #b8dcff;
            font-size: 13px;
            border-top: 1px solid rgba(255, 255, 255, 0.12);
        }

        .footer span {
            color: #65d5ff;
        }

        @keyframes muncul {
            from {
                opacity: 0;
                transform: translateY(25px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 550px) {
            body {
                padding: 15px;
            }

            .content {
                padding: 22px;
            }

            .biodata {
                grid-template-columns: 1fr;
            }

            .hobby {
                grid-column: auto;
            }
        }
    </style>
</head>

<body>

    <main class="container">

        <header class="header">
            <div class="avatar">MH</div>

            <h1>Muhammad Hilmi Hudzakki</h1>

            <p>Student Profile</p>

            <div class="badge">
                ✦ BIODATA DIRI ✦
            </div>
        </header>

        <section class="content">
            <h2>✧ Informasi Pribadi</h2>

            <div class="biodata">

                <div class="item">
                    <span class="label">👤 Nama Lengkap</span>
                    <div class="value">
                        Muhammad Hilmi Hudzakki
                    </div>
                </div>

                <div class="item">
                    <span class="label">📍 Alamat</span>
                    <div class="value">Mekarsari</div>
                </div>

                <div class="item">
                    <span class="label">🎂 Tanggal Lahir</span>
                    <div class="value">04 Desember 2010</div>
                </div>

                <div class="item">
                    <span class="label">🎓 Sekolah</span>
                    <div class="value">SMK Banjar Asri</div>
                </div>

                <div class="item hobby">
                    <span class="label">🎮 Hobi</span>
                    <div class="value">Bermain Game</div>
                </div>

            </div>
        </section>

        <footer class="footer">
            Designed with <span>♥</span> |
            <span>Personal Biodata Website</span>
        </footer>

    </main>

</body>
</html>
