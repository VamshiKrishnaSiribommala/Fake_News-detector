<h1 align="center">📰 Fake News Detector</h1>

<p align="center">
  <b>Detect whether a news article is Real or Fake using Machine Learning and NLP 🧠</b><br>
  <i>Built with Django • Scikit-learn • NLTK • React • HTML/CSS/JS</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ML-Scikit--learn-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Framework-Django-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/NLP-NLTK-orange?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/VamshiKrishnaSiribommala/Fake_News-detector?style=for-the-badge">
</p>

---

## 🚀 Features

- 🔍 Real-time fake news classification using ML
- 🧠 NLP text preprocessing (tokenization, stopword removal, etc.)
- 🌐 Django-powered REST backend
- ⚙️ React-based frontend interface
- 🗃️ Quiz/game dataset loader for extra functionality

---

## 🛠️ Tech Stack

| Category     | Tech Used                           |
|--------------|-------------------------------------|
| 💻 Frontend  | React, HTML, CSS, JavaScript        |
| 🔙 Backend   | Python, Django                      |
| 🧠 ML/NLP    | Scikit-learn, NLTK                  |
| 🗂️ Dataset   | Fake and Real News Dataset (Kaggle) |

---

## 📦 Installation & Deployment Guide

### 🔁 1. Clone the Repository

```bash
git clone https://github.com/VamshiKrishnaSiribommala/Fake_News-detector.git
cd Fake_News-detector
```

---

### 🐍 2. Install Python Dependencies

```bash
cd app/FakeNewsDetectorAPI/
pip install -r requirements.txt
```

---

### 🌐 3. Install Frontend Dependencies

```bash
cd ../fake-news-detector-frontend
npm install
```

---

### 🚀 4. Start Django Backend Server

```bash
# From project root
cd app/FakeNewsDetectorAPI/
python manage.py migrate
python manage.py runserver
```

To load quiz/game data:

```bash
python manage.py quiz_data_loader game_data/game_data.csv
```

---

### 💻 5. Start React Frontend Server

> Open a **new terminal**, then run:

```bash
cd app/fake-news-detector-frontend/
npm start
```

---

### 🌍 Access the Web Application

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🧪 How It Works

1. 📝 User submits a news headline or article.
2. 🧹 NLP preprocessing is applied (stopword removal, vectorization, etc.).
3. 🤖 The ML model classifies the input as **Real** or **Fake**.
4. 📱 The result is displayed on the frontend.

---

## 📸 Screenshots

_Add screenshots like these:_

- **Live News Monitoring:** View real-time predictions for news articles.
![live_monitoring](https://res.cloudinary.com/dng99s7st/image/upload/v1749968885/fake%20news%20detection.png)

- **News Quiz:** Test your fake news detection skills by taking our news quiz.
![news_quiz](https://res.cloudinary.com/dng99s7st/image/upload/v1749969314/obuugqolg0gnyexvpaqs.png)

- **Check News by Title:** Enter a news title to see if it's predicted as real or fake.
![check_title](https://res.cloudinary.com/dng99s7st/image/upload/v1749968884/hfwot7g0lrok1mdyvenb.png)
---

## 🙋‍♂️ Author

**Vamshi Krishna Siribommala**  
📧 [vamshikrishnasiribommala@gmail.com](mailto:vamshikrishnasiribommala@gmail.com)  
🔗 [GitHub Profile](https://github.com/VamshiKrishnaSiribommala)

---

## 🐛 Issues & Feedback

If you have any questions or suggestions, feel free to reach out to me at [vamshikrishnasiribommala@gmail.com](mailto:vamshikrishnasiribommala@gmail.com).  
If you encounter any issues, raise an [issue](https://github.com/VamshiKrishnaSiribommala/Fake_News-detector/issues).

---

## 🌟 Show Your Support

If you like this project:

> ⭐ Give it a star  
> 🍴 Fork it  
> 📢 Share it

<p align="center">📚 Keep Learning. Keep Practicing. Keep Growing. 🚀</p>


