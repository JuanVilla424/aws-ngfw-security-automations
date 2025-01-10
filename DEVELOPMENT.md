## 🚀 Getting Started

### 📋 Prerequisites

**Before you begin, ensure you have met the following requirements**:

- **GitHub Account:** You need a GitHub account to use GitHub Actions.
- **Python 3.11+:** Ensure Python is installed on your local machine.
- **Git:** Install [Git](https://git-scm.com/) to clone the repository.
- **NVM:** (Optional) Node.js installation environment versions control
- **Node.js 22.x+**: (Optional) (Required to Push) Used as lint orchestration manager in pre-commit and pre-push

### 🔨 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/JuanVilla424/aws-ngfw-security-automations.git
   ```

2. Navigate to the Project Directory
   ```bash
    cd aws-ngfw-security-automations
   ```

### 🔧 Environment Setup

**Mandatory: Setting Up a Python Virtual Environment**

Setting up a Python virtual environment ensures that dependencies are managed effectively and do not interfere with other projects.

1. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   ```

2. **Activate the Virtual Environment**

   On Unix or MacOS:

   ```bash
   source venv/bin/activate
   ```

   On Windows:

   ```bash
    .\venv\Scripts\activate
   ```

   - or

   ```bash
    powershell.exe -ExecutionPolicy Bypass -File .\venv\Scripts\Activate.ps1
   ```

3. **Upgrade pip**

   ```bash
   python -m pip install --upgrade pip
   ```

4. **Install Dependencies**

   - Using Poetry:

   ```bash
   pip install poetry
   poetry lock
   poetry install
   ```

   - Using Requirements:

   ```bash
   pip install -r requirements.txt
   ```

### 🛸 Pre-Commit Hooks

**Install and check pre-commit hooks**: MD files changes countermeasures, python format, python lint, yaml format, yaml lint, version control hook, changelog auto-generation

```bash
pre-commit install
pre-commit install -t pre-commit
pre-commit install -t pre-push
pre-commit autoupdate
pre-commit run --all-files
```

## 🤝 Contributing

**Contributions are welcome! To contribute to this repository, please follow these steps**:

1. **Fork the Repository**

2. **Create a Feature Branch**

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit Your Changes**

   ```bash
   git commit -m "feat(<scope>): your feature commit message - lower case"
   ```

4. **Push to the Branch**

   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request into** `dev` **branch**

Please ensure your contributions adhere to the Code of Conduct and Contribution Guidelines.

---

## 📜 License

© 2025 **AWS**. All rights reserved. Unauthorized use, reproduction, or distribution is strictly prohibited. For more details, please refer to the [LICENSE](LICENSE) file included in this repository.
