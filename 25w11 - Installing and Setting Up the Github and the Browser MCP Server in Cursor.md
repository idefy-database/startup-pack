## Step 1: Open Cursor and Start a New Project

- [ ] Launch Cursor on your system.
- [ ] Open an empty project to prepare for MCP setup.
## Step 2: Access Cursor Settings

- [ ] Click on the top-left menu File > Preferences.
- [ ] Navigate to Cursor Settings.
- [ ] Locate the MCP (Model Context Protocol) section.
## Step 3: Add MCP Servers to Cursor
### Option 1: GitHub MCP Server Setup
- [ ] Open Github.com and log into your account.
- [ ] Click on your profile icon (top right) and select **Settings**.
- [ ] Scroll down to **Developer Settings** and click on **Personal Access Tokens**.
- [ ] Click on **Generate new token** (Fine-grained access token recommended).
- [ ] Name your token **Cursor MCP** and set an expiration date.
- [ ] Select the Resource Owner to your profile where you want to create repositories in.
- [ ] Select **All Repositories** for broad access or specify individual repositories.
Grant the following permissions:
  - [ ] **Administration: Read & Write**
  - [ ] **Commit Statuses: Read & Write**
  - [ ] **Contents: Read & Write**
  - [ ] **Issues: Read & Write**
- [ ] Click **Generate Token** and copy it immediately (it will not be shown again).
- [ ] Open Smithery.ai and login with you GitHub account. Smithery will allow you to access, manage, and deploy MCP servers.
- [ ] Select the Github MCP Server.
- [ ] Insert the Github generated token under the Cursor tab, click **Generate Command** and copy the command.
- [ ] Go back to the **Cursor Settings > MCP**, click **Add new MCP**.
- [ ] Enter a name (**GitHub MCP**) and paste the generated command. Only for Windows: add in front of the generated command *cmd /c* if not already present. The final command should look like this: *cmd /c npx -y @smithery*.
- [ ] Once the setup completes, your GitHub MCP is ready to use.
### Option 2: Installing Browser Tools MCP
- [ ] Visit the page for **Browser Tools MCP** [Installation - AgentDesk - BrowserToolsMCP](https://browsertools.agentdesk.ai/installation#installation)
- [ ] Download the extension clicking on the link (In the future probably this step will get easier. For now the extension is not yet approved in the store).
- [ ] Unzip the folder and remember its path 
- [ ] Go to your browser (I tried with both Chrome and Edge) and open **Manage Extensions** in your browser.
- [ ] Enable **Developer Mode** on the left side.
- [ ] Click **Load Unpacked** and select the Chrome Extension folder from the downloaded folder.
- [ ] Go now to your **Cursor Settings > MCP** and click **Add new MCP**.
- [ ] Give it a name (**Browser Tools MCP**) and enter the setup command. For Windows: *cmd /c npx -y @agentdeskai/browser-tools-mcp@1.2.0*
- [ ] Click **Add** and ensure the MCP turns green (indicating a successful setup).
## Step 4: Enable YOLO Mode (Optional, but Recommended)
- [ ] Click on the top-left menu File > Preferences > Cursor Settings.
- [ ] Navigate to Features.
- [ ] Scroll down to **Enable YOLO Mode** and turn it on.
- [ ] This allows Cursor to execute MCP commands without needing manual approvals.
