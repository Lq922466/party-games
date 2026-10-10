# PASS / Party Games

[中文](README.zh.md) · [English](README.en.md) · [Español](README.es.md) · [Project home](README.md)

**INNNX. · One phone. Everyone plays.**

PASS brings questions, action challenges, random player selection and timed answers into one Flutter party-game collection. Gather around, choose a game, follow its prompts and pass the phone to the next player. The phone supplies the prompts and round structure; the conversation and reactions come from the people playing together.

## English HOME preview

<a href="screenshots/home-en.png"><img src="screenshots/home-en.png" width="360" alt="PASS complete English scrolling home screen with nine game entries" /></a>

This is a complete scrolling home preview stitched from existing Android UI captures, rather than a single screen. It shows the English game names and instructions. Click to view the full image. The Chinese and Spanish pages each show their corresponding home interface.

## Home design and navigation

A dark background, fluorescent colors, graffiti illustrations and numbered cards organize the collection. Lips, a bomb, a pointing hand, a glass, lightning, a cake, an eye and flames distinguish the entries. Two larger cards highlight Truth or Dare and Number Bomb; the remaining cards make it easy to choose a different activity. Scroll down for Mix Mode and the remove-ads entry. The upper-right control opens settings.

## All nine game entries

| Entry | How a round works | What it brings to the group |
| --- | --- | --- |
| 01 Truth or Dare | Add players, spin to choose the next person, select Truth or Dare, answer or complete the challenge, then pass the phone and spin again. | Questions and action challenges within one turn-taking flow. |
| 02 Number Bomb | A hidden number is the bomb. Take turns choosing numbers. Safe guesses narrow the range; hitting the bomb brings up a random dare. | Suspense as the possible range gets smaller. |
| 03 Most Likely To | Read the prompt, count down three, two, one, and point at the person who best fits it. Continue with the next question. | Compare impressions and explain your choices. |
| 04 Never Have I Ever | Read the statement and honestly answer whether you have done it. Move on to the next statement. | Share experiences and discover things in common. |
| 05 5 Second Challenge | Read the challenge, start the timer and answer within five seconds. Pass the phone for the next round. | Quick thinking under countdown pressure. |
| 06 Birthday Party | Choose the person being celebrated, read the birthday prompts and have everyone join in the next challenge. | Activities centered on the birthday guest. |
| 07 Truth | Open the Truth-only flow directly and take turns answering prompts. | A question-focused option for conversation and personal stories. |
| 08 Dare | Open the Dare-only flow directly and continue through action challenges. | A challenge-focused option to get the group involved. |
| 09 Mix Mode | Choose Chill or Wild. The game selects challenges at random; follow the prompt and keep passing the phone. | Variety without choosing a new activity every round. |

These descriptions follow the existing in-app help and interface implementation. The actual prompt files are private. Skip anything you do not want to answer or perform, and respect the other players' boundaries.

## Starting a session

1. Choose a mode from the home screen that suits your group's mood.
2. Follow that mode's setup, such as adding players or choosing the birthday guest. Use the wheel when random player selection is needed.
3. Read the mode's instructions and start answering, challenging or timing.
4. Complete or skip the current prompt, pass the phone and continue with another round.

## Languages, audio and offline play

The application has Chinese, English and Spanish interfaces and local prompt libraries. Local components manage language selection, player lists, some preferences and audio options. Background music and sound effects provide feedback and rhythm; related options are available in settings.

Core prompt content works offline. Ad-related features require a network connection, and the remove-ads entry uses purchase integration. The €3.99 shown in this capture is interface content from that version; it is not a verified current store price or proof that purchasing is live.

## Implementation and current status

Built with Flutter, Dart, Flutter localization, SharedPreferences and audioplayers, with Google Mobile Ads and in_app_purchase integrations. The existing project includes Android debug builds and test files. This documentation update uses existing captures and does not revalidate a distribution build. An iOS project exists, but its running state has not been confirmed here.

There is currently no public playable package. A future package needs target-device testing and redistribution checks before publication through GitHub Releases. Automatically generated Source code archives contain only this showcase's documentation and images.

[Playable release guide](docs/PLAYABLE-RELEASE.md)

## Public scope

This repository publishes the presentation and UI previews. Application source code remains private, together with prompt files, signing materials, development logs and local configuration.
