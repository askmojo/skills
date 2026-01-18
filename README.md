# AskMojo Skills

**Reusable, context-aware AI skills that remember your business.**

Stop copy-pasting prompts. Build skills that work repeatedly with your context.

---

## The Difference

**Prompts** (traditional approach):
- Copy-paste every time you need them
- Re-explain your context, voice, preferences
- Generic outputs that don't know your business
- Prompt engineering as ongoing overhead

**Skills** (AskMojo approach):
- Build once, reuse forever
- Provide context once, use repeatedly
- Consistent outputs aligned with your goals
- Focus on work, not prompt crafting

---

## Philosophy

> **"Prompts are good. Skills with memory are better."**

We believe AI should amplify your expertise, not require you to become a prompt engineer. These skills are designed to:

1. **Work repeatedly** - Use the same skill over and over
2. **Accept your context** - Business goals, brand voice, constraints
3. **Stay consistent** - Outputs align with your strategy
4. **Save time** - Stop re-explaining, start executing

---

## How to Use

### Option 1: AskMojo (Recommended)

**Best experience with [askmojo.ai](https://askmojo.ai):**

1. **Import skills** - Add any skill from this library to your AskMojo workspace
2. **Set up context once:**
   - Your business goals & priorities
   - Target audience profiles
   - Brand voice & tone guidelines
   - Past examples & preferences
3. **Use skills naturally:**
   - Select skill from dropdown in chat input, OR
   - Just ask: "Use [skill-name] for: [your input]"
4. **Context auto-loads** - Every skill uses your context automatically

**Why AskMojo is better:**
- ✅ **Setup once, use everywhere** - Context shared across all skills
- ✅ **Integrated APIs** - Built-in web research, image generation, data analysis
- ✅ **No repetition** - Never re-explain your business context
- ✅ **Learns from edits** - Outputs improve based on your feedback
- ✅ **Tool orchestration** - Skills can call other skills and APIs

[Start free at askmojo.ai →](https://askmojo.ai)

### Option 2: Import Into Claude (Native Skill Support)

**Claude has native skill support** - you can import skills directly from this repo.

**How to import a skill:**

1. **Download the skill**
   - Click into the skill folder you want (e.g., `growth-consultant/`)
   - Click "Code" → "Download ZIP" (or download just that folder)
   - Make sure the ZIP contains a `SKILL.md` file at its root

2. **Upload to Claude**
   - Go to claude.ai and sign in
   - Click your name → **Settings** → **Capabilities**
   - Scroll to the **Skills** section
   - Click **Upload skill**, choose the ZIP file
   - Toggle the skill **On** in the skills list

3. **Use the skill**
   - Start a new chat
   - Describe your task using words that match the skill's description
   - Example: "Analyze my competitor landscape using growth consultant"
   - Claude will automatically recognize and apply the skill
   - You'll see which skill Claude is using during the conversation

**No manual setup needed** - Claude handles context management automatically.

[📖 Official Claude Skills Documentation](https://support.claude.com/en/articles/12512180-using-skills-in-claude)

---

### Option 3: Reuse In ChatGPT (Manual Instructions)

**ChatGPT doesn't support native skill imports**, but you can reuse the skill's instructions manually.

#### Method A: Custom Instructions (All Users)

**Best for:** Applying one skill globally to all your chats

1. Open ChatGPT → **Settings** → **Custom instructions**
2. From the skill's `SKILL.md` file:
   - Copy the description and process into **"How would you like ChatGPT to respond?"**
   - Optionally copy context requirements into **"What should ChatGPT know about you?"**
3. **Save** - Now all chats follow that skill until you change it

**Limits:** 1,500 characters per field

---

#### Method B: Custom GPT (Plus/Pro/Team/Enterprise)

**Best for:** Creating a dedicated version of one skill

1. In ChatGPT, click **Explore GPTs** → **Create**
2. Set up the GPT:
   - **Name:** Use the skill's name (e.g., "Growth Consultant")
   - **Description:** Copy from the skill's description
   - **Instructions:** Paste the entire `SKILL.md` content
   - **Knowledge:** Upload any reference files if needed
3. **Save** your Custom GPT
4. **Use it:** Select that GPT from your list whenever you need it

**Benefit:** Dedicated version per skill, doesn't affect other chats

[📖 ChatGPT Custom Instructions Guide](https://www.datacamp.com/tutorial/how-to-use-chat-gpt-custom-instructions)

---

#### Comparison Table

| Method | Setup Time | Reusability | Context Memory | Best For |
|--------|-----------|-------------|----------------|----------|
| **AskMojo** | 1 min once | ⭐⭐⭐ Perfect | Persistent across all skills | Regular use, multiple skills, integrated APIs |
| **Claude Skills** | 2 min/skill | ⭐⭐⭐ Perfect | Per skill, auto-managed | Native Claude users, clean skill isolation |
| **Custom GPTs** | 10 min/skill | ⭐⭐ Good | Per GPT only | Dedicated ChatGPT versions per skill |
| **Custom Instructions** | 5 min once | ⭐ Limited | Global, single skill | Applying one skill to all ChatGPT chats |

---

#### Why AskMojo vs Claude/ChatGPT?

**Claude Skills & ChatGPT work great** for individual skills. AskMojo adds:

✅ **Cross-skill context** - Set up your business context once, all skills use it
✅ **Integrated APIs** - Built-in web research, image generation, data analysis
✅ **Skill orchestration** - Skills can call other skills automatically
✅ **Learning system** - Improves outputs based on your edits over time
✅ **No setup per skill** - Import once, works with your existing context

**Use Claude/ChatGPT if:** You only need 1-2 skills occasionally
**Use AskMojo if:** You use multiple skills regularly and want shared context

---

## Skills Library

*Skills will be added here as they're created from viral prompt frameworks.*

Check back soon for:
- Competitive strategy analysis
- Marketing campaign planning
- Content brief generation
- And more...

---

## Contributing

Found a viral prompt framework that should be a skill?

**Open an issue** with:
- Link to the original prompt post
- Use case it solves
- Why it would be valuable as a reusable skill

We prioritize prompts with:
- High engagement (1000+ likes)
- Clear business value
- Reusable workflows
- Broad applicability

---

## Why Open Source?

We're building [AskMojo](https://askmojo.ai) - a platform for AI-powered business workflows with persistent context management.

These open-source skills demonstrate our approach: **context curation over prompt engineering**.

By sharing these skills, we help people:
- Move beyond copy-paste prompts
- Build better AI workflows
- Understand the value of persistent context

If you want automated context management and skill orchestration, check out [AskMojo](https://askmojo.ai).

---

## About

Created by [@erwan-petton](https://linkedin.com/in/erwanpetton) - Building AI systems that amplify human expertise.

**Philosophy**: AI should handle the mechanical work so humans can focus on what's uniquely human - judgment, taste, context, relationships, and meaning-making.

---

## License

MIT License - Use freely, attribution appreciated.

---

**Prompts are good. Skills with memory are better.**
