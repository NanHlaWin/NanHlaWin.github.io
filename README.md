<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elegant One-Page</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 30px;
        }
        
        .cta-button {
            display: inline-block;
            background: white;
            color: #764ba2;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        /* Features Section */
        .features {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 2rem;
            color: #444;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: transform 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: #667eea;
            margin-bottom: 20px;
        }
        
        .feature-title {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: #444;
        }
        
        /* Footer */
        footer {
            background: #f8f9fa;
            padding: 30px 0;
            text-align: center;
            color: #666;
        }
        
        .social-links {
            margin: 20px 0;
        }
        
        .social-links a {
            color: #667eea;
            margin: 0 10px;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }
        
        .social-links a:hover {
            color: #764ba2;
        }
        
        .copyright {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Elegant</div>
            <div class="tagline">A simple, beautiful one-page template for your next project</div>
            <a href="#features" class="cta-button">Explore Features</a>
        </div>
    </header>
    
    <section id="features" class="features">
        <div class="container">
            <h2 class="section-title">Our Amazing Features</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">✨</div>
                    <h3 class="feature-title">Clean Design</h3>
                    <p>Minimal and modern design that focuses on your content and enhances user experience.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3 class="feature-title">Fast Performance</h3>
                    <p>Optimized code and assets to ensure your website loads quickly on all devices.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">📱</div>
                    <h3 class="feature-title">Responsive</h3>
                    <p>Looks great on any device, from mobile phones to large desktop screens.</p>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="#">📱</a>
                <a href="#">📧</a>
                <a href="#">🐦</a>
                <a href="#">📘</a>
            </div>
            <div class="copyright">
                &copy; 2023 Elegant One-Page. All rights reserved.
            </div>
        </div>
    </footer>
</body>
</html>
