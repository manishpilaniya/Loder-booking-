<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Card</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e9ebee;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .profile-card {
            background-color: white;
            width: 350px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            overflow: hidden;
            text-align: center;
        }
        .cover-image {
            width: 100%;
            height: 180px;
            object-fit: cover;
            /* Yahan 8920.jpg (Tractors) background ke roop me aayegi */
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
            margin-top: -60px; /* Photo ko cover image ke upar laane ke liye */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            /* Yahan 8924.png (Aapki photo) aayegi */
        }
        .info {
            padding: 15px 20px 25px;
        }
        .info h2 {
            margin: 10px 0 5px;
            color: #1c1e21;
            font-size: 22px;
        }
        .info p {
            color: #606770;
            margin: 0;
            font-size: 15px;
        }
        .button {
            display: inline-block;
            margin-top: 15px;
            padding: 8px 20px;
            background-color: #1877f2;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .button:hover {
            background-color: #166fe5;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <!-- Tractor Photo as Cover Background -->
        <img src="8920.jpg" alt="Cover Image" class="cover-image">
        
        <div class="info">
            <!-- Your Portrait Photo as Profile Picture -->
            <img src="8924.png" alt="Profile Picture" class="profile-pic">
            
            <h2>Dinesh Bajar</h2>
            <p>Agriculture & Tractor Services</p>
            
            <a href="#" class="button">Contact Me</a>
        </div>
    </div>

</body>
</html>

