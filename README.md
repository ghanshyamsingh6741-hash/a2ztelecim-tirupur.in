<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A2Z TELECOM | Professional Mobile Spares</title>
    <style>
        /* Color Theme: Orange (#FF6600), Black (#000000), White (#FFFFFF) */
        :root {
            --primary-orange: #FF6600;
            --bg-black: #000000;
            --card-gray: #121212;
            --text-white: #ffffff;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Segoe UI', Roboto, sans-serif; background-color: var(--bg-black); color: var(--text-white); line-height: 1.6; }

        /* Header & Navigation */
        header {
            background-color: var(--bg-black);
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 3px solid var(--primary-orange);
            position: sticky; top: 0; z-index: 1000;
        }
        .logo { font-size: 26px; font-weight: 800; color: var(--primary-orange); }
        .call-now {
            background: var(--primary-orange);
            color: black;
            padding: 10px 18px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        /* Management Banner */
        .mgmt-banner {
            background: #fff;
            color: #000;
            text-align: center;
            font-size: 0.85rem;
            padding: 5px 0;
            font-weight: bold;
            text-transform: uppercase;
        }

        /* Hero Section */
        .hero {
            padding: 80px 5%;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1556656793-062ff987b50d?q=80&w=1000&auto=format&fit=crop');
            background-size: cover;
            border-bottom: 5px solid var(--primary-orange);
        }
        .hero h1 { font-size: 3.5rem; margin-bottom: 10px; }
        .hero span { color: var(--primary-orange); }

        /* Parts Inventory Grid */
        .container { padding: 60px 5%; }
        .section-header { 
            text-align: center; 
            margin-bottom: 40px; 
            border-bottom: 2px solid var(--primary-orange);
            display: inline-block;
            margin-left: auto; margin-right: auto;
            width: 100%;
        }

        .parts-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .part-card {
            background: var(--card-gray);
            border: 1px solid #333;
            padding: 30px;
            border-radius: 12px;
            transition: all 0.3s ease;
            text-align: center;
        }
        .part-card:hover {
            border-color: var(--primary-orange);
            transform: translateY(-10px);
            background: #1a1a1a;
        }
        .part-card h3 { color: var(--primary-orange); font-size: 1.5rem; margin-bottom: 15px; }
        .part-card p { color: #bbb; font-size: 0.95rem; }

        /* Repair Kit Highlight */
        .kit-box {
            background: var(--primary-orange);
            color: black;
            margin-top: 50px;
            padding: 40px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .kit-text { flex: 1; min-width: 300px; }
        .kit-items { flex: 1; display: flex; flex-wrap: wrap; gap: 10px; min-width: 300px; }
        .tag { background: black; color: white; padding: 5px 15px; border-radius: 20px; font-size: 0.8rem; }

        /* Map Section */
        .map-section {
            padding: 50px 5%;
            text-align: center;
            background: #f9f9f9;
            color: #000;
        }
        .map-btn {
            display: inline-block;
            margin-top: 20px;
            background: #000;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .map-btn:hover { background: var(--primary-orange); color: black; }

        /* Footer */
        footer {
            padding: 50px 5%;
            text-align: center;
            background: #000;
            border-top: 1px solid #333;
        }
        .manager-credit { color: var(--primary-orange); font-weight: bold; margin-top: 10px; display: block; }
        
        /* Floating WhatsApp */
        .whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            color: white;
            padding: 15px;
            border-radius: 50%;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.2rem; }
        }
    </style>
</head>
<body>

    <div class="mgmt-banner">Website Managed by: Johny Singh Deora</div>

    <header>
        <div class="logo">A2Z TELECOM</div>
        <a href="tel:9500956627" class="call-now">📞 Call 9500956627</a>
    </header>

    <section class="hero">
        <h1>Welcome to <span>A2Z TELECOM</span></h1>
        <p>Your Trusted Wholesaler & Retailer for Mobile Spare Parts</p>
    </section>

    <div class="container">
        <h2 class="section-header">Premium Spare Parts Catalog</h2>
        
        <div class="parts-grid">
            <div class="part-card">
                <h3>📱 Combos</h3>
                <p>High-quality LCD and Touch assemblies for all Android & iPhone models. Testing warranty included.</p>
            </div>
            <div class="part-card">
                <h3>🔌 CC Boards</h3>
                <p>Complete Charging Connector boards with high-quality microphones and network components.</p>
            </div>
            <div class="part-card">
                <h3>📍 CC Pines</h3>
                <p>Original quality charging pins (Type-C, Micro V8) for bulk repair requirements.</p>
            </div>
            <div class="part-card">
                <h3>🚪 Back Doors</h3>
                <p>Premium glass and fiber back panels to make your phone look brand new.</p>
            </div>
            <div class="part-card">
                <h3>🏗️ Housing</h3>
                <p>Full middle frames and body housings available for all major brands.</p>
            </div>
            <div class="part-card">
                <h3>🔊 Ringer Sets</h3>
                <p>Crystal clear loud speakers and ringer buzzer modules for every mobile model.</p>
            </div>
        </div>

        <div class="kit-box">
            <div class="kit-text">
                <h2>Repairing Kits</h2>
                <p>Everything a professional technician needs to get the job done.</p>
            </div>
            <div class="kit-items">
                <span class="tag">Soldering Iron</span>
                <span class="tag">Multimeters</span>
                <span class="tag">Screwdriver Sets</span>
                <span class="tag">Glue T7000/E8000</span>
                <span class="tag">Display Opening Tools</span>
                <span class="tag">SMD Rework Station</span>
            </div>
        </div>
    </div>

    <section class="map-section">
        <h2>Find Our Shop</h2>
        <p>Visit us for the best deals on mobile parts and expert consultation.</p>
        <a href="https://maps.app.goo.gl/T2Qs4HjMpU8FBeFm6" class="map-btn" target="_blank">📍 Open in Google Maps</a>
    </section>

    <footer>
        <p>&copy; 2025 A2Z TELECOM. All Rights Reserved.</p>
        <p>Contact Support: 9500956627</p>
        <span class="manager-credit">Management: Johny Singh Deora</span>
    </footer>

    <a href="https://wa.me/919500956627" class="whatsapp" target="_blank">Chat</a>

</body>
</html>
