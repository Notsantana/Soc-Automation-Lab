
# SOC Automation Project

Welcome to the SOC Automation Project! This project aims to provide a hands-on experience in setting up a Security Operations Center (SOC) environment with automation capabilities using Wazuh and The Hive.

## Introduction

The SOC Automation Project guides you through the process of setting up a full-blown Wazuh instance integrated with a Security Orchestration, Automation, and Response (SOAR) platform, The Hive. By following this project, you'll gain practical experience in cybersecurity, specifically within the domain of security operations.

## Setup Instructions

To get started with the project, follow these setup instructions:

1. Install necessary dependencies (e.g., draw.io for diagram creation).
2. Set up the environment for deploying Wazuh, The Hive, and other required components.

## Building the Diagram

The first step in the project is to build a network diagram using draw.io. This diagram visually represents the logical flow of data and the components involved in the SOC environment.

## Network Diagram

![net diagram](https://github.com/Notsantana/Soc-Automation-Lab/assets/70494918/9a470732-b8c4-4537-8cfa-1d18abc00ba8)

## Diagram Components

Here's a breakdown of the components depicted in the diagram:

- Windows 10 client: Sends events to Wazuh.
- Wazuh manager: Analyzes events and triggers alerts.
- The Hive: SOAR platform for case management.
- Shuffle: Performs open-source intelligence gathering and enrichment.
- SOC analyst workstation: Receives alerts and performs actions.

## Workflow Explanation

The workflow depicted in the diagram outlines the sequence of events from data generation to response actions within the SOC environment. 

1. Windows 10 client sends events to Wazuh manager.
2. Wazuh manager triggers alerts or performs responsive actions based on the events.
3. Wazuh manager sends alerts to Shuffle.
4. Shuffle receives alerts, enriches IOC's, sends emails, and creates alerts in The Hive.
5. Shuffle sends emails to SOC analyst.
6. SOC analyst receives emails, reviews alerts, and responds with actions.
7. Actions from SOC analyst are sent back to Shuffle.
8. Shuffle sends responsive actions to Wazuh manager.
9. Wazuh manager instructs Windows 10 client to perform responsive actions.


![work flow](https://github.com/Notsantana/Soc-Automation-Lab/assets/70494918/b8dc822c-0d12-400c-ae5a-d37a5d495219)

## Installation Guide

Follow these steps to install and configure Wazuh, The Hive, and other required software components:

1. Install Wazuh and configure it according to the provided instructions.
2. Set up The Hive and integrate it with Wazuh for case management.
3. Deploy Shuffle and configure it for open-source intelligence gathering.

## Usage Instructions

Once the environment is set up, you can use the deployed system for various security operations tasks. Refer to the usage instructions for examples of scenarios and how the system responds to them.

## Troubleshooting

Encounter an issue? Check out our troubleshooting guide for common issues and their solutions.

## Contributing Guidelines

Contributions to the project are welcome! Follow our contributing guidelines to submit bug reports, feature requests, or code contributions.

## Conclusion

The SOC Automation Project provides a comprehensive guide to setting up a SOC environment with automation capabilities. Get started today and enhance your skills in cybersecurity operations!

For questions or further inquiries, feel free to contact us at [contact@example.com](mailto:contact@example.com).
