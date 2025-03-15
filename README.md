# 🖥️ My First Shell Script  

![Shell Scripting](https://upload.wikimedia.org/wikipedia/commons/8/82/Bash_Logo_Colored.svg)  

## 📌 Overview  
This is a beginner-friendly **Bash script** 🐧 that prompts the user to enter a number and then displays the entered value. It is designed to introduce users to shell scripting in an easy and interactive way.  

## 🌟 Features  
✔️ Simple and easy-to-use 📜  
✔️ Accepts **user input** 📝  
✔️ Displays the **entered value** 📊  
✔️ Beginner-friendly and customizable 🛠️  

## ⚙️ Prerequisites  
Before running the script, ensure that:  
- 🏷️ You have **Linux/macOS** with **Bash** installed (default on most distributions).  
- 🔒 You have **execution permissions** for the script.  

## 🚀 Installation & Execution  

### 📥 1. Clone the Repository (Optional)  
If using Git, run:  

\```bash  
git clone <your-repo-url>  
cd <your-repo-folder>  
\```

### 📝 2. Save the Script  
Copy and save the following script as `myscript.sh`:  

\```bash  
#!/bin/bash  

# 🖥️ My First Shell Script  
# 📅 Date: [YYYY-MM-DD]  
# ✍️ Author: [Your Name]  
# 📝 Description: A simple script that prompts the user for a number and displays it.  

# 📌 Prompt user for input  
read -p "🔢 Enter a number: " no1  

# 📊 Display the entered number  
echo "✅ You entered: $no1"  
\```

### 🔑 3. Grant Execution Permission  
Run the following command to **make the script executable**:  

\```bash  
chmod +x myscript.sh  
\```

### ▶️ 4. Run the Script  
Execute the script using:  

\```bash  
./myscript.sh  
\```

## 📌 Expected Output  
\```bash  
🔢 Enter a number: 10  
✅ You entered: 10  
\```

## 📌 How to Format Code Blocks in Markdown  
To display **copyable command boxes** like the ones above, wrap your commands inside **triple backticks (\`\`\`)** followed by the language (e.g., `bash` for shell scripts).  

Example:  
\`\`\`bash  
echo "Hello, World!"  
\`\`\`  

🔹 This ensures that the Markdown file properly converts it into a **formatted code block** when rendered.  

## 🔧 Customization Ideas  
- ✅ Add **input validation** to ensure only numbers are entered.  
- 🔄 Modify it to accept **multiple inputs** and perform calculations.  
- 🛠️ Extend the script to **log inputs** and save them to a file.  

## 🤝 Contributing  
Want to improve this script? Feel free to **fork**, **modify**, and submit a **pull request**!  

## 📜 License  
This script is released under the **MIT License** 📄.  

## 👤 Author  
🚀 **[Your Name]**  
📧 [Your Email]  
🔗 [Your Website/GitHub Profile]  
