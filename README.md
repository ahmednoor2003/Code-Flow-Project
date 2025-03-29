**Project Documentation: AI-Based Resume Classifier**

---

# **Introduction**

In today’s competitive job market, finding the right career path can be challenging. Our project aims to simplify this by developing an AI-based system that takes a user’s resume and recommends the best-suited career field based on their qualifications, skills, and experience.

This document provides a comprehensive overview of how our project was developed, from data collection to model training and GUI design.

---

# **Data Collection & Web Scraping**

To train our model, we needed a large dataset of resumes. Since obtaining such a dataset manually was impractical, we created a **web scraping application** using **Python** and deployed it on a spare laptop.

### **Key Highlights of Data Collection:**
- The application ran continuously for **two weeks**.
- It scraped over **150,000 resumes** from our website (**Apply4UK.com**).
- The extracted data was stored securely for preprocessing and training.

### **Challenges Faced:**
- Ensuring that the scraper worked efficiently without crashing.
- Managing the large volume of data and ensuring its integrity.

---

# **Data Preprocessing**

Raw data is often messy and contains irrelevant information. To improve the accuracy of our AI model, we applied **various preprocessing techniques** to clean and organize the dataset.

### **Steps Taken:**
✅ Categorized resumes into respective fields.
✅ Removed unnecessary fields such as **timestamps, links, and other metadata**.
✅ Eliminated **null values** and inconsistencies.
✅ Ensured uniformity in **formatting and structuring**.

This step played a crucial role in enhancing the performance of our model.

---

# **Model Training & Implementation**

Due to some unforeseen complications, we **did not have sufficient time** to properly train and test our AI model. To compensate for this, we included **reference code** in our project that provides a foundation for future improvements.

### **Future Enhancements:**
- Properly train and test the model with the cleaned dataset.
- Optimize the model to achieve higher accuracy.
- Implement advanced machine learning techniques for better predictions.

---

# **Graphical User Interface (GUI) Design**

A user-friendly interface is essential for ensuring a seamless experience. Thankfully, our **AI Engineer** had worked on a similar project before, which helped in designing the GUI efficiently.

Our **UI/UX Designer** put in great effort to make the design visually appealing and intuitive. The design is available in our **GitHub repository** (link attached in the repo).

### **Key Features of the GUI:**
🖥️ Simple and interactive design.
📂 Easy resume upload process.
📌 Quick and accurate career recommendations.

---

# **Conclusion & Future Scope**

Our project lays the foundation for an intelligent resume classifier that can help individuals identify the best career field based on their qualifications. While we faced time constraints that limited our model training, we believe that with further refinements, this system has the potential to revolutionize career guidance.

### **Next Steps:**
- **Properly train and test** the AI model.
- **Enhance GUI** for a more engaging experience.
- **Expand the dataset** to include more diverse resumes.

This project serves as an important step towards automating career recommendations using AI. 🚀

---

📌 **GitHub Repository:** https://github.com/ahmednoor2003/Code-Flow-Project

