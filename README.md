
# 📸 Image Downloader Script

A simple and effective Python script for downloading images from URLs! This tool allows you to download images with custom names and organize them in folders. Perfect for automating image downloads and organizing your content effortlessly.

---

## 🌟 Features
- **Custom Naming**: Save images with any name of your choice.
- **Flexible Storage**: Organize images into specified folders.
- **Extension Recognition**: Automatically detects supported formats (.jpg, .png, .jpeg, .gif, .svg).
- **File Safety**: Ensures that files with the same name are not overwritten.

---

## ⚙️ Setup

### Prerequisites
- **Python 3.8+**
- Install the required packages:
  ```bash
  pip install requests
  ```

---

## 🚀 Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sks01dev/image-downloader-script.git
   cd image-downloader-script
   ```

2. **Run the Script**:
   ```bash
   python image_downloader.py
   ```
   - **Enter the Image URL**: Paste the direct link to the image.
   - **Name Your Image**: Provide a name to save your file.
   - **Select Folder** (optional): Specify a folder name to save your image in a custom location.

### Example
```bash
Enter a URL: https://example.com/sample-image.jpg
What would you like to name it?: my_image
```

### Sample Output
```plaintext
Downloading
Downloaded: "images/my_image.jpg" successfully!
```

---

## 📂 File Structure

```plaintext
├── image_downloader.py   # Main script file
├── README.md             # Documentation
└── images/               # Folder where images will be saved (optional)
```

---

## 🛠️ Customization

- **Supported Extensions**: To add more supported formats, modify the `extensions` list in `get_extension()`.
- **Folder Structure**: Customize the download path by modifying the `folder` parameter in `download_image()`.

---

## 📝 License
This project is licensed under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to make this project better.
