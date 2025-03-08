## Step 1: Open Cursor and Start a New Project

- [x] Launch Cursor on your system. ✅ 2025-03-08
- [x] Open an empty project to prepare for MCP setup. ✅ 2025-03-08

## Step 2: Access Cursor Settings

- [x] Click on the top-left menu. ✅ 2025-03-08
- [x] Navigate to Cursor Settings. ✅ 2025-03-08
- [x] Locate the MCP (Model Context Protocol) section. ✅ 2025-03-08

## Step 3: Add MCP Servers to Cursor

### Option 1: GitHub MCP Server Setup

- [x] Open Github.com and log into your account. ✅ 2025-03-08
- [x] Click on your profile icon (top right) and select **Settings**. ✅ 2025-03-08
- [x] Scroll down to **Developer Settings** and click on **Personal Access Tokens**. ✅ 2025-03-08
- [x] Click on **Generate new token** (Fine-grained access token recommended). ✅ 2025-03-08
- [x] Name your token **Cursor MCP** and set an expiration date. ✅ 2025-03-08
- [x] Select the Resource Owner to your profile where you want to create repositories in. ✅ 2025-03-08
- [x] Select **All Repositories** for broad access or specify individual repositories. ✅ 2025-03-08
Grant the following permissions:
  - [x] **Administration: Read & Write** ✅ 2025-03-08
  - [x] **Commit Statuses: Read & Write** ✅ 2025-03-*08*
  - [x] **Contents: Read & Write** ✅ 2025-03-08
  - [x] **Issues: Read & Write** ✅ 2025-03-08
- [x] Click **Generate Token** and copy it immediately (it will not be shown again). ✅ 2025-03-08
- [x] Open Smithery.ai and login with you GitHub account. Smithery will allow you to access, manage, and deploy MCP servers. ✅ 2025-03-08
- [x] Select the Github MCP Server. ✅ 2025-03-08
- [x] Insert the Github generated token under the Cursor tab, click **Generate Command** and copy the command. ✅ 2025-03-08
- [x] Go back to the **Cursor Settings > MCP**, click **Add new MCP**. ✅ 2025-03-08
- [x] Enter a name (**GitHub MCP**) and paste the generated command. Add in front of the generated command *cmd /c*. The final command should look like this: *cmd /c npx -y @smithery*. ✅ 2025-03-08
- [x] Once the setup completes, your GitHub MCP is ready to use. ✅ 2025-03-08
### Option 2: Installing Browser Tools MCP

- [ ] Visit the repository page for **Browser Tools MCP** and copy the **Git Clone command**.
- [ ] Open **Cursor Agent** and enter:
  ```sh
  Run this terminal command: <Git Clone Command>
  ```
- [ ] Once cloned, locate the extension folder and open **Manage Extensions** in your browser.
- [ ] Enable **Developer Mode**.
- [ ] Click **Load Unpacked** and select the Chrome Extension folder from the cloned repo.
- [ ] Return to **Cursor Settings > MCP** and click **Add new MCP**.
- [ ] Give it a name (**Browser Tools MCP**) and enter the setup command.
- [ ] Click **Add** and ensure the MCP turns green (indicating a successful setup).
- [ ] Start the Browser Tools MCP server by running the given command in **Cursor Agent**.

## Step 4: Enable YOLO Mode (Optional, but Recommended)

- [ ] Go to **Cursor Settings > Features**.
- [ ] Scroll down to **Enable YOLO Mode** and turn it on.
- [ ] This allows Cursor to execute MCP commands without needing manual approvals.

## Step 5: Testing MCP Servers in Cursor

### Testing GitHub MCP

- [ ] Open Cursor and start a new agent chat.
- [ ] Enter: `Create a new GitHub repository named 'TestRepo'.`
- [ ] Verify that the repository was successfully created by checking GitHub.

### Testing Browser Tools MCP

- [ ] Open a website in your browser.
- [ ] Press `F12` to open **DevTools**.
- [ ] Click the **Browser Tools MCP** tab.
- [ ] Run: `Capture Screenshot` or `Get Console Logs` to verify MCP functionality.

## Conclusion

- [ ] Congratulations! You’ve successfully installed and configured MCP servers in Cursor.
- [ ] These tools can significantly enhance your development workflow by automating GitHub interactions and improving browser debugging.

## Next Steps for Your YouTube Video

- [ ] Show **Cursor installation** and how to access MCP settings.
- [ ] Walk through the **GitHub MCP setup**, highlighting permissions and security best practices.
- [ ] Demonstrate **Browser Tools MCP installation** and debugging a webpage using it.
- [ ] Explain **YOLO mode** and why it’s useful.
- [ ] End with a **real-use case demo** of MCPs in action.

This structured approach will make your video engaging and informative for viewers who want to leverage MCPs efficiently!
