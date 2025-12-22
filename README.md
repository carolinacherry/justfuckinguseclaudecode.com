# justfuckinguseclaudecode.com

[![Built with Claude Code](https://img.shields.io/badge/Built%20with-Claude%20Code-blue?logo=anthropic)](https://claude.ai/code)
[![Testimonials from X](https://img.shields.io/badge/Testimonials%20from-X-black?logo=x)](https://x.com)

> A shrine to the AI coding tool that actually fucking works.

## What is this?

A simple single-page website that displays real testimonials from real people on X/Twitter who are losing their minds over how good Claude Code is.

Inspired by the legendary [ifuckinghatejira.com](https://ifuckinghatejira.com) — except this one is about love, not hate.

## How we made this

1. **Used [Grok](https://x.com/i/grok)** to prompt a list of 100 X testimonials about how great Claude Code is
2. **Exported the list** to a markdown file
3. **Used [Claude Code](https://claude.ai/code)** to build the entire page in one session
4. **Bought the domain** on [GoDaddy](https://godaddy.com) for $12.19

That's it. The styling, animations, and functionality are 100% inspired by [ifuckinghatejira.com](https://ifuckinghatejira.com). We just swapped the hate for love.

Total time: ~17 minutes. Total cost: $12.19. Total lines of code written by a human: 0.

## Features

- 🎲 Random testimonial on each visit
- ✨ Fancy hand-drawn highlight animations (thanks [Rough Notation](https://roughnotation.com/))
- 🔗 Shareable URLs (`#1`, `#2`, etc.)
- ⬅️➡️ Browser back/forward support
- 📊 Google Analytics (because we want to know how many people are visiting)
- 🍦 Vanilla JS, no framework, no build step, just vibes

## Run locally

```bash
git clone https://github.com/carolinacherry/justfuckinguseclaudecode.com.git
cd justfuckinguseclaudecode.com
python3 -m http.server 8080
# Open http://localhost:8080
```

## Add a testimonial

Found a banger tweet about Claude Code? PRs welcome!

Edit the `testimonials` array in `index.html`:

```javascript
{
  html: `<p>Your testimonial with <em>highlights</em> and <strong>underlines</strong>.</p>`,
  author: "@username",
  link: "https://x.com/username/status/123456789"
}
```

- Wrap text in `<em>` for yellow highlights
- Wrap text in `<strong>` for red underlines

## Deploy

It's just a static HTML file. Drag and drop to Netlify, Vercel, Cloudflare Pages, or literally anywhere.

## The Fine Print

Yes, Claude Code will:
- Say "You're absolutely right!" so often you'll question your own sanity
- "Compact conversation" right when you needed that context
- Apologize for things that aren't its fault
- Occasionally gaslight you about code it definitely wrote

But then it'll one-shot a bug that's haunted you for 3 days, and suddenly all is forgiven. It ships features faster than your entire engineering team and costs less than one engineer's weekly coffee budget.

Stockholm syndrome? Maybe. Best coding agent in the world? Absolutely.

## Disclaimer

This site is not affiliated with Anthropic. We just really, really like their product.

Built with Claude Code, obviously. 🤖

---

**[justfuckinguseclaudecode.com](https://justfuckinguseclaudecode.com)** — Stop debating. Start shipping.
