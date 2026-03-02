# Agent Control Diagram Sources

This directory contains Mermaid source files for all diagrams used in the Agent Control documentation.

## How to render

1. Install the Mermaid CLI: `npm install -g @mermaid-js/mermaid-cli`
2. Render each diagram:
   ```bash
   mmdc -i diagram-name.mmd -o /static/images/diagram-name.webp -w 1200 -H 600 -b transparent
   ```
3. Alternatively, use the [Mermaid Live Editor](https://mermaid.live) and export as PNG, then convert to WebP.

## Diagrams index

| File | Output image | Used in |
|------|-------------|---------|
| `new-relic-control-components.mmd` | `/images/new-relic-control-components.webp` | `getting-started.mdx` |
| `new-relic-control-data-flow.mmd` | `/images/new-relic-control-data-flow.webp` | `getting-started.mdx` |
| `agent-control-how-it-works.mmd` | `/images/agent-control-how-it-works.webp` | `overview.mdx` |
| `agent-control-lifecycle.mmd` | `/images/agent-control-lifecycle.webp` | `overview.mdx` |
| `agent-control-config-flow.mmd` | `/images/agent-control-config-flow.webp` | `overview.mdx` |
| `agent-control-k8s-architecture.mmd` | `/images/agent-control-k8s-architecture.webp` | `overview.mdx` |
| `agent-control-host-architecture.mmd` | `/images/agent-control-host-architecture.webp` | `overview.mdx` |

## Style guidelines

- Background: transparent or white (`#ffffff`)
- Primary color (New Relic teal): `#005F8E`
- Success / GA color: `#1dcf8b`
- Warning color: `#f0b400`
- Font: use Mermaid default (Inter or system sans-serif)
- Width: 1200px minimum for retina displays
