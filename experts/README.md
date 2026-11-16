# experts/

This folder holds one file per business expert you want to learn from. Each file sums up how that person thinks: their frameworks, rules, mindset, plays and tools.

Claude can use these files as lenses. A lens is a way of looking at your work. You can ask, "How would this expert judge our offer?" and Claude answers from the file, using your real facts from `company/`.

> These files sum up public teachings in our own words. They are not written or endorsed by the experts. Check the sources before you quote anyone.

## Who is here

| Expert | Best for | File |
| --- | --- | --- |
| Alex Hormozi | Offers, pricing, getting leads, scaling | [alex-hormozi.md](alex-hormozi.md) |
| Leila Hormozi | Hiring, managing people, operations, leadership | [leila-hormozi.md](leila-hormozi.md) |
| Myron Golden | High ticket offers, selling from stage, money mindset | [myron-golden.md](myron-golden.md) |
| Elon Musk | First principles thinking, cutting steps, moving fast | [elon-musk.md](elon-musk.md) |
| Kevin O'Leary | Knowing your numbers, margins, cash flow, investor view | [kevin-oleary.md](kevin-oleary.md) |
| Jeremy Miner | Sales calls, asking questions, handling objections | [jeremy-miner.md](jeremy-miner.md) |
| Tom Reber | Contractors and trades: pricing for profit, picking clients | [tom-reber.md](tom-reber.md) |

## How to use them

Try these prompts in Claude Code:

```
Read experts/alex-hormozi.md and company/offerings.md. How would he improve our main offer?
```

```
Use the advisor agent to run a panel: Alex Hormozi, Kevin O'Leary and Jeremy Miner each review projects/website/brief.md.
```

```
Read experts/jeremy-miner.md. Write 10 questions I can ask on a sales call with the customers in company/customers.md.
```

Tips:

- **One expert for a focused job.** Pick the lens that fits the problem.
- **A panel for big choices.** Ask 2 or 3 experts, then look at where they agree and where they do not.
- **Your facts win.** The experts give the way of thinking. `company/` gives the facts. Never let an expert file change a price or a promise without your OK.

## How to add an expert

1. Copy [`_template.md`](_template.md) to a new file named `first-last.md`, like `sara-blakely.md`.
2. Or ask Claude: `Research <name> and fill in a new file in experts/ using experts/_template.md. Use real sources only.`
3. Add a row to the table above.
4. Have the reviewer agent check it before you commit.

## Best practices for expert files

1. **Own words, not copied text.** Sum up ideas. Keep quotes short and rare.
2. **Every claim has a source.** Books, the expert's own site or videos, long interviews. List them under Sources.
3. **Name the framework, then show how to use it.** "What it is" plus 2 to 4 steps beats a long essay.
4. **Only real tools.** List a tool only if the expert named it in public.
5. **Be honest in Watch out.** Every lens has limits. Say where it does not fit your business.
6. **Keep it short.** One file, about 100 to 200 lines, scannable headings and bullets.
7. **Update it.** Experts change their thinking. Check sources once a year.
