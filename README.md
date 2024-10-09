<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Bear-ey Excited Baby Shower RSVP</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: #ff6f61;
            font-size: 36px;
            margin-bottom: 10px;
        }
        p {
            font-size: 18px;
            color: #555;
            margin-bottom: 30px;
        }
        .bear-image {
            margin-bottom: 20px;
        }
        img {
            width: 150px;
            height: auto;
        }
        .rsvp-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            text-align: left;
            font-size: 16px;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        button {
            background-color: #ff6f61;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #ff4f41;
        }
        .footer {
            margin-top: 20px;
            font-size: 14px;
            color: #999;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="bear-image">
            <img src="https://example.com/bear.png" alt="Bear Image"> <!-- Replace this URL with an actual bear image -->
        </div>

        <h1>We're Bear-ey Excited!</h1>
        <p>Join us for a coed baby shower! Please RSVP by filling out the form below.</p>

        <div class="rsvp-form">
            <form action="https://formspree.io/f/{your_form_id}" method="POST">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="attendance">Will you be attending?</label>
                <select id="attendance" name="attendance" required>
                    <option value="Yes">Yes</option>
                    <option value="No">No</option>
                    <option value="Maybe">Maybe</option>
                </select>

                <label for="message">Message (Optional):</label>
                <textarea id="message" name="message" rows="4" placeholder="Leave us a message!"></textarea>

                <button type="submit">Submit RSVP</button>
            </form>
        </div>

        <div class="footer">
            <p>We're looking forward to seeing you there!</p>
        </div>
    </div>

</body>
</html>
