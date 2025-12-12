# 📘 Feature Encoding & Feature Scaling 

This practical demonstrates how to apply Feature Encoding and Feature Scaling techniques commonly used in Machine Learning preprocessing. The notebook covers converting categorical data into numerical form and scaling numerical features for better model performance.

🔍 Objectives

Understand the need for feature encoding.

Perform:

Label Encoding

One-Hot Encoding

Understand and apply feature scaling techniques:

StandardScaler

MinMaxScaler

Create, preprocess, and visualize a dataset in Google Colab.

📂 Dataset Used

A small sample dataset is created containing:

Name	City	Experience	Salary
Amit	Delhi	1	30000
Sita	Mumbai	3	55000
Rohit	Delhi	2	40000
Priya	Chennai	5	80000
Kiran	Mumbai	4	65000

The dataset includes both categorical and numerical values, making it suitable for encoding and scaling demonstrations.

🛠️ Techniques Performed
⭐ 1. Feature Encoding
✅ Label Encoding

Converts categorical text data into integer values.

Example:

Delhi → 0

Chennai → 1

Mumbai → 2

✅ One-Hot Encoding

Creates new binary (0/1) columns for every category.

Example columns created:

City_Delhi

City_Mumbai

City_Chennai

⭐ 2. Feature Scaling
✅ StandardScaler

Scales data based on:

Mean = 0

Standard Deviation = 1

Useful for models like Logistic Regression, SVM, KNN, Linear Regression.

✅ MinMaxScaler

Normalizes values between 0 and 1.

Useful when features need to maintain relative distance but fit within a fixed range.

📌 Google Colab Code

The notebook includes complete executable code for:

Creating the dataset

Performing Label Encoding

Performing One-Hot Encoding

Applying StandardScaler

Applying MinMaxScaler

Displaying scaled results

📊 Output Includes

Original dataset

Label encoded dataset

One-hot encoded dataset

Standard scaled values

Min-Max scaled values

-----------------------------------------------------------------------------------------------------------
                                                Follow Me
-----------------------------------------------------------------------------------------------------------
🤝 Contributing
Feel free to fork the repository, improve the project, and submit a pull request.

📊 Connect with me:
If you want to see more DSE projects, tutorials, and updates, follow me on:

•────────────••────────────•
        👩‍💻 Author
•────────────••────────────•
# Sushil Kumar
📧 [ Email: sushilkumarnk25102@gmail.com ]
🐙 [ Git Hub: https://github.com/sushilkumar121225 ]
🔗 [ LinkedIn: https://www.linkedin.com/in/sushil-kumar-471614289/ ]
🧩 B.tech Computer Engineering (Full stack developer)

🙌 Thank You for Visiting This Repository!
Happy Learning and Keep Exploring
