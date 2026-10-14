# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Ali Faiz Alanzi] |
| **Student ID** | [446050238] |
| **University Email** | [446050238]@std.psau.edu.sa |
| **GitHub Username** | [your-github-AliFaiz1236] |
| **Repository Link** | [ |https://github.com/AliFaiz1236/OS-Assignment1-Ali-Faiz ]
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `https://youtu.be/d8kcIOm5dG8` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [Oct 7, 2026, 7 PM]
•• What I did: Project setup and student ID configuration.
• Details: Forked the repository, set my student ID (446050238) in SchedulerSimulation.java, and read the README.
• Challenges: Setting up the workspace in VS Code.
• Solution: Configured project folders correctly.

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [Oct 7 , 7pm ]
• What I did: Project setup and student ID configuration.
• Details: Forked the repository, set my student ID (446050238) in SchedulerSimulation.java, and read the README.
• Challenges: Setting up the workspace in VS Code.
• Solution: Configured project folders correctly.
**Time spent**: 2  hours

---

### Entry 2 - [Oct8 , 7 pm]
• What I did: Analyzed queue structures and process scheduling.
• Details: Reviewed how threads and processes interact in the ready queue.
• Challenges: Understanding preemptive thread states.
• Solution: Traced code flow with test prints.
• Time spent: 2.5 hours.

---

### Entry 3 - [Oct 9 , 5 pm ]

• What I did: Implemented Feature 1 (Process Priority).
• Details: Updated queue sorting logic based on priority and arrival time.
• Challenges: Handling priority tie-breakers.
• Solution: Added secondary sorting by arrival timestamp.
• Time spent: 3.5 hours.
---

### Entry 4 - [Oct 10 , 3 pm]
• What I data / did: Implemented Feature 2 (Context Switch Counter).
• Details: Added counters and logging for thread context switches.
• Challenges: Differentiating quantum expiration from normal exits.
• Solution: Added boundary checks during execution.
• Time spent: 3 hours.

---

### Entry 5 - [Oct 10 , 6 pm]
What I did: Implemented Feature 3 (Waiting Time Tracking).
• Details: Calculated dynamic waiting times and formatted the summary table.
• Challenges: Console column alignment.
• Solution: Used Java printf formatting.
• Time spent: 3 hours.

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[Thread vs Process
A process represents an independent execution environment with its own isolated memory space, whereas a thread is a smaller lightweight unit of execution that exists within a process and shares its memory heap and resources. We used Java threads in this assignment instead of separate system processes because threads have significantly lower creation overhead and allow fast, efficient communication through shared memory structures. Specifically, in SchedulerSimulation.java, we establish this by calling new Thread(process) inside the addProcessToQueue() method, where multiple simulated processes run concurrently as distinct threads under the same Java application process. This design enables lightweight context switching and shared queue management without heavy inter-process communication overhead..]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Ready Queue Behavior
In Round-Robin scheduling, when a process exhausts its allocated time quantum before finishing its total burst time, it is interrupted and re-queued at the back of the ready queue to await its next turn. For example, in my program output, process P3 had a large burst time and was repeatedly added back to the ready queue multiple times (specifically 3 times) before its remaining burst reached zero. Re-queueing is crucial for fairness because it prevents long-running processes from monopolizing the CPU and ensures that all other processes get equal, predictable shares of processor time.
Example from my output:
[Timestamp: 145ms] Process P3 exceeded time quantum, re-added to ready queue. Current queue size: 2
Explanation of example: This snippet illustrates that P3 utilized its full time quantum slice, was paused by the scheduler, and safely pushed back to the tail of the ready queue so other waiting processes could execute.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[Thread Lifecycle
1. New: A process is in the New state immediately after instantiation when new Thread(process) is invoked inside addProcessToQueue() before it starts execution.
2. Runnable: P1 enters the Runnable state once thread.start() is called by the scheduler loop, making it eligible for CPU scheduling and queue allocation.
3. Running: P1 enters the Running state when the scheduler selects it from the ready queue and its run() method actively executes on the CPU core.
4. Waiting: P1 enters the Waiting state when it executes Thread.sleep() to simulate I/O operations or when the main thread invokes thread.join() to wait for thread completion.
5. Terminated: P1 reaches the Terminated state after its execution logic finishes completely and its run() method exits.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Real-World Applications
• Example 1 (operating-system level): CPU Scheduling in Desktop Operating Systems (Windows/Linux)
• Description: The operating system kernel manages all active applications by allocating slices of CPU time using priority-based Round-Robin algorithms.
• Why Round-Robin works well here: It guarantees fairness and high responsiveness, ensuring no single background application locks up the entire system processor.
• Example 2: Multi-player Game Server Tick Management
• Description: A multiplayer game server processes player actions and game world updates sequentially in tight iterative rounds (ticks).
• Why Round-Robin works well here: It maintains absolute predictability and fairness among all connected clients so that network packet processing is distributed evenly without noticeable lag spikes.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[Thread vs Process
A process represents an independent execution environment with its own isolated memory space, whereas a thread is a smaller lightweight unit of execution that exists within a process and shares its memory heap and resources. We used Java threads in this assignment instead of separate system processes because threads have significantly lower creation overhead and allow fast, efficient communication through shared memory structures. Specifically, in SchedulerSimulation.java, we establish this by calling new Thread(process) inside the addProcessToQueue() method, where multiple simulated processes run concurrently as distinct threads under the same Java application process. This design enables lightweight context switching and shared queue management without heavy inter-process communication overhead.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[Ready Queue Behavior
In Round-Robin scheduling, when a process exhausts its allocated time quantum before finishing its total burst time, it is interrupted and re-queued at the back of the ready queue to await its next turn. For example, in my program output, process P3 had a large burst time and was repeatedly added back to the ready queue multiple times (specifically 3 times) before its remaining burst reached zero. Re-queueing is crucial for fairness because it prevents long-running processes from monopolizing the CPU and ensures that all other processes get equal, predictable shares of processor time.]

Example from my output: [Timestamp: 145ms] Process P3 exceeded time quantum, re-added to ready queue. Current queue size: 2
Explanation of example: This snippet illustrates that P3 utilized its full time quantum slice, was paused by the scheduler, and safely pushed back to the tail of the ready queue so other waiting processes could execute.
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state )
Thread Lifecycle
1. New: A process is in the New state immediately after instantiation when new Thread(process) is invoked inside addProcessToQueue() before it starts execution.
2. Runnable: P1 enters the Runnable state once thread.start() is called by the scheduler loop, making it eligible for CPU scheduling and queue allocation.
3. Running: P1 enters the Running state when the scheduler selects it from the ready queue and its run() method actively executes on the CPU core.
4. Waiting: P1 enters the Waiting state when it executes Thread.sleep() to simulate I/O operations or when the main thread invokes thread.join() to wait for thread completion.
5. Terminated: P1 reaches the Terminated state after its execution logic finishes completely and its run() method exits.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

Real-World Applications
• Example 1 (operating-system level): CPU Scheduling in Desktop Operating Systems (Windows/Linux)
• Description: The operating system kernel manages all active applications by allocating slices of CPU time using priority-based Round-Robin algorithms.
• Why Round-Robin works well here: It guarantees fairness and high responsiveness, ensuring no single background application locks up the entire system processor.
• Example 2: Multi-player Game Server Tick Management
• Description: A multiplayer game server processes player actions and game world updates sequentially in tight iterative rounds (ticks).
• Why Round-Robin works well here: It maintains absolute predictability and fairness among all connected clients so that network packet processing is distributed evenly without noticeable lag spikes.

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

## Summary

**Key concepts I understood through these questions:**
1.
2.
3.

**Concepts I need to study more:**
1.
2.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
