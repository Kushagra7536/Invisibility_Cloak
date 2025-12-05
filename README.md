# 🧙 Invisibility Cloak - Streamlit App

A real-time invisibility cloak application using OpenCV and Streamlit, inspired by Harry Potter's magical cloak!

## ✨ Features

- **Real-time video processing** with WebRTC
- **Background subtraction** for invisibility effect
- **Blue color detection** for cloak material
- **Streamlit web interface** for easy use
- **Cross-platform compatibility**

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/Kushagra7536/Invisibility_Cloak.git
cd Invisibility_Cloak
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
streamlit run main.py
```

4. **Open your browser** and go to `http://localhost:8501`

### Streamlit Cloud Deployment

1. **Fork this repository** on GitHub
2. **Go to** [share.streamlit.io](https://share.streamlit.io)
3. **Connect your GitHub account**
4. **Deploy** by selecting your forked repository
5. **Set the main file path** to `main.py`

## 🎯 How to Use

1. **Allow camera access** when prompted
2. **Stand still** for 3-4 seconds to capture background
3. **Put on a blue cloth** (bright blue works best)
4. **Watch the magic happen!** ✨

## 💡 Tips for Best Results

- Use **bright blue colored fabric** (royal blue, cobalt blue)
- Ensure **good lighting** in the room
- **Stand still** during background capture
- **Avoid blue objects** in the background
- Use on **desktop/laptop** for best performance

## 🛠 Technical Details

- **Frontend**: Streamlit
- **Computer Vision**: OpenCV
- **Video Processing**: streamlit-webrtc, PyAV
- **Real-time Communication**: WebRTC with STUN servers
- **Color Space**: HSV for robust blue detection
- **Background Method**: Running average accumulation

## 📋 Requirements

- Python 3.8+
- Webcam access
- Modern web browser (Chrome/Edge recommended)
- Good lighting conditions

## 🔧 Troubleshooting

- **Camera not working?** Check browser permissions
- **Poor performance?** Try desktop instead of mobile
- **Invisibility not effective?** Use brighter blue cloth
- **App freezing?** Refresh and ensure good internet connection

## 📄 License

MIT License - feel free to use and modify!

---
Made with ❤️ using Streamlit & OpenCV by Kushagra Yadav