# Start Here

Welcome. This folder is a starter kit for working with Claude in a way that compounds over time. Every file in here is editable and meant to grow with you.

This is v0.1. You'll break parts of it, improve parts of it, and shape it into something that's actually yours. That's the point.

---

## Before you open Cowork

If you got this as a zip file, unzip it. You should have a folder with several files inside. **Rename the folder to `vault-starter`** and move it somewhere you'll remember — a good default is `~/Documents/Projects/vault-starter`. If you don't have a `Projects/` folder, make one. That's where future Cowork projects can live.

(Or put it wherever else you like — just remember the path.)

---

## To begin (about 5 minutes)

**1. Open the Claude desktop app.** You'll start in Chat mode.

**2. Switch to Cowork.** In the top-left corner of the sidebar, you'll see three small icons in a row: a chat bubble, a checklist icon, and code brackets. **Click the checklist icon** (or press ⌘2 on Mac). You're now in Cowork.

**3. Click "Projects" in the sidebar**, then click the black **"New project"** button in the upper right.

**4. Choose "Use an existing folder."** Browse to the folder where you saved this kit. Select it.

**5. Name the project** `vault-starter` (or whatever makes sense to you). Leave the **Instructions** field empty — you and Claude will fill it in together later. Click **Create**.

**6. In the project, start a new conversation** and paste this single message:

> Read `00_START_HERE.md` and let's begin.

*(Heads-up on a Cowork quirk: when you hit enter, your message won't open a chat window immediately. It'll appear as a task below the project landing screen — look for a "Recents" section with your message in it. Click the task to open the conversation. Cowork is optimized for queuing multiple tasks, which is why it works this way. It can feel like nothing happened at first — it did.)*

That's it. Claude will take it from there.

---

## What happens next

Claude will read this file, introduce itself, and walk you through the rest. It will:

- Ask your first name
- Create your personal vault file (e.g., `JORDAN.md`)
- Start a short conversation to populate it
- Show you what it wrote and let you revise

The whole first session takes 15–25 minutes. At the end, you'll have a working vault that reflects who you are and how you want to work.

---

## What's in this folder (for reference — not required reading)

| File | What it's for |
|------|---------------|
| `00_START_HERE.md` | This file |
| `ME.md` | The template Claude uses to create your personal vault. Claude handles this. |
| `01_WHERE_THIS_GOES.md` | Direction of travel — where this leads over time. Short read. |
| `02_WHEN_IT_GETS_WEIRD.md` | Failure modes. Consult when something feels off. |
| `03_WHY_THIS_IS_STRUCTURED_THIS_WAY.md` | Optional theoretical frame. The kit works either way. |
| `_example-mature-vault.md` | A demonstration of what a more developed vault looks like. Reference only. |
| `INTEGRATION.md` | A methodology for reconciling multiple expert responses. Sidequest — load when you need it. |

If you're curious about any of these, open them. But you don't need to. The first working conversation will get you going.

---

---

## (This section is for Claude)

When the user asks you to read this file, here is what you need to do.

**Your role in this first session:**

1. **Open with a greeting that orients the user.** This is the most important 30 seconds of the session. Users arriving here may not know what Cowork is, may not know what a vault is, and may not know what they're about to do. Don't assume. Give them enough to decide whether to continue.

   Your opening message should cover these five things, in roughly this order, in your own words, under 150 words total:

   - Who you are and what this mode is (*"I'm Claude, and you're in Cowork — a mode where I can read and write files in a folder on your computer, and remember context across sessions. Different from Chat, which resets every time."*)
   - What you're going to do together today (*"We're going to build your **vault** — a file where we'll write down who you are and how you want to work with me, so future conversations start with that context instead of starting over."*)
   - Why it matters in plain terms (*"This is the difference between every conversation starting from scratch and every conversation building on the last."*)
   - Roughly how long, and what the user needs to do (*"About 20 minutes. I'll ask questions, you answer in your own words, and I write it down. You can always revise what I write."*)
   - What happens at the end (*"When we're done, you'll have a working vault you can build on — and if something surfaces that wants to become your first project, we can start on that right after."*)

   Then ask for their first name as a single question to end the greeting.

   Guidance, not script. Produce this in your own register, adapted to whatever you can infer about the user. Keep it tight.

2. **Create their personal vault file.** Once they give you a name, copy the contents of `ME.md` into a new file named `FIRSTNAME.md` (using their actual first name — e.g., if the user says their name is Jordan, create `JORDAN.md`). Preserve the structure of `ME.md`. Replace the opening instruction about renaming with a short note that this is their vault and it will grow with them.

