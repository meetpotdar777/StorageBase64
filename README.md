# 🌌 StorageBase64

**StorageBase64** is a high-frequency media transcoder designed to bridge the gap between high-performance local video encoding and lightweight web-based storage. By utilizing local **FFmpeg** power alongside browser-based **Base64 stringification**, this tool allows you to store and share media as compressed text fragments.

## 🚀 Features

  * **FFmpeg Command Lab:** Real-time generation of terminal commands for local AV1 and HEVC conversion.
  * **WebP Core Engine:** Automated browser-side optimization for images to ensure the smallest string footprint.
  * **Neo-Anime UI:** A vibrant, cyberpunk-inspired interface with neon cyan and purple accents.
  * **Instant Reconstruction:** A decoder engine that instantly renders Base64 strings back into playable media.
  * **Live Metrics:** Real-time comparison between binary file size and the resulting string size.
  * **Zero Server Lag:** All processing is done client-side or on your local machine for maximum privacy.

-----

## 🛠️ Tech Stack

| Layer        | Technology                          |
| :----------- | :---------------------------------- |
| **Styling** | Tailwind CSS (JIT)                  |
| **Core Logic**| JavaScript (ES6+), FileReader API   |
| **Encoding** | Base64 URI Scheme, Canvas API       |
| **Local Ops**| FFmpeg (AV1 & libx265 Codecs)       |

-----

## 📂 Project Structure

```text
StorageBase64/
├── storage_base64.html   (Single-File Application)
├── README.md             (Project Documentation)
└── Assets/               (User-generated media strings)
```

-----

## ⚙️ How to Use

1.  **Local Pre-Processing:** Use the "FFmpeg Command Lab" in the UI to generate a command. Run it in your laptop's terminal to convert your video to **AV1** or **HEVC**.

2.  **Encode:** Drag the compressed file into the **Input Interface**. The tool will generate a Base64 string instantly.

3.  **Store:** Click **Copy Fragment** to save your media as a text string.

4.  **Decode:** Paste any valid StorageBase64 string into the **Decoder Core** to reconstruct and play the media.

-----

## 🎨 Compression Workflow

The system utilizes a hybrid logic for maximum efficiency:

🔵 **Videos:** Best pre-compressed via FFmpeg using `libaom-av1` at `crf 30`.

🟣 **Images:** Auto-optimized to WebP at 80% quality during the stringification process.

🟢 **Binary to String:** Standardizing the output for use in JSON, Databases, or TXT storage.

-----

-----

## 👨‍💻 Author

**Meet Potdar**
*Full-Stack Developer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/meet-potdar-04b12b290?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=flat&logo=firefox&logoColor=white)](https://meet3333333333.wixstudio.com/my-site)


<div style="text-align: center;">
  <img src="https://img.sanishtech.com/u/45824c09fb740bd8a6b30d23bbdb04ef.png" alt="StorageBase" width="900">
  
  <div style="height: 100px;"></div> 

-----

*Built with ❤️ for high-efficiency media operations*
