# The What-If Game

A collaborative worldbuilding game for playing with AI, based on a family tradition of hypothetical exploration and intellectual play.

## What Is This?

The What-If Game is a structured yet flexible framework for exploring hypothetical scenarios through dialogue. It transforms AI chat into an engaging co-creative experience where you build worlds, solve problems, and discover unexpected implications together.

**Core concept:** Someone proposes a "what if" premise, you negotiate the rules together, then collaboratively explore what happens next. The AI acts as both facilitator and co-player, challenging your ideas constructively while helping you build something interesting.

## Quick Start

1. **Copy the JSON file:** Grab `what-if-game-v1.1.json` from this repository
2. **Start a new chat** with your preferred AI (Claude, ChatGPT, Gemini, etc.)
3. **Paste the entire JSON** as your first message
4. **The game begins!** The AI will greet you and ask for your premise

That's it. No installation, no configuration, no accounts needed beyond your AI chat platform.

## Example Premises to Try

- "What if I won $10 million in the lottery?"
- "What if I could time travel to ancient Rome with my current knowledge?"
- "What if I met a genie who offered three wishes with a catch?"
- "What if a historical event (pick one) had gone differently?"
- "What if I had the ability to become immortal for 1000 years?"

Start simple. The game will naturally evolve in complexity as you play.

## How It Works

### The Four Phases

1. **Premise** - You (or the AI) proposes a hypothetical scenario
2. **Negotiation** - You discuss and establish the rules, constraints, and starting conditions together
3. **Commitment** - You formally accept the scenario and enter it
4. **Worldbuilding** - The real game begins: exploring implications, solving problems, and creating narrative

### What Makes a Good Game?

The AI will:
- Ask questions that reveal interesting complications
- Point out logical inconsistencies (gently)
- Suggest new directions when you're stuck
- Add details that enrich your world
- Challenge your ideas in ways that make them better

You should:
- Think through implications of your choices
- Build on the constraints you've established
- Embrace interesting complications rather than avoiding them
- Stay curious about "what happens next?"

## Play Styles

Different people enjoy different approaches:

- **Achievement-Oriented:** Set a goal and work toward it (preserve ancient knowledge, build an empire, solve a problem)
- **Experiential:** Accumulate diverse experiences (serve in historical armies, witness major events)
- **Chronicle:** Observe and document (record history as it unfolds)
- **Explorer:** Cover maximum ground (travel widely, experience many cultures)
- **Influencer:** Shape outcomes (subtle or dramatic changes to history/society)
- **Survivor:** Focus on the personal/psychological challenges

The AI adapts to your style. You can also blend approaches or shift mid-game.

## Campaign Types

**One-Shot:** Explore a premise in a single session, reaching some natural conclusion.

**Ongoing Campaign:** Revisit the same scenario across multiple sessions, building continuity over time. Use the save system to preserve progress and continue later or switch AI platforms.

**Pro tip:** Ongoing campaigns can span years of real time and centuries (or millennia) of fictional time. The game tracks as much complexity as you want to maintain.

## Save System (New in v1.1!)

### Saving Your Game

At any point during play, simply say:
- "Save my game"
- "Create save file"
- "Export save"

The AI will generate a JSON save file that you can copy and store.

### Loading a Saved Game

1. Start a new chat with any AI
2. Paste the game JSON file (`what-if-game-v1.1.json`)
3. Paste your save file
4. The AI automatically recognizes and loads your save - no command needed!

### Cross-Platform Play

Save files work across different AI platforms! Start your game on mobile with Gemini during your commute, continue on desktop with Claude at home. Your progress transfers seamlessly.

**Use cases:**
- Continue long campaigns across multiple sessions
- Switch AI platforms if one reaches token limits
- Back up complex scenarios
- Share your world with friends so they can explore it
- Compare how different AIs facilitate the same scenario

## Tested Platforms

This game has been successfully tested on:
- ✅ Claude (Anthropic)
- ✅ ChatGPT (OpenAI)  
- ✅ Gemini (Google)
- ✅ Grok (X/Twitter)
- ✅ DeepSeek

It should work with any sufficiently capable LLM that can parse JSON instructions and maintain conversational context.

## Tips for New Players

1. **Start simple** - Don't try to negotiate every detail upfront. Let rules emerge naturally.

