# ClimatePolicySim

![ClimatePolicySim Banner](menu_pic.png)

## 🌍 Overview
**ClimatePolicySim** is an interactive simulation designed to educate users about the impact of various policy decisions on climate change. The project provides real-time feedback on policy choices, helping users understand their effects on carbon emissions, global temperature rise, and sustainable development goals.

## 🚀 Features
- 📊 **Dynamic Policy Simulator** – Adjust climate policies and observe their impact in real-time.
- 🔄 **Collapsible Notification System** – Displays important updates and facts, with alert icons for new content.
- 📜 **Fact-Based Updates** – Periodically displays new facts on global warming and sustainable development.
- 🎨 **Customizable UI** – Background color and collapsible content panel for an intuitive experience.
- ⏳ **Timer-Based Content Refresh** – Automatically updates displayed facts at set intervals.
- 🛠 **Built with Unreal Engine 5** – Uses Blueprints and Widgets for a seamless experience.

## 📦 Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/Emir2099/ClimatePolicySim.git
   ```
2. Open the project in **Unreal Engine 5.0.3**.
3. Build and run the simulation.

## 🛠 Technologies Used
- **Unreal Engine 5** – Game Engine
- **Blueprint Scripting** – Logic Implementation
- **UMG (Unreal Motion Graphics)** – UI Development
- **Timers & GameState** – Content Management

## 📖 How It Works
1. **Collapsible Notification Widget (WBP_CollapsibleNotification)**
   - Displays climate facts with a background.
   - New content triggers an alert icon.
   - Clicking expands/collapses the panel and dismisses the alert.
2. **Fact Rotation System**
   - Uses an **array of climate facts**.
   - A timer cycles through facts and updates the widget.
3. **GameState Manager (BP_GameStateManager)**
   - Manages fact updates and UI state.
   - Calls `UpdateContent` function at defined intervals.

## 🏗️ Future Enhancements
- 🧠 **AI-based Policy Suggestions** – Recommends optimal policies.
- 🌱 **Expanded Fact Database** – More real-world climate insights.
- 📡 **Live Data Integration** – Fetch real-time climate reports.

## 🤝 Contributing
We welcome contributions! Feel free to submit issues, pull requests, or feature suggestions.



