 KrishiRakshak - Farm Decision Intelligence

KrishiRakshak is a smart, data-driven web application designed to empower farmers with real-time insights, community sharing, and actionable intelligence. Built with modern web technologies, it bridges the gap between traditional farming and digital precision.

🚀 Features

🌤️ Real-Time Weather & Risk Alerts: Utilizes the Open-Meteo API to fetch hyper-local weather data and calculates automated risk alerts for floods, heatwaves, and pests.

🚜 AgriCircle (Community Sharing): A peer-to-peer marketplace integrated with Leaflet.js maps, allowing farmers to rent tractors, hire labor, and find nearby vendors.

📊 Live Market Prices: A localized dashboard displaying the latest Mandi rates for various crops to help farmers time their sales for maximum profit.

📖 Farm Logbook: A persistent, localized task and expense tracker that calculates total investments and allows farmers to download their records as an Excel-compatible CSV file.

📸 AI Crop Health Scanner: (UI Prototype) Allows farmers to upload images of diseased crops for instant AI diagnosis and treatment recommendations.

🗣️ Voice-Enabled AI Advisor: A conversational assistant utilizing the Web Speech API to answer farming queries, suggest actions, and read responses aloud in multiple languages.

🌐 Multi-Lingual Support: Full platform localization available in English, Hindi (हिन्दी), and Marathi (मराठी).

🛠️ Tech Stack

Frontend: HTML5, CSS3, Vanilla JavaScript

Mapping: Leaflet.js with OpenStreetMap tiles

Data APIs: Open-Meteo Geocoding & Weather APIs

Web APIs: Web Speech API (Speech Synthesis & Recognition), LocalStorage API (Persistence)

📁 Project Structure

krishirakshak/
├── css/
│   └── style.css       # All global styles, variables, and media queries
├── js/
│   └── main.js         # API fetching, state management, and UI logic
├── images/
│   └── farmer.jpg      # Static image assets
├── index.html          # Main application structure
└── README.md           # Project documentation



⚙️ Installation & Usage

Because KrishiRakshak is built using Vanilla HTML, CSS, and JS, no complex build steps or package managers are required.

Clone the repository:

git clone [https://github.com/yourusername/krishirakshak.git](https://github.com/yourusername/krishirakshak.git)



Open the project:
Simply open the index.html file in any modern web browser (Chrome, Edge, Firefox, Safari).

Permissions:
Ensure you grant the browser microphone permissions if you wish to use the Voice Input feature in the AI Advisor section.

🔮 Future Enhancements

Backend Integration: Connect the Farm Logbook to a cloud database (e.g., Firebase or PostgreSQL) for cross-device syncing.

Live Mandi API: Integrate with the government data.gov.in API for live, authentic market rates.

Hardware IoT Integration: Connect the dashboard to on-field ESP32 microcontrollers for automated irrigation and pesticide control.

Real ML Vision: Connect the Crop Health scanner to a trained TensorFlow.js or Python backend model for actual image classification.

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📝 License

This project is licensed under the MIT License.
