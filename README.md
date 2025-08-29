# aicore-pipelines
SAP AI Core Pipelines

# 🧠 Prompt Registry

Prompt templates allow for dynamic and structured interactions with AI models.
A **Prompt Registry** is a centralized system for storing, managing, and versioning prompt templates used in AI-driven applications. It allows developers and teams to reuse, modify, and track changes in prompts efficiently. This is particularly useful in large-scale AI projects where prompts need to be standardized, refined, and deployed across different models or scenarios.

---

## 🚀 Features

- **Consistency**: Ensures uniform prompts across different use cases.
- **Version Control**: Tracks prompt iterations and allows rollback if needed.
- **Collaboration**: Enables teams to work on prompt engineering collaboratively.
- **Automation**: Integrates prompts seamlessly into AI workflows and CI/CD pipelines.

---

## 🛠️ Prompt Management Approaches

### 1. Imperative API (Direct API Control for Dynamic Prompt Management)

The Imperative API allows you to create, update, and manage prompt templates dynamically via API calls. This approach is best suited for interactive design-time use cases, where you need to iteratively refine prompts and track their versions. Each change is explicitly made via CRUD operations, and you can manage versions manually.

### 2. Declarative API (Git-based Sync for Automated Prompt Management)

The Declarative API, on the other hand, integrates with SAP AI Core applications and is ideal for CI/CD pipelines. Instead of managing templates through direct API interactions, you define them as YAML files in a Git repository. The system automatically syncs these templates, ensuring that updates are seamlessly reflected in the prompt registry without manual intervention.
