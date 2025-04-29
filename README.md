# 📌 Object Tracking with YOLOv8 + DeepSORT, ByteTrack, and BoT-SORT

This project demonstrates object detection and multi-object tracking using **YOLOv8** for object detection and three popular tracking algorithms: **DeepSORT**, **ByteTrack**, and **BoT-SORT**. It compares their performance and highlights strengths and weaknesses for real-time applications.

---

## 📽️ Objective

- Detect objects (e.g., vehicles) in videos using YOLOv8.
- Track objects frame-by-frame with unique IDs.
- Analyze and compare DeepSORT, ByteTrack, and BoT-SORT tracking performance.
- Optimize FPS and maintain ID consistency in crowded or fast-moving scenes.

---
## Output
- input video car : "https://youtu.be/frbFQUJjww4"
- DeepSort tracker car : "https://youtu.be/_2nHKKwIvvM"
- Byte Track tracker car : "https://youtu.be/3V6iZ175mpw"
- BoT SORT tracker car : "https://youtu.be/o8-m0n6a9WE"
- BoT SORT without ReID tracker car : "https://youtu.be/BLZ_G0IOTQg"
  
- Achieved FPS : 31.37 (BoT SORT without ReID)
- Achieved FPS : 14.83 (BoT SORT)

  ---
- input video palace : "https://youtu.be/I6B8pCxS2Og"
- DeepSort tracker palace : "https://youtu.be/ychYrYjT4Aw"
- Byte Track tracker palace : "https://youtu.be/iH7RXVUZy2I"
- BoT SORT tracker palace : "https://youtu.be/8cmqvj3h7ug"
- BoT SORT without ReID tracker palace : "https://youtu.be/9F42Q6JjZ4s"
  
- Achieved FPS : 32.35 (BoT SORT without ReID)
- Achieved FPS : 13.68 (BoT SORT)

  ---
## Hardware

Tesla T4 GPU