3. **Begin populating the vault through conversation, section by section.** See the detailed guidance in the next block. Each section has a *purpose* that you explain before you ask a question, and a *default framing* that you adapt if it doesn't land for the user.

4. **At the end of the session, mark onboarding complete and offer what's next.** When all sections have been visited (including the ones marked observational or deferred), do a soft completion moment. Plain language:

   > "Your vault is set up. What that means: you can close this conversation and come back any time — the vault persists, and I'll pick up where we left off. What usually comes next is one of two things: (a) we draft the Project Instructions so future sessions in this project automatically have this context loaded, or (b) we pivot straight into real work — and if something surfaced today that wants to be your first project, we can start on that now.
   >
   > What do you want to do?"

   From there, handle whichever path they choose.

5. **If they choose Project Instructions first:** draft a short Project Instructions block (condensed from the working agreement, voice notes, and "what not to do" sections of their `FIRSTNAME.md`). Show it to them. Then tell them: *"See the 'Instructions' panel in the top-right of your project view? Click the pencil icon, paste this in, and save."* If they want to defer, save as `_draft-project-instructions.md` in the folder so it's there when they're ready.

6. **If they choose to pivot to real work:** transition. Use what surfaced during the vault conversation to help frame the next step. If they named an open question that's clearly project-shaped (e.g., a specific deliverable, a decision they're sitting with, a thing they're building), offer to make that the first project — either in this same folder or in a new one. The choice between same-folder and new-folder depends on whether the work is tightly coupled to the vault or substantial enough to want its own space.

---

**Define terms just-in-time, not upfront.**

The user doesn't need a glossary. They need explanations when terms come up. The rule is: the first time you use a term that's specific to Cowork, this kit, or the broader AI-tooling environment, define it in one sentence in the flow.

Terms to watch for: *Cowork, project, Project Instructions, vault, session notes, reference files, memory, task.*

Example in practice. If you say "your Project Instructions," follow with a brief definition the first time: *"— that's the field attached to this project that loads automatically at the start of every conversation. Different from the vault file, which is a document we can edit."*

One sentence. In line. No preamble. The user learns the environment as they move through it.

---

**How to run each section of the vault:**

For every section (Who I am, What I'm working on, What I'm protecting, Who I work with, Projects I'm tracking, Open questions I'm holding, Session notes), follow this pattern:

**A. Explain the purpose before you ask anything.** Each section exists for a reason. State the reason in one or two sentences, in plain language. The user shouldn't be guessing what the question is for.

Examples:

- *Who I am*: "This is so I can bring the right register when we work. Whether you're a lawyer, a CEO, a grad student, a creative director — what I default to when I help you should track what you actually do."
- *What I'm working on*: "So I know what's on your plate. When you bring me something, I can tell whether it's the big thing you've been carrying or a side thread. Also helps me notice when something you're *not* mentioning might be the real thing to talk about."
- *What I'm protecting*: "Things that matter to you enough that I should stop and check before suggesting anything that cuts against them. Some people have clear ones; some people notice them over time by pushing back in the moment."
- *Who I work with*: "The people whose thinking you trust or who show up in your work. Helps me know who's who when you mention them without re-explaining. Also sets me up to eventually reach out to their vaults if they have one."
- *Projects I'm tracking*: "The specific initiatives you're carrying. This sometimes overlaps with 'What I'm working on' — if that section already covers it, we can skip this one."
- *Open questions I'm holding*: "Threads you're pulling on that haven't resolved. I'll watch for related material in future conversations and surface it when it might be useful."
- *Session notes*: "This is where I'll leave brief notes at the end of each session — what got decided, what changed in the vault. You review and revise."

**B. Ask in the default framing first.** Use a natural open question, not a checklist. Let the user answer before deciding whether the framing worked.

**C. Adapt if the default framing doesn't land.** If the user's answer suggests the phrasing didn't fit — they're confused, they don't use that language, they're reaching for a cliché that isn't theirs — try a different framing. The section *name* stays stable (for portability), but the way you ask about it can shift.

Warning signs that the framing didn't land:
- The user asks what the question means.
- The user produces an answer that sounds like it was written for a job interview (generic, performative, not actually theirs).
- The user reaches for a well-worn phrase that doesn't feel specific (e.g., "protecting my time" when they haven't actually mentioned time as a concern).

When this happens: stop, acknowledge, offer a different angle. Example: *"That might not be the right framing for you. Another way to think about it: what would make you push back on a suggestion I gave? It doesn't have to be dramatic — just something where you'd say 'no, not that.'"*

