# Cloud Fleet Manager Automation System 🚢

A comprehensive Python automation tool that streamlines document downloading and purchase order processing for Cloud Fleet Manager (CFM) marine management platform.

## 🎯 Problem Solved

Manual document processing in CFM was taking **4-6 hours daily** - a repetitive, time-consuming task that involved:
- Navigating through hundreds of orders
- Downloading individual documents
- Attaching purchase orders to each document
- Managing failed downloads
- Tracking progress manually

## ✨ Solution

This automation system reduces the entire workflow to **30 minutes**, saving **20+ hours per week** with:
- ✅ Automated browser navigation using Selenium
- ✅ Intelligent retry logic for failed operations
- ✅ User-friendly GUI interface (Tkinter)
- ✅ Progress tracking and detailed logging
- ✅ Automatic PO attachment workflow
- ✅ Resume capability for interrupted sessions
- ✅ Error handling and recovery mechanisms

## 🛠️ Tech Stack

- **Python 3.x**
- **Selenium WebDriver** - Browser automation
- **Tkinter** - GUI interface
- **Pandas** - Excel/CSV processing
- **openpyxl** - Excel file handling
- **ChromeDriver** - Chrome browser control

## 📋 Features

### Core Functionality
- 🔐 Automated login with credential management
- 📥 Bulk document downloading from CFM portal
- 📎 Automatic PO attachment based on ship names
- 🔄 Smart retry logic (up to 3 attempts per document)
- 📊 Excel-based order list processing
- 💾 Automatic progress saving

### User Interface
- 🖥️ Clean, intuitive GUI
- 📈 Real-time progress tracking
- 📝 Live logging console
- ⏸️ Pause/Resume functionality
- 🎨 Professional design with status indicators

### Reliability Features
- ⚠️ Comprehensive error handling
- 🔍 Problematic order tracking
- 📄 Detailed log files
- 🔄 Session recovery
- ✅ Verification checks

## 🚀 How It Works

1. **Load Order List**: Upload Excel file with order numbers
2. **Configure Settings**: Select download paths and options
3. **Automated Process**:
   - Logs into CFM portal
   - Searches each order number
   - Attaches appropriate PO template
   - Downloads documents automatically
   - Handles errors and retries
   - Tracks progress
4. **Review Results**: Check logs and problematic orders list

## 📊 Results & Impact

- ⏱️ **Time Savings**: 4-6 hours → 30 minutes (85% reduction)
- 📈 **Efficiency**: 20+ hours saved per week
- ✅ **Accuracy**: 100% with automatic error handling
- 👥 **Usability**: Non-technical users can operate easily
- 💰 **ROI**: Massive productivity improvement

## 🔧 Installation
```bash
# Clone repository
git clone https://github.com/aliahmedkhan0836/cloud-fleet-automation.git
cd cfm-automation

# Install dependencies
pip install -r requirements.txt

# Download ChromeDriver (match your Chrome version)
# Place in project directory or system PATH
```

## 📖 Usage
```bash
# Run the application
python cfm_downloader_gui.py
```

### Configuration
1. Launch the application
2. Enter CFM credentials
3. Load Excel file with order numbers
4. Select download directory
5. Choose PO attachment options
6. Click "Start Download"

## 📁 Project Structure
```
cfm-automation/
├── cfm_downloader_gui.py    # Main application with GUI
├── requirements.txt          # Python dependencies
├── config.json              # Configuration settings (gitignored)
├── logs/                    # Application logs
├── downloads/               # Downloaded documents
└── README.md               # This file
```

## ⚙️ Configuration Options

- **Retry Attempts**: Configurable retry count for failed downloads
- **Timeout Settings**: Adjustable wait times for page loads
- **PO Templates**: Customizable template selection logic
- **Download Path**: User-defined save locations
- **Logging Level**: Adjustable verbosity

## 🔒 Security

- Credentials stored locally (not in code)
- Config files excluded from repository (.gitignore)
- Secure authentication handling
- No data transmitted externally

## 🐛 Error Handling

The system handles multiple error scenarios:
- Network timeouts
- Element not found exceptions
- File download failures
- Session interruptions
- Invalid order numbers
- Missing PO templates

## 📝 Requirements
```
selenium>=4.0.0
pandas>=1.3.0
openpyxl>=3.0.0
tkinter (included with Python)
```

## 🤝 Use Cases

Perfect for:
- Shipping & logistics companies
- Marine management operations
- Fleet documentation processing
- Bulk document downloads
- Automated data entry workflows

## 📧 Support & Contact

For questions, customization, or similar automation projects:
- 📧 Email: aliahmedkhan0836@gmail.com
- 💼 Upwork: [Ali K.](https://www.upwork.com/freelancers/~01a50f7bd70f36bb33)
- 🐙 GitHub: [aliahmedkhan0836](https://github.com/aliahmedkhan0836)

## 📄 License

MIT License - Feel free to use and modify for your projects

---

**⚡ Built with Python | Automated with Selenium | Designed for Efficiency**

*Turning repetitive tasks into one-click solutions*
