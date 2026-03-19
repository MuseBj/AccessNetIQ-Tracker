# AccessNetIQ Tracker

This repository is used to track issues, bug reports, and feature requests for **AccessNetIQ** - a demonstration platform for ISP network management and automated customer service solutions.

## What is AccessNetIQ?

AccessNetIQ is a dual-interface platform that includes:

- **Customer Management System (CMS):** A unified dashboard featuring omni-search (IP, MAC, Serial, Phone, Name, Address), real-time signal strength graphs, bandwidth utilization charts, and plain-English status indicators.
- **AI-Powered Virtual IVR Simulator:** An ElevenLabs-powered voice system with context-aware routing that adapts messaging based on account status and system conditions.

For more details about the product capabilities, see the [product overview](#product-overview) below.

## How to Submit Issues & Feature Requests

### Bug Reports

Found something broken? Please include:

- Clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots or error messages (if applicable)
- Environment details (browser, OS, etc.)

### Feature Requests

Have an idea to improve AccessNetIQ? We welcome suggestions! Please include:

- Clear description of the proposed feature
- The problem or need it addresses
- Any relevant use cases or examples
- Priority level (nice-to-have vs. critical)

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
