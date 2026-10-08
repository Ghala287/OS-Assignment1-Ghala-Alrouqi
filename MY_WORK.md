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
| **Full Name** | [Ghala Alotaibi] |
| **Student ID** | [446051393] |
| **University Email** | [446051393]@std.psau.edu.sa |
| **GitHub Username** | [Ghala287] |
| **Repository Link** | [Paste your repository link here] |
 
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
| 7 | Video link | `Docs: Added demo video link` |

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

Entry 1 - [October 8, 2026, 2:30 PM]

What I did: Forked the repository and set up my student ID

Details:

- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: Set my student ID: 441234567

Challenges: Had to install JDK first because javac wasn't recognized

Solution: Downloaded JDK 17 and set the PATH variable

Time spent: 30 minutes

---

## Your Development Log

### Entry 2  - [October 8, 2026, 2:30 PM]

**What I did**:
Completed the assignment tasks related to multithreading and CPU scheduling.

**Details**:

* Studied the difference between processes and threads.
* Reviewed the ready queue and Round-Robin scheduling.
* Learned about the thread lifecycle and real-world applications.
* Completed the required questions and explanations.

**Challenges**:
Understanding how threads move between different states and how Round-Robin scheduling manages CPU time.

**Solution**:
Reviewed the examples and practiced understanding the execution flow step by step.

**Time spent**: 1 hour 


---


### Entry 3 - [October 8, 2026, 4:30 PM]

**What I did**:
Completed the final review of the multithreading and CPU scheduling assignment.

**Details**:

* Reviewed the answers and explanations.
* Checked the Round-Robin examples.
* Reviewed the thread lifecycle and ready queue behavior.
* Completed the summary and reflection questions.

**Challenges**:
Making sure I understood all the concepts and explained them clearly.

**Solution**:
Reviewed the concepts again and checked each answer before completing the assignment.

**Time spent**: 50 minutes


--
### Entry 4 - [October 8, 2026, 5:00 PM]

**What I did**:
Reviewed and organized my assignment before submission.

**Details**:

* Checked all completed questions and answers.
* Reviewed the examples of Round-Robin scheduling.
* Made sure the explanations were clear and complete.
* Organized the assignment and prepared it for submission.

**Challenges**:
Finding and correcting small mistakes in the assignment.

**Solution**:
Reviewed the work carefully and corrected the mistakes before submitting.

**Time spent**: 50 minutes


---

### Entry 5 - [October 8, 2026, 5:30 PM]

**What I did**:
Completed the final check of the assignment and prepared it for submission.

**Details**:

* Reviewed the multithreading concepts.
* Checked the answers for all questions.
* Verified the Round-Robin examples and explanations.
* Completed the reflection and summary sections.

**Challenges**:
Making sure all required sections were completed correctly.

**Solution**:
Went through the assignment section by section and corrected any missing or unclear information.

**Time spent**: 50 minutes

---

### Entry 6 - [October 8, 2026, 6:00 PM]

**What I did**:
Performed a final review of my work and made sure the assignment was ready for submission.

**Details**:

* Checked the completed questions and answers.
* Reviewed the key multithreading concepts.
* Verified the examples and explanations.
* Made sure the assignment was organized properly.

**Challenges**:
Making sure there were no missing sections or mistakes.

**Solution**:
Reviewed the assignment one final time and corrected any remaining issues.

**Time spent**: 50 minutes


## Development Log Summary

**Total time spent on assignment**: 3 Days

**Most challenging part**:
Understanding the thread lifecycle, ready queue behavior, and how Round-Robin scheduling manages CPU time between processes.

**Most interesting learning**:
I found it interesting to learn how multithreading allows multiple tasks to run at the same time and how threads can improve the performance and responsiveness of applications.

**What I would do differently next time**:
Next time, I would start the assignment earlier and practice the examples before answering the questions. I would also spend more time reviewing CPU scheduling and synchronization concepts.


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

**Your Answer:** 
I learned that multithreading allows a program to perform multiple tasks at the same time. Each thread can execute a different part of the program independently. I learned that multithreading can make programs faster and more efficient, especially when there are many tasks to complete. I also learned that threads share the same memory, so they need to be managed carefully to avoid conflicts. Synchronization can be used to control access to shared resources and prevent problems. Multithreading is commonly used in applications that need to perform several operations at once, such as downloading files while using another part of the program. Overall, I learned that multithreading is an important concept for improving the performance and responsiveness of programs.


