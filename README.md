# Design Experiments

## Common Design

### AI Chat (Claude, ChatGPT)

- A 2-column grid
  - One column is the sidebar: scrollable, fix account div at the bottom, hideable
  - One column is the main content: heading, chat div, filter selection bar

## Experiments

## Design Vocab

To improve my prompting skill, I document some useful design vocab and how I struggled to describe it at first. To prompt better design, we need to improve our vocabulary.

| Vocab | Original Description | Explanation |
|---|---|---|
| `collapsible` | "How to make the effect where when I click the sidebar icon, the sidebar is hidden?", "But then the sidebar should still be visible with smaller width and the icon is still visible so that i can still open it"| A collapsible sidebar can shrink in width (or size) but stays visible with some icons or contents |
| `text wrapping` | "The problem with this approach is that I can still see @layout/ai-chat/index.html:24-25 collapse in width (the letters collapsing in vertically) when hiding and expanding in width (the letters go from vertically to horizontally because there's enough space) but it should not be the case, they should just appear" | The phenomenon I saw is called text wrapping, which happens when the program automatically breaks lines of text to fit within a defined area |