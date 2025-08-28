# Blue Phantom

#### Turn the ordinary into extraordinary - become invisible in real-time using just a webcam and a blue cloak! 🪄

## ✨ About the Project

Ever dreamed of disappearing like a phantom? Blue Phantom brings that magic to life! Using your webcam, a blue cloak, and some clever computer vision tricks, this project lets you become invisible in real-time.

The project leverages OpenCV and Python to detect a blue cloak, remove it from the frame, and replace it seamlessly with the background – giving the illusion of invisibility. Perfect for fun experiments, content creation, or just impressing your friends!

## 🛠 Features

Real-time invisibility effect using your webcam.

Fully interactive: press 'b' to recapture the background without restarting.

Adjustable mask for smoother results.

Debug mode shows the cloak mask for understanding the detection process.

Lightweight and runs on any standard webcam.


## 💡 How It Works

Capture the static background (without the cloak).

Convert the video frames to HSV color space.

Detect the blue cloak using a color mask.

Replace the cloak area with the captured background in real-time.

Blend the non-cloak areas to maintain the live video effect.

## 🎥 Demo

You can run the script and see:

Yourself turning invisible whenever you wear the blue cloak.

Optional live mask view to tweak the effect.

## ⚡ Getting Started

Clone this repository:

git clone https://github.com/yourusername/Blue-Phantom.git


Install dependencies:

pip install opencv-python numpy


Run the script:

python blue_phantom.py


Wear a blue cloak, enjoy the invisibility magic, and press ESC to exit or 'b' to recapture the background.

## 🖌 Creative Possibilities

Create fun invisibility videos for social media.

Combine with green screen effects for advanced content creation.

Experiment with other colors or patterns to extend the magic.

## 🌟 Credits

Built with ❤️ using Python and OpenCV

Inspired by the magic of invisibility cloaks and real-time computer vision experiments


## 🔮 Future Enhancements

Add multi-color cloak detection.

Smooth transitions using AI-based inpainting.

Export videos directly with the invisibility effect.
