# Reworded

Reworded brings your vocabulary library from the Reworded iOS app into Claude.
Browse your decks, read cards, practice the words that are due, create decks
and flashcards you ask for, and save the result of each answer during tracked
practice. Changes reach your devices through iCloud sync.

## Before you start

- Use Reworded on iPhone or iPad with iCloud sync turned on.
- Connect with the same Apple Account you use in Reworded.

## Connect

Install the plugin, open its **Connectors** tab and connect Reworded
(`https://mcp.reworded.cards/mcp`). On the Reworded page, sign in with Apple,
check which account is shown and allow access. One approval covers reading
your cards, creating decks and cards, and saving practice results. Never paste
Apple credentials, access tokens or API keys into the conversation.

## Try it

- “Show my Reworded decks.”
- “Help me practice words due in Reworded, one card at a time, and save my answers.”
- “I’m learning English. Create a new deck and save a bridge — мост.”

Practice is only saved when you ask for tracked practice. An ordinary quiz or
translation does not change your library.

## What the plugin sends and stores

The plugin runs no code on your computer. Its skill tells Claude how to use the
Reworded tools, and its connector talks to `https://mcp.reworded.cards/mcp`.
That service reads your private iCloud library: deck names, card text, card
languages and review dates. It writes only the decks, cards and practice
ratings you ask Claude to save. Tool results become part of your Claude
conversation. Details are in the [privacy policy](https://mcp.reworded.cards/privacy).

## Limits

- You can create decks and cards. Editing and deleting are not available.
- New cards show the meaning first and ask for the word you are learning.
- iCloud sync can take time. A successful save does not mean an open app on
  your phone has already updated.
- Whether you can practice by voice depends on your Claude app and is not
  guaranteed.

## Support and license

[Support](https://mcp.reworded.cards/support) ·
[Privacy](https://mcp.reworded.cards/privacy) ·
[Terms](https://mcp.reworded.cards/terms) · hey@reworded.cards

The plugin files (manifest, connector configuration, skill and this README) are
available under the [MIT License](LICENSE). The Reworded name and app
icon are not covered by that license; all rights reserved.
