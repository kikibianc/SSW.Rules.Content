---
seoDescription: Learn how to effectively highlight and distinguish important keywords in your documentation to ensure clarity and prevent misinterpretation.
type: rule
archivedreason: 
title: Do you distinguish keywords from surrounding content?
guid: 9e3cbde7-b8d0-4281-a916-bb224d5c72f4
uri: distinguish-keywords-from-content
created: 2016-03-22T04:57:28.0000000Z
authors:
- title: Adam Cogan
  url: https://ssw.com.au/people/adam-cogan
- title: Jayden Alchin
  url: https://www.ssw.com.au/people/jayden-alchin
- title: Tiago Araujo
  url: https://www.ssw.com.au/people/tiago-araujo
related:
- use-correct-symbols-when-documenting-instructions
- do-you-make-numbers-more-readable
- awesome-documentation
- style-quotations
- formatting-ui-elements
- indent
redirects:
- do-you-highlight-actions-correctly-in-your-document
- highlight-items-in-your-document

---

We've all missed a piece of a message and found out later that we'd got it wrong. This can lead to miscommunication, mistakes, and lost time. Even worse, when finding out later that someone has misread something, there can be a lot of work to fix! But, there are ways to prevent this. Do these things to always make your writing clear:

<!--endintro-->

An important case - don't let anybody skim over negation and misinterpret your message:

::: greybox
"We found that moving CodeAuditor's scan engine (docker image) to be hosted on GitHub Action is not feasible."
:::

::: bad
Figure: Bad example - it's possible to miss the word 'not'
:::

::: greybox
"We found that moving CodeAuditor's scan engine (docker image) to be hosted on GitHub Action is **not** feasible."
:::

::: good
Figure: Good example - The bolding draws attention to the main idea, which is 'No'!
:::

When highlighting items (file names, user commands etc.) be sure to:

1. Distinguish the items from the rest of the surrounding text; and
2. Be consistent

::: info
**Warning:** Never underline the text if it isn't a link, as per [Do you use underlines only on links?](/do-you-use-underlines-only-on-links)
:::

Use the following rules to highlight items in your document:

| Style | Use this style for | Example |
| --- | --- | --- |
| **Bold text**  | Menus, commands, dialog box options, file names and paths | To access the application, click  **Start \| Programs \| Accessories \| System Tools \| Disk Defragmenter**  |
| **Initial Capitals + Bold**  | File paths and file names |  Now open  **C:\My Documents\Invoice.doc.**  |
| Quotes |  Exact reference, buttons, labels | Click "Submit" to complete the form. / Make sure your calendar is set to "Out of Office". |
| Quotes |  Quotes from others  | Einstein said it best: "If you can't explain it simply, you don't understand it well enough." |
| Different colour styling | Web UI - Important words on headings | Want to build an <span style="color:#cc4141">Angular</span> application? |
| UPPER CASE | Code keywords and database elements | Use the INNER JOIN clause in SQL Server to join one table to another. |
| Monospace (i.e. Courier New font) | Code samples, error messages | You will see the following error: `error opening database: database is currently in use.` |

::: info
**Note:** If you're quoting longer sentences, such as when replying in an email, it's best to [break the line and use clear visual indicators](/style-quotations) - like indentation, quotation marks, or a different text styles - so the quoted content is clearly separated from your own content.
:::
