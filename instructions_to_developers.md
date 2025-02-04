# Developer Guide - Issue Management and Workflow

Welcome to the subrouts.com issue tracking system! This document provides guidelines for managing issues, using labels, and tracking progress effectively. Follow these instructions to maintain a clean and organized workflow in the repository.

---

## **1. Understanding the Labels**

We use a set of labels to categorize issues and track their status. Here are the most commonly used labels:

### **Labels and Their Meaning:**

- **`in progress`**:  
    This label indicates that a developer is actively working on the issue. It should be added when you start working on an issue and removed once the issue is resolved or completed.
    
- **`awaiting issues`**:  
    This label is used for issues that require more details or input from the user or another team member before they can be worked on. If an issue has this label, it typically means that the task is blocked until more information is provided.
    
- **`bug`**:  
    This label indicates that the issue is related to a bug or unexpected behavior in the project.
    
- **`enhancement`**:  
    This label is used when the issue is a request for a new feature or improvement.
    
- **`help wanted`**:  
    This label is used when the project or issue requires assistance from contributors. It's typically used for issues that need support or extra hands.
    
- **`closed`**:  
    This label is used when an issue has been resolved or the task is completed. Once an issue is fully fixed and merged into the main branch, it should be marked as **closed**.
    

---

## **2. How to Handle Issues**

When you are working on an issue, please follow the steps below to ensure the issue is managed properly.

### **Step 1: Reviewing the Issue**

- When a new issue is created, carefully review the details provided. If the issue is not clear or lacks essential information, add the **`awaiting issues`** label. You can also leave a comment asking for more details before work can begin.
- If the issue is clear, proceed to the next step.

### **Step 2: Assigning the Issue**

- If the issue is relevant and you are working on it, **assign yourself** to the issue.
- If you are not able to work on the issue but someone else is, feel free to **assign the issue** to another developer or collaborator.

### **Step 3: Adding the "In Progress" Label**

- Once you start working on the issue, add the **`in progress`** label. This helps other team members see which issues are actively being worked on.

### **Step 4: Working on the Issue**

- Start fixing the bug or implementing the feature as described in the issue.
- If you encounter any questions or require further clarification, leave a comment in the issue.
- Keep the issue updated with progress notes so others can follow along.

### **Step 5: Resolving the Issue**

- Once the issue is fixed, create a **Pull Request (PR)** with your changes.
- In the PR description, refer to the issue number (e.g., `Fixes #10` or `Closes #10`). This will automatically link the PR to the issue and close it once the PR is merged.
- Remove the **`in progress`** label and add the **`closed`** label when the issue is resolved.

### **Step 6: Handling Blocked or Waiting Issues**

- If an issue is blocked (e.g., waiting on user input or another task), mark it with the **`awaiting issues`** label.
- Once the block is resolved, reassign the issue and remove the **`awaiting issues`** label to indicate it is ready to be worked on.

---

## **3. Best Practices for Managing Issues**

### **A. Communication**

- Always **comment** on issues if you need more information or clarification.
- Keep comments clear and concise, updating the issue status or your progress regularly.
- If you are working on an issue and need additional context, ask the creator or team for more details.

### **B. Issue Priority and Importance**

- Some issues might have higher priority than others. If needed, mention the priority in the issue description or in comments.
- If an issue needs to be worked on immediately, label it with **`urgent`** (if you choose to use this label in your project).

### **C. Keeping Issues Up-to-Date**

- Regularly check and update the issues you are working on.
- If an issue is resolved but the PR is still pending, you can add a comment with the status update (e.g., "Waiting for review").

### **D. Closing Issues**

- Once an issue is resolved and merged, always **close** the issue to mark it as completed.
- If you believe an issue is no longer relevant or cannot be fixed, add a comment explaining the situation and close it.

---

## **4. Special Notes for New Contributors**

For new contributors, please follow the steps below when submitting an issue:

1. **Use the Templates**: Always use the provided issue templates (Bug Report, Feature Request, etc.). These will help ensure that your issue is well-structured and contains all the necessary information.
2. **Be Detailed**: The more detail you provide, the better. For bugs, include steps to reproduce, screenshots, logs, and system details.
3. **Be Patient**: If you don't receive a response immediately, please be patient. We’ll get to your issue as soon as possible.
4. **Comment and Follow-Up**: If someone asks you for more information, please reply as soon as possible so that we can continue resolving the issue.

---

## **5. How to Apply Labels and Change Issue Status**

### **To Apply or Change a Label:**

- Open the issue.
- On the right side of the issue page, you’ll find the **Labels** section.
- Click on **Labels** to view a list of available labels, and click the label you want to add to the issue (e.g., **`in progress`**, **`awaiting issues`**).
- You can apply multiple labels if needed.

### **To Assign an Issue:**

- In the **Assignees** section on the right side of the issue page, click **Assign yourself** or **Assign someone else** to assign the issue to a developer.

### **To Close an Issue:**

- After the issue is resolved and the PR is merged, go to the issue page and click the **Close Issue** button at the bottom.
