# Starter prompts

Three prompts to run at your own vault, in order.

**Run one at a time.** Wait for the answer, read it, and check what changed in Obsidian before you start the next one.

---

## Prompt 1: get to know your vault

This one only reads. It changes nothing, which makes it a safe first move with any new tool.

```text
Look through my whole vault and tell me how it is organised. List the folders, say what each one seems to be for, and tell me which ones are empty. Do not create or change any files.
```

**Then check:** does its description match what you see in Obsidian's sidebar?

---

## Prompt 2: add your own vendor courses

Now it writes. Notice that you are asking it to copy a pattern that already exists, rather than inventing one. The pattern is in `Course-Files`, and the new notes go in **your own vault**, not in `Course-Files`.

```text
Read Course-Files/Vendor-Courses/README.md and one of the course notes in that folder, so you can see the layout. Then, in my own vault, add a folder and a note for each of these courses in Programme/Vendor-Courses, using the same layout. If that folder does not exist yet, create it. Do not change anything inside Course-Files.

- VC-25 Supabase Fundamentals. Provider: Supabase (https://supabase.com/docs). Do it between 20 October and 3 November 2026. Due before Session 10.
- VC-24 Foundation: Intro to LangGraph (Python). Provider: LangChain Academy (https://academy.langchain.com). Do it between 15 December 2026 and 12 January 2027. Due before Session 14.
- VC-08 Introduction to Generative AI (5-course path). Provider: Google Skills (https://www.skills.google). Do it between 26 January and 9 February 2027. Due before Session 16.

Then list every file you created or changed.
```

**Then check:** open one of the new notes in Obsidian. Does it match the layout of the notes in `Course-Files`? Is it in your own vault, under `Programme`, and not inside `Course-Files`?

---

## Prompt 3: find something across your notes

This is the one that shows you why the folder matters. It has to read several notes and join them up.

```text
Read every note in my vault and answer this: if I wanted to explain to someone what this vault is for and how I am meant to use it, what would I tell them? Point me at which notes you got each part of the answer from.
```

**Then check:** did it use more than one note to build the answer?

---

## If a prompt does something you did not expect

That is what step 7 is for. Once your work is committed and pushed, you can always look at exactly what changed and put it back.
