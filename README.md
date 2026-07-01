Designer ECY1_2 Migration Tool 1.0.0

⚠️ IMPORTANT: COMMUNITY TOOL – NOT AN OFFICIAL DISTECH CONTROLS PRODUCT

This application is a special project developed by the Distech Controls Advanced Support Team and is NOT a sanctioned or official product release by Distech Controls Inc.

Please read DISCLAIMER.txt in full before using this tool.

Designer package inspection, DG5 analysis, BACnet object discovery, and Gen 1 to ECLYPSE migration assistance utility.

Platform: Windows

Technology: PowerShell + WPF

Distribution: Community Tool

________________________________________

⚠️ Important Notice

THIS IS A COMMUNITY TOOL – READ BEFORE USE

This application is:

✅ Freely available for use and redistribution

✅ Designed to inspect Designer project package ZIP files and DG5 content

✅ Assists with Gen 1 to ECLYPSE migration workflows

✅ Supports BACnet object discovery through ECLYPSE REST APIs

✅ Provides offline analysis of DG5 files and project packages

✅ Supported by Advanced Support at their discretion, primarily for Distech:

• System Integrators (SIs)
• Authorized Distributors
• OEM Partners
• Internal engineering and support teams

❌ NOT an official Distech Controls product

❌ NOT covered by Distech Controls warranties

❌ NOT covered by Distech Controls support agreements

❌ NOT subject to standard Distech Controls QA or release procedures

📋 READ THE FULL DISCLAIMER – Contains important legal information regarding warranty, liability, and support.

By using this tool, you acknowledge and accept these terms.

________________________________________

🎯 What Is This?

Designer ECY1_2 Migration Tool 1.0.0 is a migration and analysis utility designed to assist with the transition of Designer Gen 1 facility references to ECLYPSE BACnet object paths.

The tool enables users to:

• Analyze Designer project package ZIP files
• Locate and inspect embedded DG5 files
• Extract referenced data point paths from JSON content
• Discover BACnet objects directly from an ECLYPSE controller
• Automatically map legacy paths to BACnet object references
• Generate updated DG5 files for migration workflows

Built for:

• System Integrators
• Advanced Support Engineers
• Field Service Technicians
• Application Engineers
• QA and Engineering Teams

Developed by:

Distech Controls Advanced Support Team (Community Project)

Primary Use Cases:

• Gen 1 to ECLYPSE migration assistance
• Designer package validation
• DG5 path analysis
• BACnet object discovery
• Offline JSON inspection
• Data point replacement and remediation
• Troubleshooting migration issues before deployment

________________________________________

✨ Key Features

📦 Designer Package Analysis

• Open Designer package ZIP files
• Scan ZIP archives without extracting everything
• Locate and list all embedded DG5 files
• Display file names, package paths, and sizes
• Filter results by project name

________________________________________

📄 DG5 File Inspection

• Preview DG5 files directly from ZIP archives
• No manual extraction required
• Read raw JSON content within the application
• Word-wrap support for large configuration files
• Fast navigation between project files

________________________________________

🔍 Data Point Extraction Engine

Automatically parses DG5 JSON content and extracts:

• /Data/... references
• Point names
• Full object paths

Built-in Data Point Grid includes:

• Point Index
• Point Name
• Original Path
• Replacement Path

Allows technicians to quickly identify migration targets.

________________________________________

🌐 Controller Connectivity Testing

Provides built-in controller validation before migration:

• HTTPS connectivity testing
• Basic Authentication support
• Controller REST API validation
• Detailed diagnostic logging
• TLS 1.2 support

Connection tests provide immediate feedback regarding:

• Reachability
• Authentication issues
• REST API availability
• Network-related failures

________________________________________

🏢 BACnet Object Discovery

Automatically queries supported local BACnet collections:

• Analog Inputs
• Analog Outputs
• Analog Values
• Binary Inputs
• Binary Outputs
• Binary Values

Features include:

• Parallel object discovery
• Collection status tracking
• Detailed discovery logging
• Discovered object viewer
• Controller-side object enumeration

________________________________________

🤖 Automatic Replacement Matching

The migration engine automatically matches:

Source Data Point Name

→

Discovered BACnet Object Name

Using:

• Exact matching
• Levenshtein distance calculations
• Fuzzy matching logic
• Configurable distance thresholds

Results are written directly into the Replacement column for review.

________________________________________

💾 Replacement & Save Engine

After review, users can:

• Apply path replacements
• Skip unmatched entries
• Ignore blank replacements
• Export modified DG5 files

