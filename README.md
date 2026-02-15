# Azure Data Factory (ADF) Repository

This repository contains Azure Data Factory (ADF) resources including pipelines, datasets, linked services, and triggers. It serves as a demonstration and learning resource for ADF components and data engineering workflows.

## 📂 Project Structure

The repository is organized into the following standard ADF folders:

- **pipeline/**: Contains JSON definitions for ADF pipelines (e.g., control flow, data movement activities).
- **dataset/**: JSON definitions for datasets (inputs/outputs for activities).
- **linkedService/**: Connection strings and configurations for external data stores and compute resources.
- **dataflow/**: Mapping Data Flow definitions for data transformation logic.
- **trigger/**: Definitions for scheduling and event-based triggers.
- **factory/**: Factory-level resources.

## 🚀 Getting Started

### Prerequisites

- An active **Azure Subscription**.
- An existing **Azure Data Factory** instance (v2).
- **Azure DevOps** or **GitHub** integration configured in your ADF instance (optional but recommended for CI/CD).

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/amansarohadev/adf.git
   ```

2. **Connect to ADF**:
   - Go to the [Azure Portal](https://portal.azure.com).
   - Open your Data Factory instance.
   - Launch **Azure Data Factory Studio**.
   - Ensure your ADF is connected to this repository (if configured for Git integration).

3. **Deploy/Publish**:
   - If using Git integration, you can import these resources directly by mapping the repository in ADF Studio.
   - Alternatively, you can use ARM templates (if generated) or manual JSON import for specific resources.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

