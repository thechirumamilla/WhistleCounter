# WhistleCounter

## 📌 Overview
WhistleCounter is an Android app that listens for a pressure cooker's whistle sound and counts the number of times it occurs. This project aims to provide an efficient way to monitor cooking times based on whistle counts.

## 🚀 Features
- Detects and counts cooker whistles using frequency-based filtering.
- Ignores background noise for accurate whistle detection.
- Displays real-time whistle count.
- Lightweight and efficient, optimized for mobile devices.

## 🔧 Technologies Used
- **Java** for Android app development
- **Android Jetpack** for modern UI and architecture components
- **AudioRecord API** for real-time audio capture
- **Fast Fourier Transform (FFT)** for frequency-based whistle detection
- **RingtoneManager API** for triggering built-in alarm sounds
- **Material Design Components** for a polished UI

## 🛠 Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/thechirumamilla/WhistleCounter.git
   cd WhistleCounter
   ```
2. **Open in Android Studio**
   - Open Android Studio and select "Open an existing project."
   - Navigate to the cloned repository and open it.
3. **Run the App**
   - Connect an Android device or use an emulator.
   - Click "Run" to build and deploy the app.

## 🎯 How It Works
1. Captures live audio from the device's microphone.
2. Applies a **bandpass filter** to isolate frequencies of cooker whistles (typically 1-4 kHz).
3. Detects peaks matching whistle characteristics.
4. Increments the whistle count and displays results on the UI.
5. Triggers an alarm using the system's built-in sounds when the desired count is reached.

## 📸 Demo
(Screenshot or GIF of the app detecting whistles) - TBD

## 🚀 Future Enhancements
- Improve accuracy using machine learning.
- Add cloud sync to store whistle logs.
- Introduce push notifications for completed whistles.

## 🤝 Contributing
Feel free to fork this repository and submit pull requests with improvements!

## 📜 License
This project is currently not licensed. If you wish to contribute under a specific license, please propose it in an issue.

---

💡 **Need help?** Open an issue or reach out! Happy coding! 😊