The original package remains unchanged.

New DG5 files are saved separately for validation and deployment.

________________________________________

📋 Discovered Objects Viewer

Displays all discovered BACnet objects including:

• Object Name
• BACnet Path

Useful for:

• Validation
• Troubleshooting
• Manual mapping
• Migration verification

________________________________________

🪵 Comprehensive Diagnostic Logging

Built-in logging includes:

• INFO messages
• WARNING messages
• ERROR messages
• DEBUG messages

Provides visibility into:

• ZIP processing
• DG5 parsing
• Connection testing
• BACnet discovery
• Auto matching
• Save operations

Timestamped logging helps support troubleshooting and escalation activities.

________________________________________

🖥️ Modern WPF User Interface

Features include:

• Dark theme interface
• Project filtering
• Split-panel preview layout
• Resizable preview pane
• Context menus
• DataGrid sorting and filtering
• Real-time status indicators
• Responsive WPF design

Built for support engineers working with large packages and large datasets.

________________________________________

🔄 Versioning

Semantic Versioning (MAJOR.MINOR.PATCH)

• MAJOR – Breaking changes or new migration workflows
• MINOR – New features and enhancements
• PATCH – Bug fixes and stability improvements

Current Version: v1.0.0

________________________________________

🧪 What This Tool Is Not

Designer ECY1_2 Migration Tool 1.0.0 is NOT:

❌ A controller commissioning tool

❌ A live BACnet management system

❌ A firmware update utility

❌ A controller configuration editor

❌ A replacement for official Distech Controls software

❌ A production deployment platform

❌ An automatic migration solution requiring no engineering review

Migration results should always be validated by qualified personnel before deployment.

________________________________________

🧰 Typical Workflows

1️⃣ Inspect a Package

• Open ZIP
• Scan contents
• Locate DG5 files
• Review project organization

2️⃣ Analyze Data Points

• Open DG5 file
• Switch to Data Points view
• Review extracted paths
• Identify migration candidates

3️⃣ Validate Controller Connectivity

• Enter controller credentials
• Test connection
• Verify REST API availability
• Review diagnostics

4️⃣ Auto-Migrate References

• Discover BACnet objects
• Auto-fill replacements
• Review mappings
• Correct invalid matches

5️⃣ Generate Updated Files

• Apply replacements
• Save modified DG5
• Validate results
• Deploy through normal project workflows

________________________________________

🔐 Security Notes

• HTTPS communications supported
• Basic Authentication supported
• No cloud connectivity
• No telemetry
• No external data collection

⚠️ Important

The tool includes SSL certificate validation bypass for convenience when connecting to controllers using self-signed certificates.

Only use this tool on trusted networks and approved support environments.

Controller credentials and project data should be handled according to your organization's security policies.

________________________________________

📥 Installation & Usage

• Runs on Windows
• Requires PowerShell 5.1 or later
• Requires .NET Framework 4.5 or later
• No installer required
• Script-based deployment

Recommended:

• Maintain a backup of original ZIP packages
• Save modified DG5 files separately
• Validate migration results before deployment

________________________________________

📚 Documentation

• README.md – This document
• DISCLAIMER.txt – Legal disclaimer and limitation of liability
• User Guide – Full operating guide
• Quick Start Guide – Rapid deployment instructions
• Inline help and status messages within the application

________________________________________

🤝 Support & Community

This is a community tool.

Support is provided at the discretion of the Distech Controls Advanced Support Team and may include:

• Best effort assistance
• Bug identification
• Feature recommendations
• Community-driven improvements

There are:

• ❌ No guaranteed response times
• ❌ No SLAs
• ❌ No warranty obligations

________________________________________

📊 Project Information

• Application Name: Designer ECY1_2 Migration Tool
• Current Version: v1.0.0
• Release Type: Community Tool
• Status: Stable
• Platform: Windows
• Language: PowerShell (WPF UI)

________________________________________

🏆 Acknowledgments

This tool relies on:

• .NET Framework
• Windows Presentation Foundation (WPF)
• PowerShell
• Native ZIP processing libraries
• Native JSON processing libraries
• ECLYPSE REST APIs
• BACnet object discovery services

No proprietary Distech Controls tooling is required.

________________________________________

⚠️ Final Reminder

This is a community utility.

Please read DISCLAIMER.txt before use.

Migration results should always be reviewed and validated prior to production deployment.

Built with ⚡ by the Distech Controls Advanced Support Team

