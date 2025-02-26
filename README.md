<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Join TheNewKashmir Team</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
        }
        .container {
            width: 50%;
            background: white;
            padding: 20px;
            margin: auto;
            margin-top: 30px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px gray;
        }
        img {
            width: 100%;
            border-radius: 10px;
        }
        h2 {
            color: #333;
        }
        p {
            font-size: 14px;
            color: #666;
        }
        label {
            font-weight: bold;
            text-align: left;
            display: block;
            margin-top: 10px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #d9534f;
            color: white;
            padding: 10px;
            border: none;
            width: 100%;
            margin-top: 15px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        button:hover {
            background-color: #c9302c;
        }
        .footer {
            margin-top: 20px;
            font-size: 12px;
            color: gray;
        }
        .social-links a {
            display: block;
            text-decoration: none;
            color: #d9534f;
            margin-top: 5px;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="IMG_0413.jpeg" alt="TheNewKashmir Logo">
        <h2>Join TheNewKashmir Team</h2>
        <p>We are looking for passionate individuals from <strong>Jammu & Kashmir</strong> to report and share news from their districts.</p>
        <p><strong>Salary:</strong> ₹10,000 - ₹22,000 | <strong>Experience:</strong> 1 Year in Media/Social Media</p>
        
        <form action="submit_form.php" method="POST" enctype="multipart/form-data">
            <label for="full_name">Full Name:</label>
            <input type="text" id="full_name" name="full_name" required>

            <label for="district">District:</label>
            <select id="district" name="district" required>
                <option value="">Select Your District</option>
                <option value="Srinagar">Srinagar</option>
                <option value="Anantnag">Anantnag</option>
                <option value="Baramulla">Baramulla</option>
                <option value="Pulwama">Pulwama</option>
                <option value="Kupwara">Kupwara</option>
                <option value="Jammu">Jammu</option>
                <option value="Kathua">Kathua</option>
                <option value="Udhampur">Udhampur</option>
                <option value="Rajouri">Rajouri</option>
                <option value="Poonch">Poonch</option>
            </select>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="email">Email ID:</label>
            <input type="email" id="email" name="email" required>

            <label for="experience">Experience in Media (Years):</label>
            <input type="number" id="experience" name="experience" min="1" max="20" required>

            <label for="social_media">Social Media Handle (Instagram/Facebook/Youtube):</label>
            <input type="text" id="social_media" name="social_media" required>

            <label for="resume">Upload Resume / ID Proof:</label>
            <input type="file" id="resume" name="resume" required>

            <label for="message">Why do you want to join TheNewKashmir?</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Submit Application</button>
        </form>

        <div class="social-links">
            <p>Follow Us:</p>
            <a href="https://www.youtube.com/@TheNewKashmir" target="_blank">YouTube: TheNewKashmir</a>
            <a href="https://www.instagram.com/thenewkashmir" target="_blank">Instagram: @thenewkashmir</a>
            <a href="https://www.facebook.com/profile.php?id=1000344017948" target="_blank">Facebook: TheNewKashmir</a>
        </div>

        <p class="footer">For any queries, contact us at: <strong>Maxrouf21@gmail.com</strong></p>
    </div>

</body>
</html>
