# Prompt Pack: 100 Most Common UI Elements For Vibecoders

## What It Is
A Notion database cataloging 100+ common UI elements with ready-to-use vibecoding prompts for each one. It’s essentially a prompt library specifically designed for building interfaces with AI.

Structure of each entry:

- UI Element name (Button, Text Input, Modal, Chat Message, etc.)

- Category (Navigation, Input, Display, Feedback, Layout, Media, Interactive, Data)

- Description (what the element does)

- Complexity (Simple/Medium/Complex)

- Backend Required (Yes/No)

- Database Required (Yes/No)

- Vibecoding Prompt - This is the gold: detailed, structured prompts covering frontend, backend, and database considerations

### Example from “Text Input Field”:

```
Create a text input field for [email/name/search]. Requirements:
1) Frontend: Style with focus states, borders, proper padding
2) Add real-time validation with error messages
3) Include character counter if max length specified
4) Support placeholder text and labels
5) Implement debouncing for search inputs
6) Backend: Create validation endpoint if needed
7) Sanitize input to prevent XSS attacks
8) Database: Design table column with appropriate varchar length
For best results, read the guide first.
```

The [guide](https://karozieminski.substack.com/p/vibecoding-tips-the-ultimate-collection) teaches you how to vibecode (validation, Git, debugging, etc.).

This database gives you what to say when building specific UI elements.

## Why This is Valuable
Prevents prompt amnesia - Each element has thought-through requirements

Full-stack thinking - Covers frontend, backend, and database together

Accessibility baked in - ARIA labels, keyboard navigation mentioned

Security conscious - XSS prevention, validation, sanitization

Performance hints - Debouncing, indexed search, proper data types

## How To Use It
[👉 Download the database.](https://karozieminski.substack.com/p/prompt-pack-100-most-common-ui-elements-for-vibecoding)
