# IYAZ
TESTING
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Recycling Campaign</title>
    <style>
        /* CSS: The Makeup (Setting up Canva-like fonts and colors) */
        body { font-family: 'Segoe UI', sans-serif; margin: 0; color: #333; }
        .container { width: 85%; margin: auto; padding: 40px 0; }

        /* 1. Video Section */
        .hero { background: #0b3c5d; color: white; padding: 60px 20px; text-align: center; }
        .video-box { width: 100%; max-width: 700px; margin: 20px auto; border-radius: 12px; overflow: hidden; }

        /* 2. Interactive Cards Grid */
        .card-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 30px; }
        .card { border: 2px solid #0b3c5d; padding: 20px; text-align: center; border-radius: 8px; transition: 0.3s ease; cursor: pointer; }
        /* Canva Hover Effect: Changes color smoothly when hovered! */
        .card:hover { background-color: #328cc1; color: white; transform: translateY(-5px); }

        /* 3. Flowchart / Step Section */
        .flowchart { display: flex; justify-content: space-between; gap: 15px; margin-top: 40px; flex-wrap: wrap; }
        .step { flex: 1; background: #f4f4f4; padding: 20px; border-radius: 8px; position: relative; min-width: 200px; }
    </style>
</head>
<body>

    <!-- HERO SECTION WITH VIDEO -->
    <header class="hero">
        <h1>How To Recycle</h1>
        <p>Let's keep the nutrients going for our planet.</p>
        <div class="video-box">
            <!-- Replace URL with your actual mp4 video link -->
            <video width="100%" controls poster="https://placeholder.com">
                <source src="https://w3schools.com" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
    </header>

    <main class="container">
        <!-- INTERACTIVE PACKAGING CARDS SECTION -->
        <section style="text-align: center;">
            <h2>Meet the Recyclables</h2>
            <p>Hover over the cards below to explore details:</p>
            <div class="card-grid">
                <div class="card"><h3>Brik Carton</h3><p>Portion Pack</p></div>
                <div class="card"><h3>Multiserve Pack</h3><p>Family Size</p></div>
                <div class="card"><h3>Gable Top</h3><p>Milk Carton</p></div>
                <div class="card"><h3>Plastic Bottle</h3><p>HDPE Plastic</p></div>
            </div>
        </section>

        <!-- FLOWCHART / TIMELINE SECTION -->
        <section style="margin-top: 60px;">
            <h2 style="text-align: center;">Life After Drink</h2>
            <div class="flowchart">
                <div class="step"><h3>1. Drop Off</h3><p>Leave at the center.</p></div>
                <div class="step"><h3>2. Shredding</h3><p>Mixed with water.</p></div>
                <div class="step"><h3>3. Extraction</h3><p>Fibers separated.</p></div>
                <div class="step"><h3>4. New Life</h3><p>Made into panel boards.</p></div>
            </div>
        </section>
    </main>

</body>
</html>
