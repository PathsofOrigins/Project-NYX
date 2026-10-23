# Project NYX

NYX is an experimental AI project whose main objective is
to become a game tester.

The project is being developed using Godot, GDScript, and
C++. Its neural language model is trained from scratch,
without using a pretrained language model.

## Current development

NYX currently includes:

- Experimental neural language-model training.
- Local text datasets and internet-text collection.
- Background training with saved checkpoints.
- A cloud component for uploading model weights.
- Separate interfaces for conversation and learning.

NYX is still an early prototype. Reliable conversation,
gameplay understanding, and autonomous game testing are
development goals, not established capabilities.

## Intended game-testing capabilities

The long-term goal is for NYX to:

- Understand gameplay instructions and player feedback.
- Identify and describe bugs and unexpected behaviour.
- Understand gaming terminology and cooperative dialogue.
- Recognise frustration, insults, sarcasm, and informal
  language in gaming contexts.
- Communicate useful observations about game tests.

## Proposed Reddit integration

Reddit access is proposed and is not currently enabled
in NYX's general web collector.

I am seeking approval to retrieve selected public posts
and comments through an authorised API integration.

The intended use includes training NYX's own neural
language model on grammar, conversational language,
gaming terminology, and descriptions of player experiences.

API access and permission to train on Reddit content are
both being requested. Neither permission is assumed.

The proposed integration is read-only. It would not post,
comment, vote, send messages, or access private content.

The initial proposed scope is r/gamedev and r/gaming,
subject to Reddit's approval.

Any implementation would follow the approved access scope,
request limits, and applicable data-handling requirements.
Permission to upload model weights trained using Reddit
content would also need clarification.

## Project budget

NYX is currently a personal development project with a
zero-cost hosting and data-access budget. Reddit access
would proceed only if suitable permission is available
without payment.

## Repository status

This repository initially provides a project overview.
Relevant source code may be added as development continues.
No Reddit integration is claimed to be implemented or
approved.
