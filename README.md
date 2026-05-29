# ESPCAMDASHBAORD

tactical-surveillance-cms/
├── edge_node_firmware/        # C++ codebase for the ESP32-CAMs
│   ├── src/                   # main.cpp (Camera, Wi-Fi, OTA, Endpoints)
│   └── platformio.ini         # Dependency management (Recommended over Arduino IDE)
├── command_center/            # The Central Management System (CMS)
│   ├── backend/               # Handles MJPEG stream routing, WebSocket telemetry, and database
│   └── frontend/              # React/Vite app for the multi-tab glassmorphic UI
├── .gitignore
└── README.md
