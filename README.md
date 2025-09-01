# Task 2: Grafana Dashboard

This task builds on **Task 1** by adding a **Grafana dashboard** to visualize metrics collected from your Node.js application using **Prometheus**. The goal is to create a complete monitoring setup with automated Grafana provisioning.

---

## 🚀 Project Overview

- **Node.js Application:** app.js serves as the main application exposing metrics.
- **Prometheus:** Scrapes metrics from the Node.js app.
- **Grafana:** Visualizes metrics using dashboards.
- **Goal:** Add **Grafana visualization** on top of Task 1 metrics.

---

## 📂 Folder Structure

task02-grafana-dashboard/
│
├── app.js # Node.js application exposing metrics (from Task 1)
├── package.json # Node.js dependencies (from Task 1)
├── prometheus.yml # Prometheus configuration (from Task 1)
├── dashboard.json # Exported Grafana dashboard JSON
├── dashboards.yaml # Grafana provisioning configuration for dashboards
├── datasources.yaml # Grafana provisioning configuration for data sources
└── README.md # This setup guide
