# IBMBob-and-IBMCloud

# IBM Bob and IBM Cloud

This repository contains public samples, configurations, and notes for using **IBM Bob with IBM Cloud**.

The repository currently includes one custom mode. Additional IBM Bob and IBM Cloud content may be added over time, including custom modes, MCP configurations, examples, and supporting documentation.

## Contents

### Custom Modes

#### IBM Cloud Service Instance Report

A read-only custom mode that uses an existing IBM Cloud CLI session to:

- Discover IBM Cloud service instances
- Filter results by region, resource group, and service type
- Organize Kubernetes and OpenShift clusters at the cluster level
- Generate searchable HTML reports

File:

- [`custom-modes/ibm-cloud-service-instance-report/ibmcloud-service-instance-report.custom_modes.yaml`](custom-modes/ibm-cloud-service-instance-report/ibmcloud-service-instance-report.custom_modes.yaml)

## How to Use a Custom Mode

1. Download the custom mode YAML file.
2. Open **Bob Settings**.
3. Select **Modes**.
4. Import the downloaded YAML file.
5. Select the imported mode from the mode selector in Bob Chat.

Review the YAML and its permissions before use. For the IBM Cloud Service Instance Report mode, install the IBM Cloud CLI and log in to the target account before starting.

## Repository Structure

```text
Bob-and-IBMCloud/
├── README.md
├── custom-modes/
│   └── ibm-cloud-service-instance-report/
│       └── ibmcloud-service-instance-report.custom_modes.yaml
├── mcp-configs/       # Future content
├── examples/          # Future content
└── docs/              # Future content
```

Folders for future content will be added when needed.

## Important Notes

- These materials are personal samples for learning, testing, and workshops.
- They are not official IBM products, support tools, or supported assets.
- Start in a test environment and review all commands before execution.
- Never store API keys, passwords, access tokens, or other credentials in YAML files, prompts, reports, screenshots, or this repository.
- Generated reports may contain sensitive account and resource information. Review them before sharing.

## References

- [IBM Bob Documentation](https://bob.ibm.com/docs/)
- [IBM Cloud Documentation](https://cloud.ibm.com/docs)

