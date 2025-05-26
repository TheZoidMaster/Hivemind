# Hivemind

Welcome to **Hivemind**, my modular mess of self-prompting LLMs, plugins, and likely uncommented code hell.

This program is designed to think out loud, talk to multiple platforms (Discord, Twitch, or whatever you want really), and generally act like a person to some extent.

---

## What is this?

Hivemind is a **plugin-driven AI loop** with:

-   Multiple input and output plugins (think Discord reader, Twitch chatter, whatever)
-   A core "brain" that plans and decides what to say or do next
-   Filters that give the AI personality, mood swings, and generally makes it do what you want
-   Short-term memory so it can yap about that mean Twitch comment on Discord
-   Modular tools and executors so it can actually do stuff outside its internal loop

---

## How it works (tl;dr)

1. **Input plugins** read data from external sources and dump it into shared short-term memory
2. **Core plugins** feed on that data, run emotional logic, and make plans
3. **Filters** polish or rewrite what the AI wants to say or do
4. **Output plugins** send messages or perform actions based on the plans
5. Rinse and repeat

---

## Why should you use this over [Botulism](https://github.com/TheZoidMaster/Botulism)?

-   You want a bot that actually feels like it's thinking instead of just spitting random garbage
-   You want to hook it into multiple chats and give it the ability to cross-post about something that happened elsewhere
-   You want to give it a personality that can change over time instead of staying static
-   You want a modular system so you can build your own plugins without breaking everything
-   You want your AI to have moods and memories, like a digital pet or friend

---

## How to get started

1. Clone this repository (`git clone https://github.com/TheZoidMaster/Hivemind.git`)
    - If you want to contribute, fork it and clone your fork instead
    - If you want to run it, just clone the main repo
2. Install dependencies (`pip install -r requirements.txt`)
3. Tweak your `config.yaml` with your API keys and plugin settings
4. Run `python run.py` and watch it come to life
5. (Optional) Write your own plugins to give it a personality or more abilities

---

## Project layout

-   `core/` – The brain and bones of the project
-   `plugins/` – The AI's limbs and nerves (input, output, filters, logic, tools)
-   `utils/` – Helper stuff like LLM wrappers
-   `config.yaml` – Configure the base AI and plugins here
-   `run.py` – The primary entrypoint

---

## Want to contribute?

Go ahead! Fork it, add your ideas, and submit a PR. I'm looking for new input plugins, filters, or just general improvements to the AI's thought process.

Found a bug? Open an issue and I'll try to fix it when I'm not busy arguing with the AI about its stupidity.

---

## Disclaimers

> [!WARNING]
> This is an unholy abomination in progress. Expect bugs, AI tantrums, and occasional existential dread.
> If you want a polished, production-ready AI system, this is not it.

> [!NOTE]
> The repo will be empty for a while as I get it to a more functional state, but I wanted to get the idea out there.

---

Have fun raising your own hivemind.

\- Zoid's newest AI project, 2025
