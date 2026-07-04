# Image-Zoom-Video-Generator-using-Python
A Python-based image animation project that transforms a single static image into a smooth zoom-in video using frame interpolation techniques. Built with Google Colab, Pillow, and ImageIO, the project demonstrates fundamental concepts of image processing and video generation.
Got it — you want it **clean, professional, and point-based with emojis (GitHub-ready)**. Here’s a polished version:

---

# 🎬 Image Zoom Video Generator

A simple Python project that converts a single image into a smooth **zoom-in video animation** using frame-based image processing in Google Colab.

---

## 🚀 Features

* 📤 Upload image directly in Google Colab
* 🖼️ Automatic image resizing (512 × 512)
* 🔍 Smooth center zoom-in effect
* 🎞️ Frame-by-frame video generation
* 🎥 Export output as MP4 video
* ⬇️ Auto-download generated video
* ⚡ Lightweight and fast execution

---

## 🛠️ Tech Stack

* 🐍 Python
* 📓 Google Colab
* 🖼️ Pillow (PIL)
* 🔢 NumPy
* 🎞️ ImageIO
* ⚙️ FFmpeg

---

## ⚙️ How It Works

* 📥 Step 1: Upload an image in Colab
* 🧹 Step 2: Resize image to standard resolution
* 🔄 Step 3: Generate multiple zoom frames using cropping
* 📐 Step 4: Resize each frame back to original size
* 🎬 Step 5: Combine frames into video
* 📤 Step 6: Export and download MP4 file

---

## 📁 Project Structure

```text
Image-Zoom-Video-Generator/
│
├── notebook.ipynb      # Main Colab notebook
├── input.png           # Uploaded image
├── zoom_video.mp4      # Output video
└── README.md
```

---

## 📦 Installation

```bash
pip install imageio[ffmpeg] pillow torchvision diffusers accelerate
```

---

## ▶️ Usage

* 📌 Open Google Colab notebook
* ▶️ Run all cells step-by-step
* 📤 Upload your image when prompted
* ⏳ Wait for processing
* 🎥 Download generated `zoom_video.mp4`

---

## 🎛️ Customization

* 🔢 `num_frames` → Control smoothness of animation
* 🔍 `zoom factor` → Adjust zoom intensity
* 🎞️ `fps` → Change video speed
* 📐 `resize()` → Set output resolution

---

## 🎯 Use Cases

* 📱 Social media content creation
* 🎞️ Video editing projects
* 🖼️ Photo slideshow animations
* 🎓 Learning image processing basics
* 🎬 Presentation visuals

---

## 🚀 Future Improvements

* 🔄 Zoom in + Zoom out effect
* 🎯 Pan & Zoom (Ken Burns effect)
* 🎨 Custom focus point selection
* 🎞️ GIF export support
* 🖥️ Streamlit / Web UI version
* 📊 Higher resolution (HD/4K) support

---

## 📜 License

* 🆓 Open-source project
* 📄 Licensed under MIT License

---

## ⭐ Summary

* 📌 Converts image → smooth zoom video
* ⚡ Lightweight & beginner-friendly
* 🎥 No AI model required
* 🧠 Pure image processing technique
