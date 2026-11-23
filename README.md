# LLM Disclosure Levels

> You probably saw something along the lines of "LLM(1)" or "LLM(2)" and thought "What on earth does that mean?"

How we use LLMs can be sorted into categories. When categorized, LLM disclosures work similarly to open source licenses, they communicate the values of the project, how it should be used / contributed to, and its compatibility with other levels / licenses.

LLM(0) represents a purely human made project with increasing numbers corresponding to more autonomous use.

Disclosing and labeling LLM use stands to communicate the following properties: 

1. Communicating Risks and Impacts

Different styles of LLM use bring different risks, whether that be technical, social, or environmental.
For example, may programmers may consider using LLMs for sourcing information (LLM(1)) to be acceptable while more environmentally conscious programmers may reject it.

2. Communicating Intent

The LLM use level hints at the intent of a contribution or the purpose of a project.
For example, a higher LLM use level may hint that a project is a one off tool with little maintenance.
A project using lower levels like LLM(0) or LLM(1) may hint that the project is educational in nature.

---

I will not describe the risks and intent of each level as those are subjective.

The following levels are based on the following [article](`https://every.to/guides/the-eight-levels-of-ai-adoption`).
Moving forward, I will be using the following categories to describe my projects.

> I am not familiar with higher levels of LLM use and the programming world changes frequently, so expect revisions.

## LLM(0) - Human Made

```md
## LLM Disclosure

[LLM(0)](https://github.com/davnotdev/disclosure-levels) - This project is human made.

```

Zero LLM Use.

## LLM(1) - Chatbot

```md

## LLM Disclosure
[LLM(1)](https://github.com/davnotdev/disclosure-levels) - This project is assisted with chatbots.

```

Use of LLMs to source information, snippets, or filter through data using a prompt and response model. 

## LLM(1S) - Chatbot and Static Analysis Only 

```md
## LLM Disclosure

[LLM(1S)](https://github.com/davnotdev/disclosure-levels) - This project assisted with chatbots and LLM static analysis.

```

Same as LLM(1), but the LLM may read the project and audit for mistakes, bugs, and security issues.

## LLM(2) - Copilot

```md
## LLM Disclosure

[LLM(2)](https://github.com/davnotdev/disclosure-levels) - This project uses some LLM copiloting with human approval.

```

LLMs may write to the project, but each step requires human approval.

## LLM(3) - Agent

```md
## LLM Disclosure

[LLM(3)](https://github.com/davnotdev/disclosure-levels) - This project uses some LLM agentic development with human review.

```

LLMs may work directly on the project, but the final result must be reviewed by a human before publishing.

## LLM(4) - Autopilot

```

## LLM Disclosure

[LLM(4)](https://github.com/davnotdev/disclosure-levels) - This project uses some LLM agentic development.

```

LLMs may work directly on the project, and should ideally review its own work.

## LLM(5) - ???

Personally, I have not ventured further than LLM(4), open an issue if you have ideas.

## Modifiers

Modifiers should be listed in alphabetical order.

### LLM(XA) - Generative Assets

`LLM(XA) - XXX, with generative assets.`

A stands for assets which may refer to images, logos, or other media.
Of course, different tiers of asset generation exist, but that is outside the scope of this document.

### LLM(XD) - Generative Documentation

`LLM(XD) - XXX, with generative documentation.`

D stands for documentation.
If LLMs are used only for spell checking or minor edits, that can fall under LLM(1S). 

### LLM(XP) - Applying to Dependencies

`LLM(XP) - XXX, including dependencies.`

P stands for pure meaning that all "dependencies" adhere to level X (to the author's best effort).
For example LLM(0P), means the project and all of its dependencies are human made.
The definition of "dependencies" can be interpreted by the author.

---

## LLM Disclosure

[LLM(0)](https://github.com/davnotdev/disclosure-levels) - This project is human made.

