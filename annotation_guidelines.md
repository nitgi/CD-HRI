# Annotation Guidelines for Clarification Types in Human-Robot Interaction (HRI)

This guideline provides instructions for annotating turns in conversation with clarification turns, types, and spans. The annotation task should be performed first individually and then in pairs for adjudication. The results of the adjudication will be the gold standard dataset to be presented as the final product.

Annotate the transcripts using the Google Sheets file provided in the Conversational Interface: Practice drive. There are three columns: start (in ms), speaker, text, clarification turn, clarification type, and classification span. Put in your annotations accordingly!

*(Keep in mind that turns between facilitator and participants are not to be annotated)*

## Part I: Clarification Turns

### Clarification Turns Label Definitions

- **i:** The turn initiates a clarification dialogue.
- **f:** The turn provides additional information or response as part of an ongoing clarification dialogue.

### Annotation Process for Clarification Turns

1. Read each turn carefully and try to understand the overall sentiment expressed.
2. Determine if the turn is part of a clarification dialogue:
   - If the turn starts a clarification dialogue, label the turn with an **i**.
   - If the turn is part of a clarification dialogue but a follow-up of an initiation, label the turn with an **f**.

You can stop annotating a follow-up turn when it's clear the reason for the clarification request has been resolved (e.g., "sure...") or when a new initiation begins.

## Part II: Clarification Types

### Clarification Types Label Definitions and Detailed Guidelines

#### 1. Acoustic Issue
**Definition:** Temi did not hear or process the request correctly.
- **How to Identify:** Look for turns where Temi indicates a failure to understand due to hearing or processing issues. Common indicators include phrases like "I did not understand," "I did not hear," or "Can you speak louder?"

#### 2. Confirmation Before Action
**Definition:** Temi asks for confirmation before taking an action.
- **How to Identify:** Look for turns where Temi seeks verification before executing a command. Common indicators include phrases like "Do you want me to," "Should I," or "Would you like me to."

#### 3. Confirmation After Action
**Definition:** Temi asks for confirmation after taking an action.
- **How to Identify:** Look for turns where Temi seeks validation after completing a task. Common indicators include phrases like "Did I do this right?" or "Is this correct?"

#### 4. Evaluating Intention
**Definition:** Temi asks why it has to do a specific action.
- **How to Identify:** Look for turns where Temi inquires about the rationale behind a request. Common indicators include phrases like "Why do you want me to" or "What is the reason for."

#### 5. Paraphrasing
**Definition:** Temi did not understand the participant's request and rephrased it.
- **How to Identify:** Look for turns where Temi restates the participant’s request in different words to ensure understanding. Common indicators include phrases like "Do you mean," or "Are you asking if."

#### 6. Request for Repetition
**Definition:** Temi asks the participant to repeat their request.
- **How to Identify:** Look for turns where Temi explicitly asks the participant to say something again. Common indicators include phrases like "Can you repeat that," or "Could you say that again?"

#### 7. Requesting More Information
**Definition:** Temi did not understand the meaning or context of the request and asks for more details.
- **How to Identify:** Look for turns where Temi seeks additional information to clarify a vague or ambiguous request. Common indicators include phrases like "Do you mean," or "Are you referring to."

Annotate the turn with the appropriate type label according to the definitions and use the same label for its follow-up turns (See Part I).

## Part III: Clarification Span

- Identify and mark the specific span within the turn that indicates clarification.
- Ensure the span is accurate and precisely reflects the clarification part of the turn.
- Exclude politeness markers if they appear at the beginning or end of the clarification dialogue. Actions of Temi can also be excluded except if they appear within the clarification dialogue.

### Example

- **Turn:** "Please can you repeat that?"
- **Annotation:** Clarification: Request for Repetition
- **Span:** "Can you repeat that?"

## Part IV: Pair Adjudication

1. Discuss your annotations with your partner to reach a consensus.
2. Resolve any discrepancies to ensure consistency.
3. The adjudicated results will form the gold standard dataset.

## Additional Guidelines

- **Consistency:** Strive for consistency in your annotations. Discuss any discrepancies during adjudication.
- **Clarification Scope:** Focus on the clarification aspect of the turn, even if the turn contains other information.
- **Precision:** Ensure the span accurately captures the clarification part of the turn.
