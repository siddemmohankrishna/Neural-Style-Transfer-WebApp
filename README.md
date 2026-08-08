# 🎨 Neural Style Transfer Web Application

A Flask-based web application that applies artistic styles to images using Neural Style Transfer (NST) implemented with PyTorch.

## 🚀 Features

- Upload a Content Image
- Upload a Style Image
- Generate artistic stylized images
- Deep Learning-based Neural Style Transfer
- Interactive Flask Web Interface
- Real-time image processing

## 🛠️ Tech Stack

- Python
- Flask
- PyTorch
- TorchVision
- HTML
- CSS
- Bootstrap
- Pillow

## 📂 Project Structure

```text
NST_Code/
│
├── app.py
├── train.py
├── requirements.txt
├── vgg_normalised.pth
│
├── Content_data/
├── Style_data/
├── experiment/
│
├── templates/
│   └── index.html
│
├── static/
│   ├── uploads/
│   ├── css/
│   └── images/
│
└── utils/
    ├── models.py
    └── utils.py
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/siddemmohankrishna/Neural-Style-Transfer-WebApp.git
cd Neural-Style-Transfer-WebApp
```

### Create Virtual Environment

```bash
python -m venv myenv
```

### Activate Environment

Windows:

```bash
myenv\Scripts\activate
```

Linux/Mac:

```bash
source myenv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## 🏋️ Model Training

```bash
python train.py --batch_size 4 --epochs 10 --experiment trial2
```

Training checkpoints will be saved inside:

```text
experiment/trial2/
```

## 🌐 Run Web Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

in your browser.

## 📸 Example Workflow

1. Upload a Content Image
2. Upload a Style Image
3. Click Generate
4. Download the Stylized Output

## 📈 Deep Learning Architecture

- Encoder: Pre-trained VGG Network
- Adaptive Instance Normalization (AdaIN)
- Decoder Network
- Content Loss
- Style Loss

## 🎯 Future Improvements

- Multiple style blending
- GPU acceleration
- User authentication
- Cloud deployment
- Batch image processing

## 👨‍💻 Author

**Siddem Mohan Krishna**

- GitHub: https://github.com/siddemmohankrishna
- LinkedIn: https://www.linkedin.com/in/siddem-mohan-krishna-247984378/

## 📜 License

This project is developed for educational and research purposes.
