Hirose Electric Americas // Digital Signage Dashboard

This repository hosts a custom, web-based dashboard designed for high-visibility on-screen monitors at Hirose Electric Americas. It combines real-time industrial data with high-end brand aesthetics to showcase Hirose’s position as a leader in global connectivity.
📊 Features

    Real-Time Ticker: Live tracking of Hirose Electric (TSE: 6806) alongside key industry peers and partners (Apple, NVIDIA, Tesla).

    Commodity Tracking: Active monitoring of Copper and Gold market prices—essential materials for precision connector manufacturing.

    Global Connectivity Viz: An interactive, high-tech visualization of global weather and infrastructure patterns via Windy.com.

    Brand Integration: Custom-themed using Hirose's primary brand colors:

        Hirose Blue: #5B95F1

        Hirose Green: #80B341

🛠 Tech Stack

    Hosting: GitHub Pages

    Framework: Vanilla HTML5 / CSS3

    Data Sources: TradingView (Market Data), Windy.com (Global Visuals)

🔄 How to Update Content

To change the stock symbols or update the dashboard layout:

    Open the index.html file in this repository.

    Locate the symbols array within the TradingView script.

    Add or remove ticker symbols using the following format:
    { "proName": "EXCHANGE:SYMBOL", "title": "DISPLAY NAME" }

    Commit Changes to save. The monitors will update automatically on their next refresh.

🚀 Deployment

This project is live-synced to GitHub Pages. The production URL for use in digital signage software is:
https://[YOUR-USERNAME].github.io/hirose-monitors/
