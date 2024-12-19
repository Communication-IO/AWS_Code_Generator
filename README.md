# AWS Actions List in JSON Format

<!-- 
This repository contains a collection of JSON files. Each JSON file provides a comprehensive list of AWS actions for various AWS services and products. These files are structured to help developers, system architects, and security professionals explore and utilize AWS actions effectively.
-->

## Overview

This repository serves as a central resource for AWS actions documentation. Each JSON file corresponds to a specific AWS service and contains a detailed list of all available actions, including:

- **Service Name**: The AWS service or product.
- **Action Name**: The specific actions supported by the service.
- **Description**: A brief description of what each action does.
- **Permissions**: Associated IAM permissions required for the action.

## Structure

The JSON files are organized as follows:

```json
{
    "ServiceName": "ExampleService",
    "Actions": [
        {
            "ActionName": "example:ActionName",
            "Description": "A brief description of the action.",
            "Permissions": "Permissions required"
        },
        ...
    ]
}
