# When It Gets Weird

Failure modes you'll hit, and what to do about them. None of these are your fault. All of them are recoverable.

## Claude confidently produces something wrong

**What it looks like:** A plausible, well-written response that misdescribes your work, your team, your situation, or the thing you actually asked about.

**What to do:** Tell Claude specifically what's wrong. "That's not right — the actual situation is X" or "You're describing a version of this that doesn't match what I said." Don't soften it. Don't give Claude an out. Have it revise.

**Why this is the single most important habit to build:** Claude will match the confidence level of its training distribution, not its actual knowledge. The correction loop is where your vault gets sharp. If you let wrong-but-plausible outputs stand, the vault drifts and the drift compounds.

## The vault describes you in a way that doesn't fit

**What it looks like:** You read a section of your vault file and think "that's not quite me" or "I wouldn't say it that way" or "this makes me sound like someone I'm not."

**What to do:** Rewrite it. Either directly in the file, or by telling Claude "rewrite this section — here's what's off about it." If the vault doesn't sound like you, it won't produce work that sounds like you.

## Claude forgets context mid-conversation

**What it looks like:** Halfway through a long conversation, Claude starts responding as if it doesn't have your vault loaded, or loses track of a thread from earlier in the same conversation.

**What to do:** Start a new conversation in the same Project. Project Instructions reload. For long-running threads, it's usually better to start fresh every few days anyway — the vault is the persistence mechanism, not the conversation.

## Outputs feel generic

**What it looks like:** Claude produces responses that could apply to anyone — no signal that it knows who it's working with.

**What to do:** Two checks. First, is the vault actually loaded? Look at your Project Instructions field — is it populated? Second, is the vault itself thin? If most sections are empty or vague, outputs will be generic. Generic output is often an instruction to fill in the vault more.

## Claude agrees with everything you say

**What it looks like:** You float a half-baked idea and Claude tells you it's great. You push back on Claude's suggestion and Claude immediately capitulates. Every conversation feels like validation.

**What to do:** Tell Claude explicitly to push back. Something like: "I'd rather you challenge my framing than agree with it. If my thinking has a blind spot, name it." Update your `YOURNAME_CLAUDE.md` voice notes to make this a default. Validation feels good for about ten minutes and then becomes useless.

## The vault gets bloated

**What it looks like:** Three months in, your vault is 40 pages, most of it isn't accurate anymore, and loading it into a conversation slows Claude down.

**What to do:** Prune. Delete sections that aren't active. Split stale material into a separate archive file. The vault should be current, not comprehensive. Recency beats completeness.

## Something sensitive ends up in the vault

**What it looks like:** Claude writes down something about a person, a situation, or a decision that you don't want persisting in a file. Could be client information, a team dynamic, a personal detail — anything that shouldn't sit there indefinitely.

**What to do:** Delete it from the file. If you need Claude to remember it for a single conversation, keep it in chat and don't file it back. Be explicit with Claude about what doesn't get written down: "don't add anything from this conversation to my vault unless I tell you to." The default is that Claude saves helpful-seeming things; you can override that default.

## Cowork asks for permission before doing things

**What it looks like:** You ask Cowork to write or change a file and it pauses to confirm.

**What to do:** This is a feature, not a bug. Cowork checks before making file changes because the folder is yours. Say yes or no. Over time you'll develop a sense of when to pre-authorize ("go ahead and save edits to the vault without asking") and when to require confirmation.

## Claude references things you didn't tell it

**What it looks like:** Claude mentions details about you — where you live, roles you hold, interests you have — that didn't come up in your vault conversation. It feels like Claude knows things you didn't share.

**What to do:** That context is almost certainly coming from your Claude account preferences, which Claude can see across all your conversations. It's not secret, but it's worth knowing it's there. Two options:

- **Leave it on.** Claude will continue to draw on that context. Useful if your preferences are accurate and you want the benefit of pre-populated context.
- **Turn it off for this work.** In Claude settings under Profile, you can clear or edit your preferences. You can also tell Claude directly: "don't use my account preferences for this project — only use what's in my vault." Claude should respect that.

The vault's design assumes that what's in the vault is what you consciously authored. Account preferences are a separate layer. If they're feeding your vault without your awareness, that's a boundary worth making explicit.

## A section's framing doesn't fit how you think

**What it looks like:** Claude asks about "What I'm protecting" or "Open questions I'm holding" or similar, and the phrasing doesn't land. You don't think about your work in those terms. The question feels like a pop quiz where the expected answer doesn't exist for you.

**What to do:** Two options, both fine:

- **Ask Claude to rephrase.** "That framing doesn't match how I think about it. Try a different angle?" Claude should be able to adapt the question to language closer to yours while keeping the section's purpose.
- **Mark the section as observational.** Tell Claude: "I don't think about this explicitly — notice it as we work together and flag it when you see it." The section stays thin on day one and grows by observation rather than by direct answer.

The section headings in the vault template are defaults, not prescriptions. If "What I'm protecting" should be "Things to flag" for you, rename the section. The vault serves you; you don't serve the template.

## Claude declared onboarding done before you were ready

**What it looks like:** You ask a question that touches on real work, Claude answers, and then Claude treats the onboarding as complete and pivots into working mode — even though you haven't visited every section, you haven't explicitly said you're done, and you haven't done the Project Instructions step.

**What to do:** Tell Claude to come back to the flow. "We're not done with onboarding. We still need to visit [sections]. Let's finish that before pivoting." Claude should resume where you left off.

This is a known drift pattern. The onboarding should end only when you explicitly say so — not when Claude judges the vault "scaffolded enough." If it happens often, flag it so the kit can be sharpened.

---

If something breaks in a way not listed here, tell Claude what happened and ask how to recover. And flag it — it's worth knowing about.
