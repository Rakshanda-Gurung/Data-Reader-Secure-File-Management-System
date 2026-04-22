# Data-Reader (Secure-File-Management-System)
 
Data Reader  is a Streamlit-based web application that enables users to securely manage and preview files using PIN-based protection. The application supports full CRUD operations, file searching, and basic image editing, making it a complete and user-friendly file management solution.

 ## Features
- Security
- PIN-based file access control
- Secure PIN storage using SHA-256 hashing
- Prevents unauthorized file access

 ## File Management (CRUD)
- **Create** – Upload and securely store files
- **Read** – Preview files after PIN verification
- **Update** – Edit text, document, PDF, and image files
- **Delete** – Secure file deletion with preview
- **Search** – Search files by name

 ## Supported File Formats
- Text files (.txt)
- PDF documents (.pdf)
- Word documents (.docx)
- Images (.jpg, .jpeg, .png)
  
 ## Tech Stack
- **Python**
- **Streamlit** – Web application framework
- **Pillow (PIL)** – Image processing
- **PyPDF2** – PDF file reading
- **python-docx** – Word document handling
- **ReportLab** – PDF generation
- **Hashlib** – Secure PIN hashing
- **BytesIO** – In-memory file handling

 ## Install Dependencies
- pip install -r requirements.txt

 ## Run the Application
- streamlit run data7.py
- python -m streamlit run data7.py

- <a href = "https://data-reader-secure-file-management-system-zmewpnynpkmuxarghkyu.streamlit.app/">Data Reader </a>
