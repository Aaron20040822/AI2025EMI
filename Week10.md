##  1. What is DronePaint? (in 2 sentences)
DronePaint is an AI-based interactive art system that enables users to control a group of drones to create light paintings using only hand gestures. It uses deep learning models for gesture recognition, allowing natural, real-time control without any physical controller or device.

## 2. How do hand gestures move the drones?
DronePaint uses a camera-based computer vision system to capture hand movements. These inputs are processed by a Convolutional Neural Network (CNN) to interpret gestures, which are then mapped to drone commands such as position, direction, and movement speed.

## 3. What is the system architecture?
The system includes:

A gesture recognition module using DNN/CNN models;

A drone controller layer translating gesture input into commands;

A real-time light path visualizer, ensuring smooth and synchronized swarm movement;

ROS (Robot Operating System) as the communication middleware.

## 4. Why do we smooth the hand’s path before flying?
Hand gestures can be jittery or inconsistent, especially in real-time. Smoothing the path ensures stability, prevents sudden drone errors, and generates aesthetic, flowing light trails that look professional and artistic.

## 5. Three Metaphors for LightPaint
“The Airbrush of the Sky” – Your hand becomes the brush, the sky becomes your canvas.

“Digital Fireflies in Harmony” – Drones light up and move like coordinated fireflies based on your hand dance.

“Conducting a Symphony of Light” – You’re the conductor, drones are instruments performing a light-based concerto.

## Knowledge Boost 快充：What is DNN?（什麼是深度神經網路？｜ディープニューラルネットワークとは？）
🧠 Definition | 定義
DNN (Deep Neural Network) 是一種模仿人腦運作的 AI 系統，由多層「人工神經元」所組成，能夠逐層提取特徵：從簡單的線條到複雜的圖像。

👉 就像一位藝術家，DNN 先描邊，再上色，最後創造整幅畫作——它的「多層結構」就是學習深度的關鍵。

🔍 Applications | 應用領域
🎤 語音辨識（Voice Recognition）

🚗 自駕車（Autonomous Vehicles）

😃 臉部辨識（Face Detection）

🎨 Metaphor Approach | 比喻式學習法
Like a detective, DNN gathers clues layer by layer—from footprints (edges) to faces (objects).

Like a chef, it first preps ingredients (basic features), then combines them into dishes (complex insights).

Like LEGO, each layer adds new bricks to build a detailed, functional model of reality.

