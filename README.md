🌟 Jenkins Log S3 Optimizer 🌟
🚀 Project Overview
The Jenkins Log S3 Optimizer is a cost-saving automation solution designed to efficiently manage Jenkins logs by moving them from local storage to Amazon S3. Instead of relying on ELK stack, which incurs high costs, this project transfers logs to S3, where they are automatically archived or deleted based on a lifecycle policy, reducing storage costs by up to 50%.

🔍 Problem Statement
Jenkins failure build notifications were already set up via Gmail and Slack, eliminating the need for long-term log retention in ELK stack.
However, logs were still being stored in ELK, resulting in unnecessary storage costs.
💡 Solution
✅ Automated log migration – A Bash script scans Jenkins job directories and moves daily logs to an S3 bucket.
✅ No plugins required – Uses AWS CLI instead of Jenkins extensions, ensuring a lightweight and efficient solution.
✅ Cost-efficient storage – Leverages S3 Lifecycle Policies to automatically transition old logs to Amazon Glacier or Deep Archive for lower costs.
✅ Scalable & hands-free – Works across multiple Jenkins job directories, requiring zero manual intervention.

🛠 Technologies Used
🐧 Bash Scripting
🏗 Jenkins
☁️ AWS S3
🔧 AWS CLI
✨ Benefits
🔹 Simplifies log management without relying on third-party tools.
🔹 Reduces cloud storage costs by eliminating unnecessary retention.
🔹 Ensures compliance & efficiency with automated log handling.

📸 Screenshots
Dummy job
![dummy-job](https://github.com/user-attachments/assets/8b884159-dbae-4a6b-b412-4e8daabf0962)

Run script 
![terminal](https://github.com/user-attachments/assets/851cae62-6012-489e-99dd-b220a87b44d2)

