# Workflow Builder (WFB)

A visual **Workflow Builder** built using **React (Vite)** and **Redux Toolkit**.  
This project allows users to create structured workflows using **Action**, **Condition (True/False)**, and **End** nodes with enforced rules and clean UI logic.

---

##  Live Demo

 Deployed on **Vercel**  
🔗[https://wfb-sigma.vercel.app/]
---

##  Features

- Tree-based workflow structure
- Action nodes with linear flow
- Condition nodes with **True / False branching**
- End nodes with **zero outgoing connections**
- Rules enforced to prevent invalid workflows
- Add & delete nodes with **auto-reconnect**
- Recursive rendering of workflow nodes
- Clean and minimal UI
- State managed using **Redux Toolkit**

---

##  Workflow Rules

- **Start node**
  - Can add Action or Condition
  - Cannot be deleted

- **Action node**
  - Can add Action
  - Can add Condition (only if not part of a branch)
  - Can add End
  - Only one outgoing connection allowed

- **Condition node**
  - Can only add True and False branches
  - Maximum two children (True / False)

- **End node**
  - Final step of a workflow
  - No outgoing connections
  - No actions allowed

---

##  Tech Stack

- **React** (Vite)
- **Redux Toolkit**
- **JavaScript**
- **CSS**
- **Vercel** (Deployment)
- **GitHub** (Version Control)

---

## Project Structure

