# Example Agent Prompts

This folder collects **good agent prompts** for common design tasks. They're meant to be:
- **Battle-tested** — someone actually used this and it worked
- **Specific** — not "make a good design," but "turn this PRD into a mobile onboarding flow"
- **Reusable** — another team should be able to copy-paste and get ~80% of the way there

## How to contribute

1. Find a prompt that worked well for you
2. Add a new markdown file in this folder
3. Follow the template below
4. Open a PR

## Template

````markdown
# [Task name]

**Goal**: [one sentence]
**Agent type**: [designer / copy / layout / icon / PM / etc.]
**Input**: [what you feed in]
**Output**: [what you expect back]

## Prompt

```
[the actual prompt]
```

## Notes
- What works well
- What to watch out for
- Variations you've tried
````

## Categories we'd love examples for

- [ ] PRD → first design draft
- [ ] Design → developer-ready spec
- [ ] Copy tone conversion across a design system
- [ ] Accessibility review of an existing design
- [ ] Onboarding flow generator
- [ ] Empty state / loading state generator
- [ ] Design critique / review
- [ ] Multi-agent handoff (e.g. PM agent → design agent → QA agent)
