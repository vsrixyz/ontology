# The Road To Information Architecture

## An ontology toolkit

V. Sri\
Content Designer\
2024-Q2

---

| Contents                  |                         |
| ------------------------- | ----------------------- |
| [Discovery](#/2)          | Collecting the elements |
| [Concept Mapping](#/9)    | Painting a picture      |
| [Product Narrative](#/15) | Writing a story         |
| [Terminology](#/19)       | Defining the terms      |


---

# Discovery

## Collecting the elements

Collect all the concepts that need definition in a a single place. Features that need names, language that's unclear, or anything else that's confusing.

---

## Start here

1. Create a board in Miro, Figjam, or any other [[collaborative whiteboard software]]. Or use this Figjam template.
2. Identify the participants and name a single decision maker for the Mapping, Narrative, and Terminology phases. (The content designer is generally the decision maker for Terminology.)
3. Spend 3 days adding post-it notes the board by answering the *kickstart questions*. (This can be done asynchronously.)

---

## Kickstart questions

- Who needs to be involved at each phase? More isn't always better. Also, name a sole decision maker for each phase. This person unblocks impasses.
- Spend 10 minutes and create a post-it for the key concepts of your experience. Think nouns. What do people touch, see, interact with? Limit one idea per post-it.
- Spend 10 more minutes but this time think verbs. What are people doing or trying to do? One idea per post-it.
- Spend 10 more minutes sorting. Which concepts are potentially confusing? Copy the post-its into one (or more) of the three types of confusing concepts.

---

## Three types of confusing concepts

| Type         | Description                                                                                                                                                                                              | Example                                                                                                                                                                                                                                 |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collision    | When the same terminology is used for two concepts                                                                                                                                                       | `Huddle` has a specific meaning in Slack. If you called another feature "Huddle" that would be confusing.                                                                                                                               |
| Fuzzy label  | The reverse of collision. Where the same concept is referred to in multiple ways.                                                                                                                        | This is common. In Zendesk, a `ticket comment` is also referred to as a `reply` or a `message`.                                                                                                                                         |
| Dirty magnet | A kind of fuzzy label. It generally means a design element or feature that tends to attract mess or clutter over time, due to a lack of constraints or guidance on how to organize information properly. | Terms like `AI` and`machine learning` are being overused without being properly defined. <br><br>In the UI sense, a desktop or home screen without predefined structures where users indiscriminately place files, leading to disarray. |

---

## Concepts vs terminology

At this stage of the process, we are focusing on concepts, not terminology. Don't worry if the current label doesn't sit well with you. You will have a chance to change it later.

| Concept                | Terminology    | Branded terminology        |
| ---------------------- | -------------- | -------------------------- |
| The idea, the meaning  | The label      | The brand or catchphrase   |
| Conceptual             | Functional     | Perceptual                 |
| *Homo Sapiens Sapiens* | George Clooney | "World's Sexiest Man 1997" |
| Text editor            | Composer       | RoboComposer               |

Sometimes the concept and terminology end up being the same, but they don't have to be.

---

## Things to avoid

- Don't do a full audit of the product. Focus on the concepts that are most confusing.
- Don't erase anything or santitize your boards. It's a kitchen sink, it's meant to be messy!
- Don't worry about knowing the answers; this is about generating questions and finding your blind spots.

---

# Concept mapping

## Painting a picture

Visually arrange your concepts to show how they are connected. There are lots of ways to do this, but try to keep it *low-fidelity* and simple.

---

## Start here

1. In another part of your whiteboard, answer the *clustering questions* to generate fodder for your concept maps.
2. Choose a concept map type and start arranging your clusters. (You can change your mind later, or you can make multiple maps.)
3. Draw arrows, group concepts, and annotate relationships. It's OK to be messy at first.

---

## Clustering questions

1. What concepts (verbs, nouns) etc go together? Move these together into clusters.
2. Physically separate unrelated clusters.
3. See if you can label clusters by theme or by *jobs to be done*.

---

## Types of concept map

Scroll down to see examples of concept maps.

--

![](https://i.imgur.com/99AOIwq.png)
--

![](https://i.imgur.com/7qlSFj2.png)

--

![](https://i.imgur.com/MuT22FL.png)

--
![](https://i.imgur.com/glIwt89.png)

--
 ![](https://i.imgur.com/sgDEIDE.png)

--

![](https://i.imgur.com/UgeqHnu.png)

--

![](https://i.imgur.com/BuZRCHT.png)

--

![](https://i.imgur.com/ln92LG9.jpeg)

---

## Things to avoid

- Your concept map does not have to include edge cases
- Your concept map doesn't have to tell a linear story
- Your concept map does not need to be pretty or 100% accurate

---

# Product Narrative

## Write the story

Now that they have more structure, your concepts into a story format. For the first time, you will walk through your concepts from the perspective of the user.

---

## Start here

- In a sense, this is your first prototype of the experience. Write for someone without context
- Use short clear sentences, unpack internal jargon, and walk through concepts in the order they are encountered 
- Explain every concept when it is introduced and literally highlight any key concepts

---

## This is the screenplay

- Explain everything in words (without the user of images or mockups) much like a screenplay
- Your narrative is meant to inform the visual design, rather than the other way around. A well-written experience narrative will enable different design explorations.
- Unlike a concept map, the sequence of events and concepts matters here.

| Concept map |     | Narrative  |
| ----------- | --- | ---------- |
| Visual      |     | Written    |
| Non-linear  |     | Linear     |
| Exploratory |     | Concise    |
| Genotype    |     | Phentotype |

---

## Things to avoid

- Focus on the common scenarios, don't worry about edge cases
- Avoid product jargon, because it often needs to be explained
- Don't link out things. Explain what you need to in the narrative. Keep it short, but don't leave anything out. (Yes, this is hard!)

---

# Terminology

## Defining the terms

It's easier to title a book after you've written a chunk of it. Now it's time to draw some lines in the sand and create formal definitions for your concepts. This terminology will help keep the experience consistent.

---

## Start here

- Synthesize the mapping and narrative work into a single document listing all terms relevant to your product area
- Entries consist of a term, a short definition, and examples. Keep it simple, but make every word tell.
- Most important: choose a single human to author the document and make the final decision on terminology. Do not leave this up to an artificial intelligence.

 ---

## Clarity is the ultimate goal

- Use the user's language wherever possible
- Help people understand what a thing, and what it is not
- You're writing a reference document, not a listicle. It won't be entertaining, and it probably not be *instantly* understood
- Keep personal opinions and bias out of it ("I don't like the word 'task'")

---

## This is a living document

- Every glossary must be maintained, make sure you're resourced for the long-term effort
- The product owner should definte a process to add and update this glossary that's fair and efficient
- Changing a definition should be 3X harder than adding a new one

---

# Glossary

| Terminology  | Definition                                                                                                                                                                                                                       | Example                                                                                                                                                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Affordance   | An aspect of the design that suggests how an element can be used, often perceived intuitively by the user. It's a quality that signals functions to users, guiding them towards the correct action without explicit instruction. | A 3D effect on a 'Submit' button in a form interface implies it can be pressed. Users understand they can interact with it by clicking or tapping.                                                                              |
| Collision    | When the same terminology is used for two concepts                                                                                                                                                                               | `Huddle` has a specific meaning in Slack. If you called another feature "Huddle" that would be confusing.                                                                                                                       |
| Concept      | A general idea that represents a group of related phenomena, forming the basis for a product, service, or system in design.                                                                                                      | The concept of a "virtual meeting room" in teleconferencing software that simulates an in-person meeting space.                                                                                                                 |
| Dirty magnet | A kind of fuzzy label. It generally means a design element or feature that tends to attract user-generated mess or clutter over time, often due to a lack of constraints or guidance on how to organize information properly.    | Terms like `AI` and`machine learning` are being overused without being properly defined. Or a desktop or home screen without predefined structures where users indiscriminately place files and app icons, leading to disarray. |
| Fuzzy label  | The reverse of collision. Where the same concept is referred to in multiple ways.                                                                                                                                                | This is common. In Zendesk, a `ticket comment` is also referred to as a `reply` or a `message`.                                                                                                                                 |
| Glossary     | A list or collection of terms and their definitions, often arranged alphabetically and included in academic papers, technical documentation, or specialized texts.                                                               | A section at the end of a user manual that explains the specific technical terms used throughout the document.                                                                                                                  |
| Low-fidelity | A type of prototype that is simple and often quick to create, lacking detail and not fully functional, but used to explore, present and validate concepts during the early stages of the design process.                         | A hand-drawn sketch of an application interface that outlines basic layout and UI elements without detailed graphics, color, or interactivity, used for initial brainstorming or testing.                                       |
| Terminology  | The set of technical or special words and phrases used in a particular context, industry, profession, or field.                                                                                                                  | In UI design, terms like "breadcrumbs," "modal," "accordion," and "toggle" are part of design terminology.                                                                                                                      |
|              |                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                 |
|              |                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                 |
|              |                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                 |
|              |                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                 |
