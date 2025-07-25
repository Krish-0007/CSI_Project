# 🎓 Student Marks Prediction with Special Attention Detection

This project uses machine learning to predict student performance based on various academic and behavioral factors. It also identifies students who are likely to fail and **require special attention**, allowing timely interventions from educators or mentors.

---

## 🔍 Objective

- Predict **final exam marks** using features like:
  - 📚 Hours studied per day
  - 🏫 Attendance percentage
  - 📝 Previous exam scores
  - 😴 Sleep hours
  - 🙋 Class participation rating

- Automatically **flag students** predicted to score **below 40** as:
  > ❌ Requires Special Attention

---

## 🧠 Tech Stack & Algorithms

- **Python 3**
- **Libraries**:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
- **Algorithm**: Linear Regression
- **Preprocessing**: StandardScaler for normalization

---

## 📁 Repository Structure

| File                             | Description                                               |
|----------------------------------|-----------------------------------------------------------|
| `student_data.csv`              | Raw dataset with features and actual marks                |
| `student_model_predictions.csv` | Predictions for test set with actual vs predicted marks   |
| `student_predictions_top50.csv` | Predictions + remarks for first 50 students               |
| `student_marks_prediction.ipynb`| Jupyter Notebook with training, prediction, and analysis  |
| `README.md`                     | Project overview and usage guide                          |

---

## 📊 Sample Output

| Hours_Studied | Attendance | Final_Marks | Predicted_Marks | Remark                     |
|---------------|------------|-------------|------------------|----------------------------|
| 2.5           | 60         | 33          | 35.2             | ❌ Requires Special Attention |
| 5.0           | 85         | 78          | 75.9             | ✅ Satisfactory               |

---

## 🚀 Future Enhancements

- Replace Linear Regression with more powerful models like:
  - `RandomForestRegressor`
  - `XGBoostRegressor`
- Build an interactive **Streamlit dashboard**
- Add student **ID/name** tracking
- Real-time integration with school attendance and exam systems

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome!  
Feel free to fork this repository and raise a pull request.

---

## 📜 License

This project is open-source and free to use under the **MIT License**.

---

## 🧩 Author

**Krishnav Sharma**  
B.Tech (AI), SKIT Jaipur  
[LinkedIn]([https://linkedin.com/](https://www.linkedin.com/in/krishnav-sharma-960350247/)) • [GitHub]([https://github.com/](https://github.com/Krish-0007))

