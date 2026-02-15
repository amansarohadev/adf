# Azure Data Factory (ADF) Data Engineering Project

This repository serves as a comprehensive **Azure Data Factory (ADF)** solution demonstrating enterprise-grade data engineering patterns. It showcases end-to-end data pipelines, complex transformations using Mapping Data Flows, and robust orchestration strategies.

The project implements real-world scenarios including:
- **Data Ingestion**: Automated data movement from various sources (e.g., Blob Storage) using Copy Activities.
- **Data Transformation**: Advanced logic using **Mapping Data Flows** to clean, filter, aggregate, and split data streams (e.g., processing transaction logs by payment method).
- **Control Flow**: Orchestration of dependent tasks, error handling, and pipeline chaining (e.g., `PipelineManager` executing child pipelines).
- **Maintenance**: Automated cleanup tasks and file management.

This project is designed for Data Engineers to explore best practices in ETL/ELT workflows within the Azure ecosystem.

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