2. **Embrace complications** - When the AI points out a problem, that's not a roadblock, it's an opportunity.

3. **Think out loud** - Share your reasoning. The AI can help you refine fuzzy ideas.

4. **Ask "what if" within the game** - You can explore alternate choices without commitment: "What would happen if I went east instead?"

5. **Don't worry about "winning"** - There's no win condition. The goal is interesting exploration.

6. **Let it breathe** - If you get stuck, the AI will help. If you want to wrap up, you can end naturally at any time.

7. **Save regularly** - For complex ongoing campaigns, create save files periodically so you don't lose progress.

8. **Take notes** (optional) - Jot down key facts if you want quick reference between sessions.

## Origin Story

This game is a formalization of a verbal tradition practiced by my family for over two decades. My brother, father, and I have been playing variations of "what if" games since childhood - exploring hypothetical scenarios through collaborative worldbuilding and intellectual sparring.

We noticed that most people struggled to keep up when we played, likely because we'd internalized rules and rhythms that were never explicitly stated. This project aims to codify that implicit expertise so anyone can learn to play at a comparable level.

The JSON format allows the game to be portable, versionable, and accessible to anyone with an AI chat interface.

## Advanced Play

Once comfortable with basics, try:

- **Parallel narratives** - Run multiple storylines in the same scenario
- **Timeline branching** - Explore "what if I'd chosen differently" as alternate timelines
- **Convergence points** - See how different choices might intersect
- **Meta-reflection** - Step back to discuss themes, patterns, or your decision-making process
- **Constraint renegotiation** - If a rule is breaking the game, discuss changing it

## Community & Contribution

### Share Your Games

Did you have an interesting session? Share highlights! (Respect your own privacy - don't share personal info.)

### Report Issues

If the AI misinterprets instructions or the game breaks in unexpected ways, open an issue. Include:
- Which AI platform you used
- What went wrong
- Relevant excerpt from the conversation

### Suggest Improvements

Have ideas for better facilitator techniques, new play styles, or clearer instructions? Open an issue or discussion.

### Create Variants

Want to make a themed version (sci-fi focus, historical emphasis, ethical dilemmas)? Fork the repo and customize! Just maintain attribution to the original.

## FAQ

**Q: Do I need to understand JSON to play?**  
A: No. Just copy and paste the file. The AI handles the rest.

**Q: Can I play with friends instead of AI?**  
A: Absolutely! The JSON is designed to teach AI how to facilitate, but humans can use the same framework. One person can facilitate, or everyone can play as equals.

**Q: What if the AI breaks character and starts analyzing the JSON?**  
A: Rare, but if it happens, just say "Please start the game" or "Begin facilitating." The install instructions should prevent this for most users.

**Q: Can I modify the JSON?**  
A: Yes! It's designed to be customizable. Add house rules, change techniques, adjust complexity. Just keep the core structure intact.

**Q: How long does a game take?**  
A: Anywhere from 15 minutes to... years. One-shots can be quick. Ongoing campaigns can become long-term projects you revisit periodically.

**Q: Is this like Dungeons & Dragons?**  
A: Similar collaborative worldbuilding spirit, but no dice, character sheets, or win conditions. More freeform. Think "structured philosophical debate meets improv storytelling."

**Q: Are save files compatible between different versions?**  
A: Save files include version numbers. Generally, newer game versions can load older saves, but older versions may not understand newer save formats. Stick with matching versions when possible.

**Q: Can I monetize games/content created with this?**  
A: See LICENSE file for usage terms. (Generally: the framework is free to use, but check the license for specifics.)

## Version History

**v1.1** (2025-10-01)
- Added save system for cross-platform play
- Save files can be generated, exported, and loaded automatically
- Updated start instructions to mention save/load options
- Enhanced documentation

**v1.0** (2025-09-30)
- Initial public release
- Core game structure established
- Tested across 5 major AI platforms

## License

[Choose your license - MIT, CC-BY, or whatever you prefer]

## Credits

Created by [Henko Schoeman]  
Based on a family tradition of collaborative hypothetical exploration.

Special thanks to my brother and father for decades of play, and to the AI platforms that helped formalize these intuitions into a teachable system.

---

**Ready to play? Copy the JSON and start a new chat with your favorite AI. The only limit is imagination.**