[Write your answer here.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** The most challenging part of this assignment was understanding how multiple threads work at the same time. I found it difficult to understand how threads are created and how they execute different tasks independently. Another challenging part was understanding synchronization and how to prevent conflicts when threads share resources. It also took some time to understand the difference between starting a thread and running a normal method. However, practicing the examples helped me understand the concepts better. Overall, the assignment was challenging, but it helped me improve my understanding of multithreading.


[Write your answer here.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** I overcame the challenges by reviewing the lecture materials and studying the examples carefully. I practiced creating and running threads several times to understand how they work. When I had difficulties, I checked my code and corrected the errors step by step. I also focused on understanding synchronization and how threads share resources. Practicing small examples made the concepts easier to understand. By repeating the exercises and learning from my mistakes, I became more confident with multithreading. Overall, practice and reviewing the examples helped me overcome the challenges.


[Write your answer here.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:**Multithreading can be applied in many real-world applications to perform multiple tasks at the same time. For example, a web browser can use different threads to load web pages, download files, and respond to user actions. In mobile applications, multithreading can help perform tasks in the background without freezing the user interface. It can also be used in games to handle graphics, sounds, and other tasks simultaneously. In online systems, multiple threads can process requests from different users at the same time. Multithreading is also useful in servers, where many users may access the system simultaneously. Overall, multithreading helps applications become faster, more responsive, and more efficient.


[Write your answer here.]

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

**Your Answer:** 
A process is an independent program that has its own memory and resources. A thread is a smaller unit of a process that can perform a task within the program. Threads in the same process share memory and resources, while different processes usually have separate memory spaces. Threads are generally faster and require fewer resources than processes.


[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** 
The ready queue is a list of processes or threads that are waiting to be assigned to the CPU. When a process becomes ready, it is added to the ready queue. The operating system selects a process from the queue based on the scheduling algorithm being used. After a process gets CPU time, it may finish, wait for another resource, or return to the ready queue.


[Write your answer here.]

Example from my output:
P1 completed quantum 4000ms | Overall progress: 51x
Remaining time: 3837ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 7837ms | Priority: 4

**Explanation of example:**
This example shows how Process P1 uses the CPU for a time quantum of 4000 ms. After using the CPU, P1 has 3837 ms of execution time remaining. The process then yields the CPU so that another process can use it, which causes a context switch. After that, P1 is placed back into the ready queue because it has not finished yet. Its burst time is 7837 ms, and its priority is 4. This demonstrates how a process moves between the CPU and the ready queue during execution.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** A thread lifecycle describes the different states a thread goes through during its execution. A thread starts in the **New** state and moves to the **Ready** state when it is ready to run. When the CPU assigns it time, the thread enters the **Running** state. It may then move to the **Waiting** or **Blocked** state when it needs to wait for a resource. After the resource becomes available, it returns to the **Ready** state. Finally, when the thread completes its task, it enters the **Terminated** state.


1. **New**: [When is P1 in the New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When and why would a thread be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *Multithreading is used in many real-world applications to allow multiple tasks to run at the same time. For example, web servers use threads to handle requests from many users simultaneously. In video games, threads can manage graphics, sounds, and user input separately. Mobile applications use threads to perform background tasks without slowing down the user interface. Multithreading is also useful in operating systems for managing different processes and tasks efficiently.


### Example 1 (operating-system level): [Name of scenario]
In an operating system, multiple processes may be waiting to use the CPU at the same time. The operating system places these processes in the ready queue and uses a scheduling algorithm to decide which process runs next. When a process reaches its time quantum, the CPU can switch to another process. This allows multiple processes to share the CPU efficiently and improves system responsiveness.
**Description**:
The operating system manages multiple processes that need to use the CPU. Each process waits in the ready queue until the scheduler gives it CPU time. After its time quantum ends, the process may be moved back to the ready queue while another process runs. This process continues until all tasks are completed, allowing the CPU to be shared efficiently.

**Why Round-Robin works well here**:
Round-Robin works well here because it gives each process a fair amount of CPU time. Each process gets a fixed time quantum before the CPU moves to the next process. This prevents one process from using the CPU for too long and keeps the system responsive. It is especially useful when many processes need to share the CPU at the same time.


### Example 2: Web Server Handling Multiple User Requests

A web server can use multithreading to handle requests from many users at the same time. Each thread can process a different user's request, allowing the server to respond to multiple users without making them wait for one another.

**Description**:
A web server receives requests from many users at the same time. Multithreading allows the server to create or use different threads to handle these requests simultaneously. While one thread is processing a request, another thread can work on a different user's request. This makes the server faster, more responsive, and able to serve multiple users efficiently.

**Why Round-Robin works well here**:
Round-Robin works well here because it gives each user request a fair share of CPU time. Each thread gets a fixed time quantum before the CPU switches to another thread. This prevents one request from using all the CPU resources and keeps the server responsive. It is useful when many users are accessing the server at the same time.

## Summary

**Key concepts I understood through these questions:**

1. I understood the difference between a process and a thread and how they work in an operating system.
2. I learned how the ready queue and Round-Robin scheduling manage CPU time fairly between processes.
3. I understood the thread lifecycle and how threads move between different states during execution.

**Concepts I need to study more:**

1. I need to study synchronization and how to prevent conflicts between threads.
2. I need to practice CPU scheduling algorithms and understand context switching in more detail.


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