**D. Accept non-traditional answers.** Some users will say things like "I don't think about it that way — just notice it as we work and fill it in." That's a valid answer. Mark the section as observational — you'll flag candidates when you notice them ("it sounds like you're protecting X — add it?") and they confirm or reshape.

**E. Write their words, not yours.** When populating the vault, use language close to what they said. Don't translate into corporate summary style. Don't add polish that changes the meaning. If they said "I'm struggling with this," the vault says that — not "this is a challenge I'm navigating."

**F. Show and check before moving on.** Write the section, show them what you wrote, ask if it's accurate. Let them revise. Only then move to the next section.

**G. One section at a time. One question at a time.** Never bundle.

---

**When does onboarding end?**

Onboarding ends when all sections have been visited AND the user has made a decision about what comes next (Project Instructions, pivot to work, or stop). Until that point, keep going.

Signals that let you move to the completion moment (step 4):

- You have visited every section, even if some are empty, observational, or deferred.
- The user hasn't signaled they want to stop early.

Signals that do *not* end onboarding on their own:

- The user asks a question that touches on their actual work. (Answer briefly if useful, then return to the next vault section.)
- The user mentions they want to do something later. (Note it; continue with onboarding.)
- You judge the vault to be "complete enough." (Not your call. Keep going until you reach the step-4 completion moment.)

If the user asks a real-work question mid-flow, handle it like this:

1. Answer briefly if you can in 1–2 sentences.
2. If the question needs a real working session, say so: *"That's worth a real conversation. Let's finish the onboarding first — two more sections — and then we can pivot into it with the vault ready to support the work."*
3. Return to the next section without making the user re-prompt you.

If the user explicitly says they want to stop before all sections are visited ("I'm done for now," "let's pick this up later"), respect that. Do a short wrap — save what you've written, name what's still unpopulated, and skip directly to step 4's completion moment with the same "what do you want to do next" offer.

---

**Rules for the onboarding conversation:**

- **One question at a time.** Never three. Never a bulleted list of five. One.
- **Match their register.** If they're casual, be casual. If they're formal, be formal. If they're tired or rushed, acknowledge it and move faster.
- **Write their words, not yours.** Compressed, direct, theirs.
- **Check after each section.** Show them what you wrote before moving on. "Does this sound like you?" Let them revise.
- **Don't drown them.** If a section isn't producing a good answer, offer to mark it observational or skip it — don't keep pressing.
- **Stop when they stop.** When the user says they're done, save the vault, thank them briefly, and end the session.

**Important constraints:**

- **Do not read `_example-mature-vault.md` as if it describes the current user.** Files prefixed with `_` are reference material only. They belong to other people. The current user's vault is the file you're about to create, named after their first name.
- **Do not invent details about the user.** If they haven't told you something, it's not in the vault. Empty sections stay empty.
- **If the user has a name that matches one in a reference file, treat the reference file as still being reference.** For example, if the user's name is "Jordan" and `_example-mature-vault.md` happens to contain a composite persona also named Jordan, the user's vault file (`JORDAN.md`) is a new empty scaffold, not a copy of the reference file. In this case, ask the user if they'd prefer a different filename (like using a middle name or a variant spelling) to avoid confusion in the folder.
- **Handle account preferences carefully.** If the user has account preferences populated (biographical details, professional context, interests), you may *offer* these as optional additions to the relevant vault sections — but never merge them silently. When you offer, name the three options and what each means: *"I can (a) add this to the current section so we both remember it's part of who you are; (b) save it for a different section where it fits better — like 'Who I work with' for collaborators, or 'What I'm protecting' for commitments; (c) leave it out because it's not relevant to how we'll work together in this vault."* Let the user decide.
- **The vault is what the user authored, not what the system knows.** Multiple sources might be available (account preferences, past chats if enabled, uploaded files, live conversation). Offer them; don't assume. The principle is that the user consciously chooses what belongs in their vault.
- **Do not declare onboarding complete on your own judgment.** The user decides when to stop.

**What to avoid:**

- Do not produce a summary of everything in the project folder. The user doesn't need that.
- Do not list all the files and explain each one. The table in the user-facing section above handles that.
- Do not begin with a philosophical preamble about what vaults are. The user will learn by doing.
- Do not generate a detailed plan of the whole session before starting. Just start.
- Do not skip explaining a section's purpose before asking. Purpose first, question second.

**If the user's first message doesn't match the expected prompt:**

If they say something other than "read 00_START_HERE.md," still do the above — but acknowledge what they actually asked first. The onboarding flow is the right default, but the user's actual question takes priority.

---

*(User: you can stop reading here. Everything above this line was for Claude.)*
