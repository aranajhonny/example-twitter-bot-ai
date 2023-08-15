# Membrane Tweet Bot

This is a program that uses the Membrane to create a Twitter bot that generates and tweets out lesser-known words along with their definitions, pronunciations, and example sentences.

## How It Works

The AI responds with a message containing the generated word and related information. using GPT-3.5-turbo.
The program then uses the `twitter` driver to post a tweet on Twitter.

## How to Use

Paste the following URL in your browser to open the directory inside the Membrane VSCode Extension.

vscode://membrane.membrane/directory/example-twitter-bot-ai

Run `:tweet` action or add schedule to tweet at regular intervals, like every 30 minutes. use `0 */30 * * * *`.