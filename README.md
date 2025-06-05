📦 ByteNode - Distributed File Storage System using Django + IPFS
ByteNode is a distributed file storage solution built using Django and IPFS (InterPlanetary File System). Designed for high availability, fault tolerance, and efficient file management, ByteNode intelligently chunks and distributes files across multiple nodes, ensuring redundancy and reliability.

🚀 Key Features
🔐 Secure Authentication: Django-based user login, registration, and role management

📁 File Chunking: Automatically splits files into 1MB chunks for scalable upload and download

🌐 IPFS Integration: Redundant storage across multiple IPFS nodes to ensure data persistence

🩺 Health Monitoring: Detects and repairs missing chunks, supports self-healing mechanisms

⚖️ Load Balancing: Prevents node overload with dynamic chunk redistribution

🧩 Chunk Tracking: View detailed metadata and distribution of every file

🛠️ Admin Dashboard: Visual system stats, node diagnostics, and distribution health checks

🌍 RESTful API: Complete API set for file management and node configuration

🖥️ Screenshots
1. Login & Authentication: Secure entry point for users with login and registration using Django’s auth system.
![1](https://github.com/user-attachments/assets/a4ac61f1-aeb2-493a-8010-193e5e8b1332)

2. Admin Dashboard
Displays system stats including file count, chunk distribution, replication health, and node status.
![2](https://github.com/user-attachments/assets/58f0850b-591b-4860-a93d-bf52dcf73d7b)

3. File Management
Lets users upload, download, and delete files. Chunk details and metadata shown for each.
![3](https://github.com/user-attachments/assets/dda98ffd-85ea-4432-b509-a7c5e2861ae5)

4. Health Check & Chunk Stats
Visual indicators of chunk redundancy and overall storage health across nodes.
![4](https://github.com/user-attachments/assets/ad4c9596-0f2b-4021-9bab-a8036f759c4d)

5. File Details
Detailed view showing file info, IPFS hashes, chunk size, and distribution across nodes.
![6](https://github.com/user-attachments/assets/19b45345-77c6-49f4-af6d-d50b38b0f631)

7. Django Admin Interface
Backend interface to manage nodes, file chunks, users, and distributions via Django.
![7](https://github.com/user-attachments/assets/266a0142-fea6-4115-afec-a81fdd7eb1d2)

8. Node Diagnostic Tool
Allows testing, adding, and configuring new IPFS nodes with storage details.
![8](https://github.com/user-attachments/assets/5a467743-ebe9-412d-84ea-dbea5b835846)

10. Upload File Interface
Real-time visual feedback during file upload and distribution across the system.
![9](https://github.com/user-attachments/assets/b564d9c2-2db6-4d61-bfc2-c461dca7a9b8)

11. System Node List
Table listing all IPFS nodes with their status, storage load, and diagnostics.


⚙️ Technologies Used
Django + Django REST Framework

IPFS (Local or remote nodes)

PostgreSQL (or SQLite for development)

Bootstrap (UI Styling)

📂 Project Structure
/storage/: IPFS Node simulation & management

/api/: REST API for file upload/download & metadata

/dashboard/: Admin panel for diagnostics & health monitoring

📽️ Demo Video: 
This video covers:

Installation & setup
File upload and chunk distribution
Monitoring system health
Troubleshooting common issues

📌 How to Run
git clone https://github.com/your-username/bytenode.git
cd bytenode
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Ensure IPFS daemon or simulation is running on designated ports.


🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
