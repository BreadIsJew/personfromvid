# 🎥 PersonFromVid: AI-Powered Video Frame Extraction Tool

![PersonFromVid](https://img.shields.io/badge/Download%20Latest%20Release-Release%20Page-brightgreen)

Welcome to the **PersonFromVid** repository! This tool harnesses the power of AI to automatically identify and extract high-quality frames from videos that contain people. With advanced features like intelligent pose categorization, head orientation detection, and shot type classification, PersonFromVid is designed to make video processing efficient and user-friendly.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration Options](#configuration-options)
5. [GPU Acceleration](#gpu-acceleration)
6. [Resumable Processing](#resumable-processing)
7. [Pose Categorization](#pose-categorization)
8. [Head Orientation Detection](#head-orientation-detection)
9. [Shot Type Classification](#shot-type-classification)
10. [Contributing](#contributing)
11. [License](#license)
12. [Contact](#contact)
13. [Releases](#releases)

## Features

- **High-Quality Frame Extraction**: Automatically extracts frames from videos that contain people.
- **Pose Categorization**: Classifies poses as standing, sitting, or squatting.
- **Head Orientation Detection**: Identifies the direction a person's head is facing.
- **Shot Type Classification**: Classifies the type of shot (close-up, medium, wide).
- **GPU Acceleration**: Utilizes GPU for faster processing.
- **Resumable Processing**: Allows you to pause and resume processing without losing progress.
- **Extensive Configuration Options**: Customize settings to fit your needs.

## Installation

To get started with PersonFromVid, you need to clone the repository and install the required dependencies. Use the following commands:

```bash
git clone https://github.com/BreadIsJew/personfromvid.git
cd personfromvid
pip install -r requirements.txt
```

## Usage

To use PersonFromVid, run the main script with your video file as an argument:

```bash
python main.py your_video_file.mp4
```

This command will process the video and extract frames based on the built-in settings.

## Configuration Options

PersonFromVid offers a variety of configuration options. You can adjust these settings in the `config.yaml` file located in the repository. Key options include:

- `frame_rate`: Set the frame extraction rate.
- `output_directory`: Specify where to save extracted frames.
- `pose_detection`: Enable or disable pose detection.
- `head_orientation`: Enable or disable head orientation detection.
- `shot_type_classification`: Enable or disable shot type classification.

## GPU Acceleration

For optimal performance, PersonFromVid supports GPU acceleration. Ensure that you have the necessary drivers and libraries installed. If you are using NVIDIA GPUs, you can install CUDA and cuDNN. This will significantly speed up the processing time.

## Resumable Processing

If you need to pause the processing, you can do so without losing progress. Simply stop the script, and it will save the current state. When you restart the script, it will continue from where it left off.

## Pose Categorization

The tool intelligently categorizes poses into three main types:

- **Standing**: When a person is upright.
- **Sitting**: When a person is seated.
- **Squatting**: When a person is in a crouched position.

This categorization helps in better understanding the context of the video.

## Head Orientation Detection

Understanding head orientation can provide insights into a person's focus or attention. PersonFromVid detects head orientation in three directions:

- **Left**
- **Right**
- **Center**

This feature is particularly useful for analyzing interactions in videos.

## Shot Type Classification

PersonFromVid classifies the type of shot used in the video. The classifications include:

- **Close-Up**: A shot that tightly frames a subject.
- **Medium**: A shot that captures a subject from the waist up.
- **Wide**: A shot that shows the subject in their environment.

This classification aids in editing and production processes.

## Contributing

We welcome contributions to PersonFromVid! If you have suggestions or improvements, please fork the repository and submit a pull request. For larger changes, consider opening an issue to discuss your ideas first.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please reach out via the Issues section of the repository.

## Releases

To download the latest release, visit the [Releases page](https://github.com/BreadIsJew/personfromvid/releases). You will find the necessary files to download and execute.

Feel free to explore the features and make the most out of PersonFromVid. Happy extracting!