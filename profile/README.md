## Hi there 👋

# Welcome To Eduteam 6 on the GADS Program. 
---

## Meet The Team
- [Confidence Bassey](https://github.com/confidence-bassey) - Project Lead / Android Developer
- [James Amattey](https://github.com/jamattey) - Product Manager / GADS Google Cloud Track




## Problem Statement

### Background

Preparing for a spelling competition is a mundane task for students. Studying and preparing for a quiz with 4000 potential questions sets the bar very high. 

For the sake of the competition, a high bar is important and helpful to increase the credibility of the competition. However, the spelling bee has far more advantages for each participant and hence everyone should be given a chance to participate.

---

### The Goal

- To develop a solution that allows students to have a repository of information about the words they are studying. 
- Allow students to tackle words in stages
- Gamify the learning experience so that it is fun for students
- Provide any relevant information about words to students
- Track students spelling and word arrangement and identify areas for development.

---

### The Reality

Currently, students print out multiple pages of 4000 words usually in alphabetical order. This makes it difficult to track the progress made by a student or help the student adjust to new words and trick questions. 

### The Consequence

Students are unable to track their progress with words. Also, students waste a lot of paper resources in the process of printing and reprinting.

---

### Requirements

- The app should generate words for the students
- Students can learn according to their levels, starting with basic words and ending with complex words
- Students can view words they had wrong and repractice them
- Student can take a regular practice or play a word game.

---

# Key Features & Scope

## Random Word Generator

### Description:

The random word generator is a service instigated by an API that generates random words from a word service such as a dictionary. 

This provides the origin of the word, the meaning, the use of the word in a sentence as well as any other derivatives of the word. 

---

### Goal:

The goal is to prevent students from printing several pages of words. 

To give students information about the words under study in one go. 

---

### Usecase:

- A student starts a practice session 

- The system prints a random word from the repository but hides a few letters in random positions. 

- Using text to speech, the system pronounces the word and defines it. 

- The text to speech service will also read out the origin, definition and sentence use of the word.

---

## Spelling and Correction

### Description:

The user can activate their device microphone and spell the word based on the information received.

---

### Goal:

- Allow the student to spell the word under a stipulated time.
- By only showing a few letters, students are able to identify the words by picturing the positioning of various letters.

---

### Use Case:

- The student clicks on microphone icon and spells the word
- The app records the spelling and compares with the original word
- The system determines if the word is correct or not.

---

## Out Of Scope

- Student leaderboard to allow students to study together
- Reverse Word game, that defines the word and ask for a spelling, origin or pronunciation

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
