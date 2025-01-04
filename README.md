# VisualWords - An Image Caption Generator

VisualWords is a cutting-edge project that combines advanced computer vision and generative AI to generate accurate, context-aware captions for any input image. By integrating YOLOv11 for object detection and Google Gemini's generative AI, this tool transforms images into meaningful text descriptions seamlessly. It is an end-to-end project featuring a user-friendly website for an enhanced user experience.

---

## Features

- **Object Detection**: Utilizes YOLOv11 for precise identification of objects in an image.
- **Caption Generation**: Leverages Google Gemini's generative AI to produce high-quality, contextually relevant captions.
- **End-to-End Automation**: Processes images from detection to captioning in a single workflow.
- **User-Friendly Website**: Provides an intuitive interface for users to upload images and view generated captions.
- **Highly Accurate**: Combines state-of-the-art models for superior performance.

---

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.8+
- TensorFlow/PyTorch (depending on your YOLOv11 implementation)
- Google Gemini API access

Additionally, you will need the following Python libraries:

- `numpy`
- `opencv-python`
- `matplotlib`
- `transformers`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/VisualWords.git
   cd VisualWords
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Google Gemini API credentials by following the official documentation and storing your API key in an environment variable.

---

## Usage

### Using the Website

1. Start the web server:
   ```bash
   python app.py
   ```

2. Open your web browser and navigate to `http://localhost:5000`.

3. Upload an image to generate a caption and view the results.

### Command-Line Interface

1. Place your input images in the `input_images/` folder.

2. Run the main script:
   ```bash
   python main.py
   ```

3. Generated captions will be saved in the `output_captions/` folder along with visualized object detection results.

---

## Example

**Input Image**:
![example_input](docs/example_input.jpg)

**Generated Caption**:
"A group of people playing soccer on a sunny day."

---

## Contribution

Contributions are welcome! If you have ideas, suggestions, or improvements, feel free to open an issue or create a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [YOLOv11](https://github.com/ultralytics/yolov11)
- [Google Gemini](https://ai.google/)


