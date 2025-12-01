
# 🕹️ Hangman Game

![Language](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
[![LinkedIn](https://img.shields.io/badge/HiramDeep%20Kaur-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/hiram-deep-227916337/)

---

## 📌 Project Overview

This notebook is a **text-based Hangman game** implemented in Python, fully runnable in **Google Colab**.  

Features:

- Random word selection from a text file (`words.txt`)  
- Graphical Hangman stages from a text file (`stages.txt`)  
- Input validation for single alphabet characters  
- Real-time display of guessed letters and word progress  
- Limited number of attempts with feedback  

It is designed for **learning Python basics, loops, conditionals, and sets** in an interactive way.

---

## 🔗 Self-Learning Resources

- [Python Official Documentation](https://docs.python.org/3/)  
- [Text-Based Games in Python](https://realpython.com/python-games/)  
- [Google Colab Tutorials](https://colab.research.google.com/notebooks/intro.ipynb)  

---

## 📌 How to Run the Game

1. **Upload the necessary files** in Colab:
   - `words.txt` → List of words (one per line)  
   - `stages.txt` → Hangman stages separated by `###`

2. **Run the main cell**:
```python
words_file = 'words.txt'
stages_file = 'stages.txt'
play_game(words_file, stages_file)
````

3. **Gameplay**:

   * Guess one letter at a time
   * You have a limited number of tries (default: 6)
   * Correct guesses reveal the letters
   * Game ends when word is guessed or attempts run out

---

## 👤 Author

**HiramDeep Kaur**
🔗 [LinkedIn Profile](https://www.linkedin.com/in/hiram-deep-227916337/)

---

⭐ If you found this notebook helpful, please **Star** the repository and share with others!

---
