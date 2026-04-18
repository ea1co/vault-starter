# Integration

A methodology for reconciling what happens when you send the same question to several people and get several different responses back. Load this file into a conversation when you're ready to work through a pile of reviewer inputs. Skip it until then.

## The pattern this is for

You have a question or brief that matters. You've sent it to a handful of advisors, experts, or colleagues — four is a common number. Their responses are back. Some agree. Some disagree. Some are reading the question differently than others. Now what?

The common failure mode is to summarize the responses and call it done. That's aggregation, and it wastes what you paid for. You didn't send the brief to four people to average their views — you sent it because each one sees something the others don't, and the variance between them is the data.

Integration is the practice of working that variance into a stronger read than any individual response could give you.

## The six moves

Work these in order. Each one is a distinct move and does different work.

### 1. Converge

Find where the responses agree. Unanimous agreement across differently-positioned reviewers is usually robust signal — but not always. Sometimes reviewers agree because they share the same blind spot. Name the agreement, then ask: is this agreement because the point is strong, or because none of them were positioned to see past it?

### 2. Adjudicate

Find where they disagree on facts. Factual disagreements can usually be resolved — one is right, one is wrong, or a further question settles it. Don't leave factual disagreements unresolved; they corrupt the rest of the analysis. If you can't resolve one on your own, flag what additional input you need.

### 3. Surface the frame clash

Find where they disagree not on facts but on *how to see the problem*. This is often the most valuable finding in the whole exercise. Different framings produce different problems, which produce different answers. Name the competing framings explicitly. Ask which framing is serving the actual question and which is imposing a shape that doesn't fit.

The frame clash is where "wicked problems" reveal themselves. Most hard strategic questions aren't about picking between solutions — they're about choosing which problem to solve.

### 4. Blind spots

Ask what *none* of the reviewers addressed. This usually requires bringing in a perspective outside the panel — a different discipline, a different role, a different vantage. If you assembled a panel of marketing experts and none of them mentioned legal risk, that's not because the legal risk isn't there — it's because your panel was positioned not to see it.

Naming the blind spot is often the most original contribution you'll make in the whole exercise.

### 5. Hold the tension

Some disagreements shouldn't be resolved. They represent genuine dualities in the situation that strategy has to *navigate* rather than *decide*. If reviewers A and B disagree because A prioritizes short-term credibility and B prioritizes long-term positioning, the answer isn't to pick one — it's to design an approach that honors both, and to be explicit about the trade-off.

The move here is to name the tension as a feature, not a bug. Strategies that try to resolve every tension usually collapse into one of the poles.

### 6. Posture, not summary

The output is not a digest of what the reviewers said. It's your reading: here is what we now see, here is what remains uncertain, here is what we are going to do. Compressed — ideally under 250 words. If you find yourself rehashing the reviewers, stop and ask what *you* think now that you've heard them.

This is the move that distinguishes integration from aggregation. Aggregation produces a summary. Integration produces a posture.

## The epistemology underneath

The reason this practice works is that every response — human or model — is *positioned*. It's shaped by the reviewer's priors, situational exposure, training, and frame. No single positioned observer can see the whole shape of a complex situation. Triangulating across differently-positioned observers gets closer to the shape than any of them could alone.

This is also why **the reviewers themselves aren't the answer** — they're inputs. The integration is the answer, and you're the integrator. A pile of reviewer responses without integration isn't strategy; it's raw material.

## Using this with Claude

You can load this file into a Cowork conversation along with the brief and the reviewer responses, and have Claude run the six moves explicitly. A prompt that works:

> "I've loaded [brief file] and [reviewer response files]. Work the six moves from INTEGRATION.md in order. Label each section. For moves where the answer isn't clear, flag the uncertainty rather than forcing a conclusion. For move 6, keep the posture under 250 words."

When Claude produces the integration, push back on the weakest section. Tell it what's missing or wrong. The revision is where the analysis gets sharp.

## One caution

Claude is also a positioned reviewer. When you load this file and ask Claude to integrate responses, you're not getting a neutral synthesis — you're getting Claude's integration, which has its own frame. The strongest version of this practice is you integrating, with Claude as one voice among others. If you find yourself deferring to Claude's posture, that's a signal to push back.
