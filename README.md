# shiv-demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Thrift Edit | Curated Vintage</title>
    <style>
        :root {
            --bg-color: #f7f7f2; /* Off-white vintage feel */
            --accent: #3a5a40;   /* Deep thrift-store green */
            --card-bg: #ffffff;
            --text: #2d2d2d;
        }

        body {
            font-family: 'Helvetica Neue', sans-serif;
            background-color: var(--bg-color);
            color: var(--text);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Hero Section */
        header {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.1)), url('https://images.unsplash.com/photo-1558769132-cb1aea458c5e?auto=format&fit=crop&q=80&w=1000');
            background-size: cover;
            background-position: center;
            color: white;
        }

        header h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            letter-spacing: -2px;
        }

        /* Bento Grid Layout */
        .container {
            max-width: 1100px;
            margin: -50px auto 50px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .store-card {
            background: var(--card-bg);
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
            border: 1px solid #eee;
        }

        .store-card:hover {
            transform: translateY(-10px);
        }

        .tag {
            display: inline-block;
            background: #e9ecef;
            padding: 5px 12px;
            border-radius: 50px;
            font-size: 0.75rem;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
        }

        .store-card h2 {
            margin: 0 0 10px 0;
            font-size: 1.5rem;
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: var(--accent);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 500;
        }

        footer {
            text-align: center;
            padding: 40px;
            font-size: 0.9rem;
            opacity: 0.7;
        }
    </style>
</head>
<body>

    <header>
        <h1>THE THRIFT EDIT</h1>
        <p>Your 2026 guide to sustainable style.</p>
    </header>

    <div class="container">
        <div class="store-card">
            <span class="tag">#Y2K #STREETWEAR</span>
            <h2>ZThrifts</h2>
            <p>The ultimate hub for verified sellers. If it's trending on TikTok, it's here.</p>
            <a href="#" class="btn">Shop Now</a>
        </div>

        <div class="store-card">
            <span class="tag">#MINIMALIST #LUXURY</span>
            <h2>AAINAA</h2>
            <p>Curated high-end vintage with a focus on silhouettes and neutral tones.</p>
            <a href="#" class="btn">View Drops</a>
        </div>

        <div class="store-card">
            <span class="tag">#90sDENIM #CASUAL</span>
            <h2>Rewago</h2>
            <p>Specializing in pre-loved denim and oversized flannels. Perfect for everyday wear.</p>
            <a href="#" class="btn">Browse</a>
        </div>

        <div class="store-card">
            <span class="tag">#BOHEMIAN #PRINTS</span>
            <h2>Bombay Closet Cleanse</h2>
            <p>Eclectic prints, sustainable vibes, and community-driven fashion events.</p>
            <a href="#" class="btn">Check it out</a>
        </div>
    </div>

    <footer>
        <p>© 2026 Curated by [Your Name]. Stay stylish, stay sustainable.</p>
    </footer>

</body>
</html>
