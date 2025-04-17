<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Sederhana</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .profile-img {
            display: block;
            margin: 0 auto 20px;
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .info {
            margin-bottom: 15px;
        }
        .info label {
            font-weight: bold;
        }

        /* Media Queries for Responsive Design */
        @media (max-width: 600px) {
            .container {
                padding: 15px;
            }
            .profile-img {
                width: 120px;
                height: 120px;
            }
            h1 {
                font-size: 24px;
            }
            .info {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Profil Saya</h1>
    <img src="https://via.placeholder.com/150" alt="Foto Profil" class="profile-img">
    
    <div class="info">
        <label>Nama:</label>
        <p>John Doe</p>
    </div>
    <div class="info">
        <label>Usia:</label>
        <p>25 Tahun</p>
    </div>
    <div class="info">
        <label>Email:</label>
        <p>johndoe@example.com</p>
    </div>
    <div class="info">
        <label>Tentang Saya:</label>
        <p>Saya seorang pengembang web yang menyukai teknologi dan desain. Saya selalu berusaha untuk belajar hal baru dan meningkatkan keterampilan saya.</p>
    </div>
</div>

</body>
</html>
