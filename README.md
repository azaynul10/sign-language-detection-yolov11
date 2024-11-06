#  Sign Language Detection using YOLOv11 

<div align="center">
  <img src="https://media.giphy.com/media/r4N5NIckk37x76byEf/giphy.gif?cid=790b76114q7ujlpguzc2zydj63z6ftf1al6yelf52rzgmc9p&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="Sign Language Detection Demo" width="700"/>
  <p><i>Real-time sign language detection powered by YOLOv11</i></p>
</div>

## 🌟 Journey & Challenges Overcome

> "Every error message was a stepping stone to success"

- 🔥 Exhausted 2 Google Colab accounts' RAM
- 💪 Persisted through numerous dependency conflicts
- 🧹 Cleared precious storage space, sacrificing other applications
- 🐛 Tackled and resolved countless bugs
- 🚀 Never gave up despite the obstacles!

## ✨ Features

- 🎯 Real-time sign language detection
- 🤖 Powered by YOLOv11 architecture
- 📊 High accuracy detection
- 🎮 User-friendly interface
- 🚀 GPU-accelerated inference (If you have colab pro you can use A100 GPU otherwise T4 GPU)
- 🔄 Support for multiple hand gestures

## 🎬 Demo & Results

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExajFobjNpeXY2eDg0NHl5dWJ5b2kwNm9teWJnMmRzN3ByZnZta3hlYSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/qfAulQmnLyKNBt89qt/giphy.gif" alt="Training Progress" width="600"/>
  <p><i>Model training progress and results visualization</i></p>
</div>

## 🛠️ Technical Details

```python
# Core Technologies
- YOLOv11
- TensorFlow
- OpenCV
- Python
- CUDA for GPU acceleration
```

# 📊 Model Performance

## Detection Results
| Gesture    | Confidence Score | Detection Time |
|------------|-----------------|----------------|
| Hello      | 95%             | ~8.4ms        |
| Thank You  | 92%             | ~7.2ms        |
| Love You   | 93%             | ~7.8ms        |

## Key Metrics
- **Average Inference Time**: 7.8ms per frame
- **FPS**: ~128 frames per second
- **Input Resolution**: 640x640 pixels
- **Model Architecture**: YOLOv11
- **Hardware**: Google Colab T4 GPU

## Performance by Gesture
### Hello
- ✅ High accuracy in frontal hand detection
- ✅ Consistent detection with varying hand positions
- ⚠️ May need improvement in low-light conditions

### Thank You
- ✅ Good detection of folded hands
- ✅ Works well with different angles
- ⚠️ Occasional confusion with similar gestures

### Love You
- ✅ Accurate detection of the specific hand shape
- ✅ Robust against different backgrounds
- ⚠️ May require more training data for edge cases

## Training Statistics
- **Training Duration**: XX hours
- **Number of Epochs**: 50
- **Training Dataset Size**: XX images (I've used less amount of datasets but I would suggest you create or get datasets from RoboFlow and train with your own datasets)
- **Validation Dataset Size**: XX images
- **Hardware Used**: Google Colab T4 GPU

## Challenges Overcome
- 🔄 RAM limitations on Google Colab
- 💾 Storage constraints
- 🐛 Dependency conflicts

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/azaynul10/sign-language-detection-yolov11

```
You can then run it in your Google Colab.
## 💪 Challenges & Solutions

<details>
<summary>Click to expand!</summary>

- **RAM Limitations**: 
  - Optimized batch sizes
  - Implemented gradient checkpointing
  
- **Storage Issues**: 
  - Streamlined dataset management
  - Optimized model checkpoints
  
- **Dependency Conflicts**: 
  - Created detailed environment setup
  - Documented working configurations
</details>

## 📈 Training Process

<div align="center">
  <img src="https://github.com/user-attachments/assets/8f1da8bc-e9ee-4ab2-9ddd-37f8ac6a15b3" alt="Training Metrics" width="600"/>
</div>

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest features
- 🔧 Submit PRs

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<div align="center">
  <b>Built with persistence, powered by determination! 💪</b>
  
  If you found this helpful, please ⭐ this repository!
</div>
