# AccessNetIQ Tracker

This repository is used to track issues, bug reports, and feature requests for **AccessNetIQ** - a demonstration platform for ISP network management and automated customer service solutions.

## What is AccessNetIQ?

AccessNetIQ is a dual-interface platform that includes:

- **Customer Management System (CMS):** A unified dashboard featuring omni-search (IP, MAC, Serial, Phone, Name, Address), real-time signal strength graphs, bandwidth utilization charts, and plain-English status indicators.
- **AI-Powered Virtual IVR Simulator:** An ElevenLabs-powered voice system with context-aware routing that adapts messaging based on account status and system conditions.

For more details about the product capabilities, see the [product overview](#product-overview) below.

## How to Submit Issues & Feature Requests

This project uses **GitHub Issues** as its issue tracking system. All bug reports, feature requests, and tasks are managed through the repository's Issues tab on GitHub.

### Accessing the Issues Page

1. Go to the repository on GitHub: `https://github.com/sst/opencode`
2. Click the **Issues** tab near the top of the page
3. Click the **New issue** button (green button on the right side)

### Creating a New Issue

When creating an issue, you'll see available issue templates. Select the appropriate template:

#### For Bug Reports
Select the **Bug Report** template. You'll be asked to provide:

- [ ] **Issue Title:** A clear, concise description of the problem (e.g., "Login button not responding on dashboard page")
- [ ] **Select a label:** Choose `bug` from the labels section on the right sidebar
- [ ] **Steps to reproduce:** Numbered list of actions that led to the bug
- [ ] **Expected behavior:** What should have happened
- [ ] **Actual behavior:** What actually happened
- [ ] **Screenshots:** Visual evidence of the issue (see screenshot instructions below)
- [ ] **Environment:** Browser, OS, and any relevant system details

#### For Feature Requests
Select the **Feature Request** template. You'll be asked to provide:

- [ ] **Issue Title:** A clear description of the proposed feature (e.g., "Add dark mode support to dashboard")
- [ ] **Select a label:** Choose `enhancement` from the labels section on the right sidebar
- [ ] **Problem it solves:** Why this feature would be valuable
- [ ] **Proposed solution:** Your idea for how to implement it
- [ ] **Use cases:** Specific scenarios where this would be useful

### How to Take and Attach Screenshots

#### Taking a Screenshot on Windows

1. **Quick Screenshot (Full Screen):**
   - Press `Win + Shift + S` to open the snipping toolbar
   - Your screen will dim and you can click and drag to select an area
   - The screenshot is copied to your clipboard

2. **Using Snipping Tool (More Options):**
   - Press `Win` and search for "Snipping Tool"
   - Click **New** to start a fresh snip
   - Choose from: Free-form, Rectangular, Window, or Full-screen
   - Save or copy the image

3. **Screenshot Key (Full Screen Only):**
   - Press `Print Screen` (or `PrtScn`) to capture the entire screen
   - Image is saved to clipboard (paste into an image editor to save)

#### Attaching Screenshots to GitHub Issues

Once you have a screenshot:

1. While creating or editing an issue on GitHub, click inside the issue description box
2. **Drag and drop** the image file directly into the text area, OR
3. Click the **Attach files** icon (paperclip) at the bottom of the text area
4. Select your screenshot from the file picker
5. The image will upload and embed automatically

**Tip:** You can also paste an image from your clipboard directly into the GitHub text area using `Ctrl + V`.

### Defining Issue Types

Use the **Labels** feature on GitHub to categorize your issue:

| Issue Type | GitHub Label | When to Use |
|------------|--------------|-------------|
| **Bug** | `bug` | Something is broken, incorrect, or not working as expected |
| **Enhancement/Feature** | `enhancement` | New functionality or improvement to existing features |
| **Question** | `question` | You need clarification or have inquiries about the project |
| **Task** | (use `enhancement` or create `task`) | Work items that aren't bugs or features (e.g., refactoring, cleanup) |

#### How to Add Labels

1. On the right sidebar of the issue creation page, find the **Labels** section
2. Click the gear icon or the label dropdown
3. Select the appropriate label(s) for your issue
4. You can select multiple labels if applicable

#### Setting Priority

Add priority labels to indicate urgency:

| Priority | Label | Description |
|----------|-------|-------------|
| Critical | `priority-high` | System down, data loss, security issues |
| Important | `priority-medium` | Significant impact on functionality |
| Minor | `priority-low` | Cosmetic issues, nice-to-have improvements |

### Best Practices for Good Issues

- **Search first:** Use the search bar on the Issues page to check if a similar issue already exists
- **One issue per report:** Keep each issue focused on a single problem or feature
- **Be specific:** Include version numbers, browser/OS details, and exact error messages
- **Include reproduction steps:** For bugs, provide clear steps to reproduce the issue
- **Use screenshots liberally:** Visual evidence greatly speeds up troubleshooting
- **Stay responsive:** Answer follow-up questions on your issue to help resolve it faster

### Issue Labels

We use the following labels to categorize issues:

| Label | Description |
|-------|-------------|
| `bug` | Something isn't working as expected |
| `enhancement` | New feature or feature improvement |
| `question` | Further information is requested |
| `priority-high` | Critical issue requiring immediate attention |
| `priority-medium` | Important but not urgent |
| `priority-low` | Minor issue or nice-to-have |
| `documentation` | Related to docs or README updates |
| `cms` | Related to the Customer Management System |
| `ivr` | Related to the Virtual IVR Simulator |
| `status-engine` | Related to the Status Engine or Scenario Toggle |
| `good-first-issue` | Good for newcomers to tackle |

## How to Contribute

1. **Search First:** Check existing issues before creating a new one to avoid duplicates.
2. **Use Issue Templates:** When creating a new issue, select the appropriate template (Bug Report or Feature Request).
3. **Be Specific:** The more detail you provide, the faster we can address it.
4. **Stay Engaged:** Respond to questions or follow-up requests promptly.

## Product Overview

### Core Capabilities

#### 1. Unified Customer Management System (CMS)

- **Omni-Search:** Complex lookup via IP Address, MAC, Serial Numbers, Phone, Name, Address
- **Single Pane of Glass:** Integrates service details, Apogee API billing history, and SNMP device health metrics
- **Visual Analytics:** Real-time signal strength graphs, bandwidth utilization charts, outage history timelines
- **Plain-English Indicators:** Non-technical red/yellow/green status with troubleshooting suggestions

#### 2. AI-Powered Virtual IVR Simulator

- **ElevenLabs Voice Integration:** Natural, dynamic customer interactions
- **Context-Aware Routing:** Dynamic messaging based on account status (billing, technical support, etc.)
- **Status-Dependent Messaging:** Auto-adapted IVR greetings during outages with restoration estimates
- **Web-Based Call Simulator:** Virtual phone interface with DTMF keypad and call flow visualization

#### 3. Real-Time Status Engine & Visual Mapping

- **Instant Scenario Toggling:** Simulate full or partial regional outages
- **Geospatial Intelligence:** Mapping for perimeter visualization, device clusters, and issue radii

### Target Audiences

1. **ISP Sales & Pre-Sales Teams:** Demonstrate technical capabilities and customer service tools to prospective clients
2. **ISPs & Telecomm Operators:** Adopt these technologies to manage networks, reduce support costs, and enhance customer experience

## Repository Structure

```
AccessNetIQ-Tracker/
├── README.md              # This file
├── ISSUES/                # Issue tracking directory
└── ...                    # Additional project files
```

## Questions?

Feel free to open an issue with the `question` label, or reach out to the maintainers.
