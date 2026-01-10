Notes and documentation for the Helm Charts YouTube vedio series. Below is the index of topics covered, along with links to the corresponding YouTube videos.

| Topic | YouTube Video |
| :--- | :--- |
| [1. Helm Introduction](./1%20Helm%20Introduction.md) | [Watch Video](https://youtu.be/UzMT5oE6OIM) |
| [2. Helm Chart structure](./2.%20Helm%20Chart%20structure.md) | [Watch Video](https://youtu.be/ilTlbAVF-Ps) |
| [3. Helm Lifecycle](./3.%20Helm%20Lifecycle.md) | [Watch Video](https://youtu.be/8QnnkjeCHRM) |
| [4. Managing Values in Helm](./4.%20Managing%20Values%20in%20Helm.md) | [Watch Video](https://youtu.be/Llzs-Ep9Scs) |
| [5. Helm Package and Publish](./5.%20Helm%20Package%20and%20Publish.md) | [Watch Video](https://youtu.be/LPT5eGwF0H4) |
| [6. Helm versioning and linting](./6.%20Helm%20versioning%20and%20linting.md) | [Watch Video](https://youtu.be/3TnN10M-RQY) |
| [7. Helm Subcharts & Dependencies](./7.%20Helm%20Subcharts%20%26%20Dependencies.md) | [Watch Video](https://youtu.be/-BC_QpXhAQ8) |

## 1: Introduction to Helm

### 📘 Topics

- What is Helm? Why use it?
- Concepts: Chart, Release, Repository
- Where Helm fits in a CI/CD pipeline

### 🎬 Demo

- Helm basic 

---

## 2: Helm Chart Structure

### 📘 Topics

- Chart structure breakdown
    - `Chart.yaml`
    - `values.yaml`
    - `templates/`
- Templating basics
- Overriding values

### 🎬 Demo

- Create a new chart:

  `helm create myapp`

- Walk through each file

---

## 3: Helm lifecycle

### 📘 Topics

- Helm lifecycle
- Helm Install
- Viewing a release
- Overriding values at install time
- Helm Upgrade
- Helm Rollback
- Dry-run, diff, and debugging
- Helm uninstall

### 🎬 Demo

- `helm install`
- `helm upgrade`
- `helm rollback`
- Using namespaces

---

## 4: Managing Values in Helm

### 📘 Topics

- Creating env specific values
- Precedence of values in Helm
- Debugging Values
- Handling Secrets

### 🎬 Demo

- Creating and managing env specific values
- `values-dev.yaml`, `values-prod.yaml`
- `helm install -f values-dev.yaml`

---

## 5: Packaging, Releasing & Repositories

### 📘 Topics

- Packaging charts
- Hosting repositories
- GitHub Pages as a repo

### 🎬 Demo

- `helm package`
- `helm repo index`
- Push chart to GitHub Pages

---

## 6: Helm versioning and linting

### 📘 Topics
- chart version vs app version
- incrementing versions
- Linting & testing charts

### 🎬 Demo

- Usage of `helm lint`

---

## 7: Advanced Helm Patterns

### 📘 Topics

- Subcharts & dependencies
- Using global values
- Library charts

### 🎬 Demo

- Add a dependency using `Chart.yaml`
- Building dependency helm chart
- Using dependency helm chart in dev, uat, prod by overriding values


**Please follow and subscribe to my channel for more DevOps, Cloud, DevSecOps, and other topics of DevOps: [**Tech Hustle with UG**](https://www.youtube.com/@techhustlewithUG)**

