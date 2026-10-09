# Bitlight RLN Design Kit & UI Flows

The design reference package for Bitlight RGB Lightning Node (RLN), including the design system, Lightning Service Provider (LSP) user flows, and UI screens.

This package supports design reviews, implementation handoff, and external product presentations.

**Design snapshot:** October 9, 2026  
**Language:** English  
**Theme:** Dark mode

## 1. Package Overview

The package includes editable Figma source files, PNG exports, and PDF documentation.

| Folder / File | Contents | Purpose |
| --- | --- | --- |
| `design-source/` | `Bitlight RLN Design Kit & UI Flows.fig` | Editable source for reviewing design details and making authorized changes |
| `RLN DESIGN KIT/` | Design system PNG exports | Visual foundations, UI components, and documented component states |
| `LSP UI Flows/` | User flow PNG exports | Task sequences, decision points, and screen transitions |
| `LSP UI Screen/` | UI screen PNG exports | Detailed layouts and interface states for LSP workflows |
| PDF documents | Design reference documentation | Document-based viewing and review |
| `README.md` | Package guide | Package contents, viewing instructions, and review guidance |

The folder names above match the delivery package. Refer to the included PDF files for their titles and coverage.

## 2. Recommended Reading Order

1. **Design System — `RLN DESIGN KIT/`:** review the visual foundations and component conventions.
2. **LSP UI Flows — `LSP UI Flows/`:** follow the task sequences, decision branches, and outcomes.
3. **LSP UI Screens — `LSP UI Screen/`:** review the layouts and states within each workflow.

For a quick overview, start with the user flows and key screens, then refer to the design system for component details.

## 3. Design System

The design system defines the visual conventions for the interfaces in this package.

Review each component's documented variants, dimensions, labels, values, trailing icons or actions, helper text, and interaction states. Read the annotations alongside each example.

- Follow the specified typography, spacing, corner radii, colors, and alignment.
- Distinguish placeholders from entered values.
- Keep labels, units, and helper text clearly associated with their fields.
- Refer to the documented focus, error, success, and disabled states where available.
- Treat example values as sample data rather than production settings.

For states that are not documented, confirm the intended behavior with the product team.

## 4. LSP UI Flows

The flow diagrams show how users move through LSP workflows. Follow the arrows and read the branch labels and annotations to understand each path.

| Symbol | Meaning |
| --- | --- |
| Rounded rectangle | Page or screen |
| Diamond | Decision point |
| Solid arrow | Main flow or standard transition |
| Dashed arrow | Exception, retry, or return path, as labeled |
| Rounded capsule | Start or end of a flow |
| Dashed container | Related steps or a functional module |

These diagrams describe the user experience. Refer to the technical documentation for backend protocols, API contracts, transaction lifecycles, and error handling.

## 5. LSP UI Screens

Review each screen alongside its corresponding user flow to understand its context and purpose.

- Use screen names and annotations to identify the task and interface state.
- Maintain the intended information hierarchy, action priority, and component consistency.
- Preserve the distinction between balances, amounts, units, and provider information.
- Consult the product requirements for validation, loading, cancellation, timeouts, and recovery behavior where these are not specified in the designs.

The screens reflect the design snapshot noted above and may differ from subsequent application releases.

## 6. File Formats & Viewing

| Format | Use | Notes |
| --- | --- | --- |
| **FIG** | Inspecting and editing the Figma source | Import into Figma and resolve any missing fonts or library references before editing |
| **PNG** | Viewing individual screens, flows, and design system exports | Static images; component properties and layout settings are available in the Figma source |
| **PDF** | Reading and reviewing the design documentation | Zoom in to inspect labels and annotations |

PNG export scale does not change the intended UI dimensions. A 2× export has twice the pixel width and height of the original frame. For implementation measurements, use the Figma source or explicit design annotations.

The Figma source is in `design-source/`:

`Bitlight RLN Design Kit & UI Flows.fig`

Import the `.fig` file into Figma to access the editable designs. PNG and PDF files can be viewed without Figma. A shared Figma link is not required.

## 7. External Presentations & PR

For external presentations and PR materials, choose representative screens and flows that clearly communicate a user journey. Keep titles and state labels readable, and preserve the original aspect ratios.

Use relevant design system examples to explain the product's visual consistency. Identify the section or screen when sharing an excerpt.

Describe these materials as design references. Ensure any claims about feature availability or production behavior are supported by the corresponding product release.

## 8. Implementation & Feedback

Use these materials alongside the product requirements and technical documentation. If a screen, annotation, or requirement appears inconsistent, confirm the intended behavior with the product team.

When submitting feedback, include:

- The section and screen or component name.
- The relevant interface state or flow step.
- A screenshot or annotated excerpt.
- A clear description of the issue, question, or proposed change.

Submit feedback through the channel used to share this package.

## 9. Attribution & Usage

**Project:** Bitlight Labs — Bitlight RGB Lightning Node.

**Copyright © 2026 Bitlight. All rights reserved.**

These resources may be viewed or used only within the scope expressly authorized by Bitlight. Providing access to these materials does not, in itself, grant permission to reproduce, modify, redistribute, or use them commercially.
