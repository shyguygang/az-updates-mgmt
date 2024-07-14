# 🤖 Azure Automation and Update Management Setup

![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)

This PowerShell script automates the setup of Azure Automation and Update Management for your Azure environment.

## 📋 Table of Contents

- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [Functions](#-functions)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- Create and manage Azure Automation accounts
- Set up Log Analytics Workspaces
- Connect VMs to Log Analytics Workspaces
- Configure Azure Update Management
- Deploy Azure Updates Dashboard Workbook and Alerts

## 🛠 Prerequisites

- Azure PowerShell modules (`Az.OperationalInsights`, `Az.Automation`, `Az.Resources`)
- Azure subscription with appropriate permissions
- PowerShell 5.1 or later

## 💾 Installation

1. Clone this repository:
git clone https://github.com/yourusername/azure-automation-setup.git

2. Navigate to the project directory:
cd azure-automation-setup

## 🚀 Usage

1. Open PowerShell and navigate to the project directory.
2. Run the script:
```powershell
.\AzureAutomationSetup.ps1
```
3. Follow the on-screen prompts to set up your Azure environment.

## 🔧 Functions

- Connect-ToAzure: Connects to Azure and sets the context
- Show-MainMenu: Displays the main menu options
- Invoke-Option1: Checks/creates Automation Account and lists Log Analytics Workspaces
- Invoke-Option2: Creates new Log Analytics Workspace and deploys
- Invoke-Option3: Enables Azure Update Management on existing LAW
- Connect-VMsToLAW: Connects VMs to Log Analytics Workspace
- Setup-AzureUpdateManagement: Sets up Azure Update Management
<p></p>
- 👥 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
<p></p>
- 📄 License
This project is licensed under the GNU License - see the LICENSE file for details.

```<center>
  Made with ❤️ by g0hst
