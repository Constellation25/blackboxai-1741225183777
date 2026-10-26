
cat > public/index.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agent C25 - Constellation25</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: linear-gradient(135deg, #0f0118 0%, #1a0033 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            padding: 20px;
        }
        .card {
            text-align: center;
            max-width: 800px;
            padding: 48px;
            background: rgba(157, 69, 255, 0.08);
            border: 1px solid rgba(157, 69, 255, 0.4);
            border-radius: 12px;
        }
        h1 { 
            font-size: 48px; 
            margin-bottom: 12px; 
            color: #9945ff;
            font-weight: 700;
        }
        .sub { 
            font-size: 18px; 
            opacity: 0.8; 
            margin-bottom: 32px;
            font-weight: 500;
        }
        .badge {
            display: inline-block;
            background: #10b981;
            padding: 8px 20px;
            border-radius: 4px;
            font-size: 14px;
            font-weight: 700;
            letter-spacing: 0.5px;
            margin-bottom: 32px;
        }
        .info {
            background: rgba(0, 0, 0, 0.3);
            padding: 24px;
            border-radius: 8px;
            margin: 24px 0;
            text-align: left;
        }
        .info-item {
            margin: 12px 0;
            font-size: 15px;
            display: flex;
        }
        .info-item strong {
            color: #9945ff;
            display: inline-block;
            width: 140px;
            flex-shrink: 0;
        }
        .capabilities {
            margin: 32px 0;
            text-align: left;
        }
        .capabilities h2 {
            font-size: 24px;
            margin-bottom: 20px;
            color: #9945ff;
            text-align: center;
        }
        .capability-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 16px;
        }
        .capability {
            background: rgba(157, 69, 255, 0.1);
            padding: 20px;
            border-radius: 8px;
            border: 1px solid rgba(157, 69, 255, 0.2);
        }
        .capability h3 {
            font-size: 16px;
            margin-bottom: 8px;
            color: #ffffff;
        }
        .capability p {
            font-size: 13px;
            opacity: 0.7;
            line-height: 1.5;
        }
        .links { 
            margin-top: 32px; 
        }
        a {
            color: #9945ff;
            text-decoration: none;
            font-weight: 600;
            font-size: 16px;
            margin: 0 16px;
        }
        a:hover { 
            text-decoration: underline; 
        }
        .footer { 
            margin-top: 40px; 
            font-size: 13px; 
            opacity: 0.5;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Agent C25</h1>
        <p class="sub">Constellation25 Planetary Agent System</p>
        <div><span class="badge">LIVE</span></div>
        
        <div class="info">
            <div class="info-item"><strong>System:</strong> Agent C25 v1.0.0</div>
            <div class="info-item"><strong>Organization:</strong> Constellation25</div>
            <div class="info-item"><strong>Status:</strong> Backend API Operational</div>
            <div class="info-item"><strong>Port:</strong> 3000</div>
            <div class="info-item"><strong>Endpoint:</strong> /api/*</div>
        </div>

        <div class="capabilities">
            <h2>LLM Tools & Capabilities</h2>
            <div class="capability-grid">
                <div class="capability">
                    <h3>Research & Papers</h3>
                    <p>Search and analyze academic papers from Arxiv and scientific databases</p>
                </div>
                <div class="capability">
                    <h3>Weather Intelligence</h3>
                    <p>Real-time weather data integration for context-aware responses</p>
                </div>
                <div class="capability">
                    <h3>Universal Search</h3>
                    <p>Search across web, local data, and knowledge bases</p>
                </div>
                <div class="capability">
                    <h3>Payment Processing</h3>
                    <p>Secure payment integration for subscriptions and transactions</p>
                </div>
                <div class="capability">
                    <h3>File Upload</h3>
                    <p>Upload and manage files with AI-powered processing</p>
                </div>
                <div class="capability">
                    <h3>Authentication</h3>
                    <p>Secure user authentication and session management</p>
                </div>
                <div class="capability">
                    <h3>GraphQL API</h3>
                    <p>Flexible query language for efficient data retrieval</p>
                </div>
                <div class="capability">
                    <h3>Health Monitoring</h3>
                    <p>System health checks and status endpoints</p>
                </div>
            </div>
        </div>

        <div class="links">
            <a href="https://github.com/Constellation25/AiMetaverse">GitHub Repository</a>
            <a href="http://localhost:3000/health">Health Check</a>
        </div>
        
        <div class="footer">
            Constellation25 | CyGeL White / Kre8tive Holdings | 2026
        </div>
    </div>
</body>
</html>
EOF
