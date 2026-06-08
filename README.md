# wcag-in-practice-skill

A Claude skill that brings WCAG accessibility knowledge into any Claude project.

Built by [Jainish Soni](https://wcaginpractice.com) — CPACC Certified.

---

## What this is

Claude skills add domain-specific knowledge to Claude Projects. When you add this skill to a project, Claude gains accessibility-aware context for code review, component guidance, and WCAG questions — without you needing to paste documentation into every conversation.

This skill covers WCAG 2.1 and 2.2 AA across nine reference areas:

- Semantic structure (headings, landmarks, skip links)
- Keyboard and focus behavior
- Color contrast and visual design
- Accessible forms
- Modals, toasts, and overlays
- Navigation patterns (menus, tabs, accordions)
- Interactive controls (carousels, drag/drop, progress)
- ARIA roles, labels, and live regions
- Motion and media (prefers-reduced-motion, captions)

---

## How to install

1. Download `wcag-in-practice-public.skill` from the [Releases](../../releases) page
2. Open [Claude.ai](https://claude.ai) and go to a Project
3. Click **Project knowledge** and upload the `.skill` file
4. Start a new conversation — Claude will now apply WCAG context automatically

The skill works in any Claude Project. You don't need wcag-kit or WCAG Lens installed to use it, though the three tools work well together.

---

## The full ecosystem

| Tool | What it does | Where to get it |
|---|---|---|
| **This skill** | WCAG knowledge inside Claude Projects | Right here |
| **wcag-kit** | MCP server — WCAG knowledge inside Cursor, Claude Desktop, any MCP editor | [npm](https://www.npmjs.com/package/wcag-kit) |
| **WCAG Lens** | VS Code extension — real-time red underlines as you type | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=jainishsoni.wcag-lens) |
| **wcaginpractice.com** | 27+ interactive broken-vs-fixed patterns and a free page checker | [wcaginpractice.com](https://wcaginpractice.com) |

**The workflow:** Lens flags it in your editor. wcag-kit explains it in your AI assistant. The playground shows it working correctly.

---

## What you can ask Claude after installing

- "Review this form component for accessibility issues"
- "My modal doesn't trap focus — how do I fix it?"
- "What ARIA attributes does a tab panel need?"
- "Does this color combination pass WCAG contrast?"
- "Walk me through keyboard navigation for a dropdown"
- "What's the difference between aria-label and aria-labelledby?"

---

## Releases

Each release contains:
- `wcag-in-practice-public.skill` — the installable skill file
- Changelog notes for what changed

See [Releases](../../releases) for all versions.

---

## Contributing

Found a pattern that should be covered or have a suggestion?

Open an issue describing the gap, or submit pattern suggestions at
[wcaginpractice.com/contribute](https://wcaginpractice.com/contribute).

---

## License

MIT. Free to use, share, and build on.

---

Built by [Jainish Soni](https://wcaginpractice.com) · CPACC Certified · Toronto, Canada
