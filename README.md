![Screenshot (616)](https://github.com/user-attachments/assets/23fd50fb-fcb9-467e-b216-8cb57f4719cc)![Screenshot (563)](https://github.com/user-attachments/assets/9ff16ab3-1658-4fb5-af08-088257c056a8)# Atlassian_Jira_finalproject_assignment

# Agile with Atlassian Jira - Final Project

This repository documents the steps and requirements for setting up an Agile project using a company-managed Kanban board in Jira, based on the provided guidelines.

---

## **Project Overview**

This project involves creating and managing a company-managed Kanban board in Jira. The board will evolve through different versions, incorporating various Agile practices.

### **Versions and Requirements**

| Version | Requirement Summary                                   | Verification Steps                                       |
|---------|-------------------------------------------------------|---------------------------------------------------------|
| **A**   | Create a Kanban project with columns: Backlog, Selected for Development, In Progress, Done | Verify that issues move across columns correctly        |
| **B**   | Set WIP limit for "In Progress" to 3 items            | Verify that exceeding the limit turns the column red    |
| **C**   | Create a backlog separate from the board              | Verify backlog is hidden when viewing the board         |
| **D**   | Split "In Progress" into Analyze, Build, and Verify columns. Set WIP limit of 3 for "Build" | Ensure issues can flow through these columns as expected|
| **E**   | Add a swimlane named Expedite for high-priority issues | Verify high-priority issues appear in the swimlane      |
| **F**   | Create an epic named Initial Release and add issues   | Ensure epic label is visible on board issues            |
| **G**   | Create a filter to display open issues from Initial Release | Ensure only non-done issues of the epic are displayed   |
| **H**   | Move all issues to Done and release version 0.1       | Verify that no released issues appear on the board      |
| **I**   | Explore additional Jira features                      | Document any explored features                          |

---

## **Procedure**

1. **Setting up the Kanban Board**  
   Create a company-managed Kanban board named `project final` in Jira. Ensure columns are named as required.

2. **Implementing Requirements**  
   Implement each board version sequentially, following the guidelines and references provided.

3. **Verification**  
   After implementing each version, verify that the board behaves as expected.

---

## A: Steps to Create a Company-Managed Kanban Project

### Create a New Kanban Project:
1. Log in to your Jira account.
   ![Screenshot (563)](https://github.com/user-attachments/assets/b065e5cd-28f9-4523-96ab-14c56a3b1688)
2. Click on **Projects** in the top navigation bar and select **Create project**.
   ![Screenshot (564)](https://github.com/user-attachments/assets/78ba3ba3-4dde-445a-8d7c-fc400595ce8c)
3. Choose **Kanban** as the project type in `Software Development` tab.
   ![Screenshot (565)](https://github.com/user-attachments/assets/92bc3386-efde-48ca-91a7-585e2665dede)
   ![Screenshot (566)](https://github.com/user-attachments/assets/a6cfc5f1-da90-4924-a102-e5cf04d96756)
   ![Screenshot (567)](https://github.com/user-attachments/assets/4a334411-6f85-4c01-8c85-043efa57cfb2)
4. Select **Company-managed** when prompted for the project management type.
   ![Screenshot (568)](https://github.com/user-attachments/assets/226b9ae7-104f-445b-9544-353dcf2490ce)
5. Enter the project name as **project final**.
6. Click **Create** to finish setting up the project.
   ![Screenshot (569)](https://github.com/user-attachments/assets/07e761f1-da38-4580-b0f9-b0c7b78ae24f)

### Configure Columns:
1. Once the project is created, go to the board view.
   ![Screenshot (570)](https://github.com/user-attachments/assets/f0476cba-0486-47a4-ac98-201a968d04ff)
3. Verify the name of columns as follows:\n
   - Backlog
   - Selected for Development
   - In Progress
   - Done

### Verification Steps:
1. To verify create issues in backlog i.e. `add item 1`, `add item 2`, `remove item 1` etc and you can see their status by double-clicking, status can be viewed as: **Backlog**, **Selected for Development**, **In Progress**, and **Done**.
   ![Screenshot (571)](https://github.com/user-attachments/assets/0f32ef3b-c241-4cc6-a009-55975ab06d82)
   ![Screenshot (572)](https://github.com/user-attachments/assets/5fd20add-bc2a-4da0-b756-430028822da0)
   ![Screenshot (573)](https://github.com/user-attachments/assets/c92a7f70-7706-44ec-903d-bc9c60136daf)

2. Test moving issues across the columns to ensure smooth transitions.
   ![Screenshot (574)](https://github.com/user-attachments/assets/c97a173a-bdb0-46e9-9f06-49301daaec7c)
   ![Screenshot (574)](https://github.com/user-attachments/assets/c04220f7-ad9c-4dc7-aa91-b32c718a5ff5)
   ![Screenshot (576)](https://github.com/user-attachments/assets/2cc40fdb-16f7-438d-b3ed-0a6c0b70695f)
   ![Screenshot (577)](https://github.com/user-attachments/assets/47c7120b-16f4-4fa0-a727-445e823c8126)
   ![Screenshot (578)](https://github.com/user-attachments/assets/632afb26-8d9e-4f7d-8cde-c6ee40db52e7)
   ![Screenshot (579)](https://github.com/user-attachments/assets/8dd6df03-daab-448b-8701-ad0addbb50d1)
   
## B: Steps for Setting WIP Limit in the "In Progress" Column of a Kanban Board

### Navigate to your Kanban board:
1. Open your Jira project where you want to set the WIP limit.
2. Go to the Kanban board by selecting it from the sidebar.

### Set WIP Limit:
1. Click on the three-dot menu in the upper-right corner of the `in Progress` column.
   ![Screenshot (580)](https://github.com/user-attachments/assets/8ebbf6ba-da5c-43c0-990d-19158462840c)
2. Select the limit as desired in my case i chose the max limit to be `3`.
   ![Screenshot (581)](https://github.com/user-attachments/assets/fec9a765-c02f-414b-bd3e-0029c420781f)

### Verify WIP Limit:
1. Return to your Kanban board.
2. Create more items.
   ![Screenshot (582)](https://github.com/user-attachments/assets/52098c5f-9953-42e1-8766-3cb290ade394)
3. Try moving items into the "In Progress" column. If the number of items exceeds 3, you should see a visual indicator (e.g., the column changes color or a warning appears).
   ![Screenshot (583)](https://github.com/user-attachments/assets/fcc34be4-9e42-439f-b75d-9e380e8e817a)

## C: Steps for Hiding Backlog View in a Kanban Project

### Navigate to your Kanban project:
1. Open your Jira project where you want to create a backlog.

### Access Board Settings:
1. Click on the three-dot menu in the upper-right corner of the board.
   ![Screenshot (584)](https://github.com/user-attachments/assets/2ec07c40-795c-43e8-9e7b-fdc4a76b1d5e)
2. Select **Board settings**.
   ![Screenshot (585)](https://github.com/user-attachments/assets/e5b2366a-7a8c-4e20-b6bf-ca3136ff6c70)

### Enable Separate Backlog:
1. Go to the **Columns** tab.
   ![Screenshot (586)](https://github.com/user-attachments/assets/88ec71f0-2f97-4ef4-9dab-0bf396faef7c)
2. You can move any item to the Kanban backlog to enable the separate view or you should see an option to enable the Kanban backlog. Toggle this option to **ON**.
   ![Screenshot (587)](https://github.com/user-attachments/assets/3e501f21-bcfa-4abf-a3e7-d273c56d4ab9)

### Configure Columns:
1. Once the backlog is enabled, you'll see a new section labeled **Backlog** above the board columns.
2. Move issues that are not ready for development into the backlog by dragging them into the **Backlog** section.

### Verify Backlog View:
1. Go back to the project view, and you should now see a separate **Backlog** tab next to your Kanban board tab.
   ![Screenshot (588)](https://github.com/user-attachments/assets/06aef4a6-9f7c-4255-8d80-cccbc3669677)
3. Issues in the backlog will not be visible on the main board until they are moved to the "Selected for Development" or equivalent column.

### Notes

Backlog visibility:
- Once enabled, the backlog becomes a distinct view from the main board, allowing your team to manage upcoming tasks without cluttering the active board.


## D: Steps to Split the In Progress Column

### Go to Board Settings:
1. Open your Kanban board.
2. Click on the three-dot menu in the upper-right corner and select **Board settings**.

### Open the Columns Tab:
1. In the **Columns** section, you will see all the existing columns of your board.
   ![Screenshot (616)](https://github.com/user-attachments/assets/64940c36-7b48-470e-8ceb-85cbcc6a9f4a)
   
### Add New Columns:
1. Click **Add column** and create the following columns with category `In Progress` if you have not created new statuses:
   - Analyze
   - Build
   - Verify
   ![Screenshot (617)](https://github.com/user-attachments/assets/941bc361-8b02-4b35-801e-13e128292364)
   ![Screenshot (618)](https://github.com/user-attachments/assets/16cd6289-6072-4b75-a542-f8addfdb95d2)
2. If you want you can delete the `In Progress` column in this process the status for earlier created column with `In Progress` status get their own status with default names from their respective column names.
   ![Screenshot (619)](https://github.com/user-attachments/assets/cdc5212c-d3c1-431a-a929-7f70afdf315f)
   ![Screenshot (620)](https://github.com/user-attachments/assets/8616fb29-c132-4059-ab73-2fc7c42ed774)
   ![Screenshot (621)](https://github.com/user-attachments/assets/2de434ac-0067-4d99-8d0d-0e309784e2e9)

### *Create Statuses in Workflow (if not deleted the In Progress Column):
1. If your workflow already has statuses related to these columns under `In Progress` category, drag them from the existing **In Progress** column to the new ones.
2. If the statuses do not exist go to project settings and open the workflow tab:
   ![Screenshot (592)](https://github.com/user-attachments/assets/4adeb47b-8076-45d7-b6aa-a7b9e3348fcf)
   ![Screenshot (595)](https://github.com/user-attachments/assets/3896560e-3f34-430a-9165-871770f49d07)
3. Now click on `edit workflow`
   
   - Click **Add status** when creating a column.
   - Define new statuses (**Analyze**, **Build**, **Verify**) for each column under `In Progress` category.
   - Ensure that your workflow is updated accordingly.
   - Tick Accept all transitions.
   ![Screenshot (596)](https://github.com/user-attachments/assets/4dd90983-f377-4e17-bcc2-19eb66eae0f8)
   ![Screenshot (597)](https://github.com/user-attachments/assets/148f0c5e-52f1-4e09-a217-19501a0f4b40)
4. Publish the workflow draft to save the changes done.
   ![Screenshot (602)](https://github.com/user-attachments/assets/b2bd9665-5f27-4140-a074-fea5235d1c11)

### *Move Statuses into New Columns (if not deleted the In Progress Column)
1. After creating new statuses go back to board settings.
2. Click the cloumn tab, you can now see there are unmapped statuses which can be assigned to the any column.
3. Assign the statuses to their respective columns, by dragging and dropping.
![Screenshot (603)](https://github.com/user-attachments/assets/30243d89-ca92-4aa9-888d-cd68d5630f29)

### Steps to Set WIP Limit for Build Column

### In the Columns Tab:
1. Find the newly created **Build** column.
2. Click on the number next to **Max issues (WIP limit)** under the **Build** column.
3. Set the value to **3** and press `Enter`.
   ![Screenshot (622)](https://github.com/user-attachments/assets/66f0a233-9194-4b06-857b-268b229e1d04)

### Verify WIP Limit:
1. Go back to your board and try adding more than 3 issues in the **Build** column.
2. If the limit is exceeded, the column will turn red, indicating that the WIP limit has been breached.
   ![Screenshot (623)](https://github.com/user-attachments/assets/4420be15-33b5-420a-b3ac-931b2afb5675)

### Verification Steps
1. Ensure that issues can move smoothly between **Analyze**, **Build**, and **Verify** columns.
2. Check that when more than 3 issues are moved into the **Build** column, a WIP limit warning is displayed.


## **References**

- Atlassian documentation: [Jira Software Documentation](https://support.atlassian.com/jira-software-cloud/)
- Week-wise lab exercises as referenced in the project.

---

## **Explored Jira Features**

Describe any additional features you explored during version **I**.
