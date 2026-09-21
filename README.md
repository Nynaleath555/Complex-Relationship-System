# 👥💕 🤝💗🔥🫂💚 ⚖️ Nynaleath's Complex Relationship System V2

A dynamic relationship system for AI Dungeon designed to make NPC relationships develop more gradually, naturally, and realistically.

## ✨ What is this?

I designed this system to add more complexity and nuance to relationships with NPCs in AI Dungeon.
One of the problems with AI-driven romance is that the AI can sometimes advance relationships far too quickly in an attempt to satisfy the player. Characters may become close friends, romantic partners, or even fall in love after only a handful of interactions, regardless of how little trust, familiarity, or emotional connection has actually been established.
Complex Relationship System is designed to help prevent that.
Instead of treating a relationship as a single progression from strangers → friends → lovers, the system tracks several independent aspects of the relationship and allows them to develop at different speeds.
The system was originally created for my AI Dungeon scenario 🎼 The Melody Next Door 🎶, but it is designed primarily for romance scenarios with a single romantic interest, particularly those aiming for a slow-burn romance and a more realistic relationship progression.

## 💡 How it works
The system tracks multiple relationship dimensions independently:

👥 Friendship
Familiarity, companionship, and platonic connection

💕 Romance
The overall development of the romantic relationship

🤝 Trust
How much the NPC feels they can rely on the player

💗 Affection
Emotional attachment and fondness

🔥 Attraction
Romantic/physical interest

🫂 Comfort
How safe and comfortable the NPC feels around the player

💚 Jealousy
Emotional reaction to potential romantic rivals

⚖️ Stability
Overall emotional stability of the relationship

These values are independent.

For example:
An NPC can be attracted to the player without trusting them.
Two characters can become good friends without developing romantic feelings.
An NPC can trust the player while still feeling little attraction.
Romantic attraction does not automatically mean romance.
A relationship can become more emotionally intimate while still remaining platonic.
Betrayal can damage trust without completely destroying affection.
Jealousy can appear without automatically meaning that the NPC is in love.
This separation allows relationships to develop in less predictable and more believable ways.

## 🐢🔥 Designed for slow burn
The system is particularly suited for scenarios where romance should take time.
The goal is not to prevent romance from happening. The goal is to make romantic progression feel earned.
Small interactions produce small changes.

Meaningful events can produce larger changes.

Major emotional moments can significantly affect the relationship.

This means that an NPC should not suddenly go from barely knowing the player to being deeply in love with them simply because the player flirted a few times.

The relationship has to develop through interactions, shared experiences, trust, emotional connection, and the circumstances established by the story.

## 🔥 Designed to complement AI Dungeon's AI
This system does not replace the AI's narrative judgment.
Instead, it provides additional relationship context that the AI can use when deciding how an NPC should react.
The system is designed to work alongside Inner Self, and its relationship context can be incorporated into an AI Dungeon scenario through the appropriate scripting hooks.

Important: The system provides relationship state and context, but good AI Instructions and scenario writing are still recommended. The system works best when the AI is explicitly instructed to respect established relationships and avoid forcing romantic progression.

## 🔌 Compatibility

Complex Relationship System was designed to be compatible with 🎭Inner Self.
It is an independent project and is not part of, affiliated with, or maintained by the Inner Self project.

Complex relationship wasn't tested with Auto Cards or another scripts apart of Inner Self.

## 📦 Installation
### Requirements
-AI Dungeon script edit mode
-Inner Self original code by Lewd Leah 
-Basic familiarity with AI Dungeon scripting

### Setup
-Erase all code of your library, input, context and output
-Copy Inner Self original code library and paste into your library
-Copy Complex Relationship System library and paste into your library, below of Inner Self original code
-Copy Complex Relationship System input and paste into your input
-Copy Complex Relationship System context and paste into your context
-Copy Complex Relationship System output and paste into your output
-Add the recommended AI Instructions and Author's Note.
-Start your scenario.

# 📊 Relationship states
Each relationship dimension has several descriptive states.
Friendship

Enemy → Persona Non Grata → Neutral → Acquaintance → Friend → Good Friend → Best Friends
Romance

No Romantic Interest → Mild Attraction → Romantic Interest → Falling in Love → Sweethearts → Soulmates
Trust

Possessive → Jealous → Wary → Trusting → Secure
Affection

Indifferent → Fond → Attached → Deeply Attached → Devoted
Attraction

None → Curious → Attracted → Strongly Attracted → Intense Attraction
Comfort

Distant → Cautious → Comfortable → Close → Intimate
Jealousy

Calm → Alert → Jealous → Highly Jealous → Obsessive

Stable → Strained → Unstable → Distressed → Crisis

These labels are primarily used to give the AI a meaningful description of the current relationship state rather than exposing raw numerical values.

## 🎯 Recommended use
This system is best suited for:
💕 Single-love-interest romance scenarios
🐢 Slow-burn romance
🎭 Character-driven stories
🏠 Slice-of-life scenarios
🎸 Contemporary romance
📖 Stories where relationships develop over many interactions
🧠 Scenarios where NPC personality and emotional continuity are important

It may be less useful for scenarios where:
Romance is intentionally instantaneous.
The player has many simultaneous romantic interests.
Relationships are primarily determined by explicit player choices rather than gradual interaction.
The scenario does not require persistent relationship states.

# 📜 License
This project is licensed under the MIT License.

You are free to:
-Use the system in your own scenarios.
-Modify it.
-Integrate it into your own projects.
-Publish scenarios containing it.
-Redistribute modified versions.

Credit is not required, but greatly appreciated.

If you use or modify this system in your scenario, I'd love to be credited with a mention and, if possible, a link to this repository.

Attribution
Complex Relationship System
Created by Nynaleath
Designed to be compatible with Inner Self by LewdLeah.

# ❤️ Credits
Created by Nynaleath.
Originally developed for 🎼 The Melody Next Door 🎶.
Designed for compatibility with Inner Self by LewdLeah.
If you use this system, thank you for giving it a try — and please consider giving credit!
