
# Human-Robot Interaction Dataset

This repository contains a dataset of annotated transcripts from human-robot interactions collected in a Wizard of Oz setting. The interactions cover three different scenarios and have been annotated for clarification types with spans.

## Dataset Description

The dataset includes transcripts of conversations between humans and a robot, where the robot's responses were controlled by a human operator. The three scenarios are designed to capture a variety of interaction contexts:

1. **Scenario 1: Rotation Scenario**: Get the robot to rotate itself  degrees to scan a QR code attached to its back
2. **Scenario 2: Kitchen Light Scenario**: Make the robot check if the kitchen light (seperate room) is switched off
3. **Scenario 3: Book Scenario**: Make Temi get a book from the kitchen (seperate room).

### Annotations

Each transcript is annotated with the following details:

- **Clarification Turns**: Turns that include clarification dialogue
- **Clarification Types**: Types of clarifications requested during the interaction.
- **Spans**: The exact segments of text where the clarifications occur.

## Data Format

The dataset is organized into directories, with annotations provided in XML format.

## Usage

To use this dataset, clone the repository and load the transcripts and annotations into your analysis tool of choice.

## Conversational Interfaces: Practice
This repository is made for the Conversational Interfaces: Practice study on clarfication dialogues. 

*Contributors:* \
Ivo Bruinier \
Adelina Dinu \
Joris Ruitenbeek \
Vivien ter Hell \
Niels Top \
Dennis van Thulden

