# MS_Fabric_LAB_21
# 🚀 Microsoft Fabric Deployment Pipelines Lab

This repository contains the steps and screenshots from a hands-on lab exercise where we implemented **Deployment Pipelines in Microsoft Fabric**.

## 🎯 Objective

Learn how to:
- Create development, test, and production workspaces in Microsoft Fabric
- Set up a deployment pipeline
- Assign workspaces to pipeline stages
- Create content (Lakehouse)
- Deploy content between stages
- Validate synchronized content across environments

---

## 🧪 Lab Steps

### 1️⃣ Create Workspaces
- Navigate to [Microsoft Fabric](https://app.fabric.microsoft.com/home?experience=fabric)
- Create 3 workspaces:
  - `Development`
  - `Test`
  - `Production`
- Ensure Fabric Trial is enabled for each workspace

### 2️⃣ Create a Deployment Pipeline
- Go to **Deployment Pipelines** → **New Pipeline**
- Name the pipeline (e.g., `LakehousePipeline`)
- Proceed to create and configure stages

### 3️⃣ Assign Workspaces to Pipeline Stages
- Assign:
  - Development workspace to **Development stage**
  - Test workspace to **Test stage**
  - Production workspace to **Production stage**

### 4️⃣ Create Content in Development
- Go to the `Development` workspace
- Create a **Lakehouse** named `LabLakehouse`
- Load **sample data (NYCTaxi)** into the Lakehouse

### 5️⃣ Deploy Between Stages
- Deploy from `Development → Test`
- Deploy from `Test → Production`
- Confirm green check marks between each stage (content is synced)

### 6️⃣ Verify Content in Workspaces
- Check that the `LabLakehouse` exists in the `Test` and `Production` workspaces

---

## 🧹 Clean Up
- Navigate to each workspace
- Go to **Workspace Settings** → **Remove this workspace** if needed

---

## 🧠 Learn More
- [Microsoft Fabric Documentation](https://learn.microsoft.com/fabric/)
- [Deployment Pipelines Overview](https://learn.microsoft.com/fabric/cicd/deployment-pipelines)

---


