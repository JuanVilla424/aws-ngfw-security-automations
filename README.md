# 📄 AWS NGFW Security Automations

![AWS CloudFormation](https://img.shields.io/badge/AWS-CloudFormation-blue)
![YAML](https://img.shields.io/badge/YAML-CB171E?logo=yaml&logoColor=fff)
![AWS Lambda](https://img.shields.io/badge/AWS-Lambda-FF9900)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)
![Status](https://img.shields.io/badge/Status-Development-blue.svg)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

Welcome to the **AWS NGFW Security Automations** repository! This project offers a comprehensive and automated solution for deploying Virtual Private Clouds (VPCs) with integrated network firewalls on AWS on non AWS Organization member accounts. Designed to streamline the setup and management of secure network infrastructures, this template leverages Infrastructure as Code (IaC) tools to ensure consistency, scalability, and ease of maintenance.

## 📚 Table of Contents

- [Features](#-features)
- [Architecture Diagram](#-architecture-diagram)
- [File Structure](#-file-structure)
- [License](#-license)
- [Contact](#-contact)

## 🌟 Features

- **Automated VPC Creation**

  - Streamlines the setup of Virtual Private Clouds with minimal manual intervention.

- **Integrated Network Firewall**

  - Deploys advanced network firewalls to secure your infrastructure from threats.

- **Customizable Subnets and Routing**

  - Configure public and private subnets, routing tables, and gateways tailored to your requirements.

- **Predefined Security Policies**

  - Includes default security rules and policies that can be customized to meet specific security needs.

- **Infrastructure as Code (IaC) Support**

  - Utilizes tools like Terraform or CloudFormation for reproducible and version-controlled deployments.

- **Scalability and Flexibility**

  - Easily scales to accommodate growing network demands and adapts to varying infrastructure needs.

- **Monitoring and Logging**

  - Integrates with monitoring tools and provides detailed logs for network traffic and firewall activities.

- **High Availability and Redundancy**

  - Ensures reliable network operations with redundant configurations and failover mechanisms.

- **Easy Integration with Existing Systems**

  - Seamlessly connects with existing cloud resources and on-premises infrastructure.

- **Security Best Practices**

  - Implements industry-standard security measures to ensure robust protection of your network.

- **Comprehensive Documentation and Support**

  - Provides detailed guides and support resources to assist with deployment and management.

- **User-Friendly Configuration Interface**
  - Offers an intuitive interface for configuring and managing your VPC and firewall settings.

## 🖼️ Architecture Diagram

![Diagram](https://github.com/JuanVilla424/aws-ngfw-security-automations/blob/dev/source/image/architecture_diagram.png?raw=true)

## 📁 File Structure

This project consists of microservices that facilitate the functional areas of the solution. These microservices are deployed to a serverless environment in AWS Lambda.

```
|-deployment/ [folder containing templates and build scripts]
|-source/
  |-image/                  [folder containing images of the solution such as architecture diagram]
  |-layout/                 [folder containing base diagram editable layout]
```

## 📫 Contact

For any inquiries or support, please open an issue or contact [r6ty5r296it6tl4eg5m.constant214@passinbox.com](mailto:r6ty5r296it6tl4eg5m.constant214@passinbox.com).

---

## 📜 License

© 2025 **AWS**. All rights reserved. Unauthorized use, reproduction, or distribution is strictly prohibited. For more details, please refer to the [LICENSE](LICENSE) file included in this repository.
