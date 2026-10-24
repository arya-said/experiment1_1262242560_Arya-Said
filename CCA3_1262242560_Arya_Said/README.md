# CCA3: Usability study of Flowspace vs ClickUp

| | |
|---|---|
| **Name** | Arya Said |
| **Roll number** | 1262242560 |
| **Project** | Flowspace: a redesign of ClickUp's first-run experience (sign-up, onboarding and first workspace) |
| **Figma prototype** | https://www.figma.com/proto/NGVBa9i4SpuI5o8qh3aflH/Untitled?page-id=73%3A12147&node-id=73-12148&starting-point-node-id=73%3A12148&scaling=min-zoom&content-scaling=fixed |
| **Original website** | https://clickup.com |

## Method

Mixed-methods study with 5 participants: friends and batchmates who had not used ClickUp or seen Flowspace before.

1. **Think aloud (qualitative):** each participant did one task on ClickUp first, then the same kind of task on the Flowspace Figma prototype, speaking their thoughts aloud. Each session was audio-recorded.
2. **Transcripts:** the researcher wrote up each recording. The transcripts have not been checked against the audio, so they are not verbatim speech-to-text output.
3. **Survey (quantitative):** each participant rates both versions in the course UX survey. Survey results are not yet included in this repo.

Each participant did a different task. The tasks were not the same across participants, so the platforms cannot be compared task by task.

| Participant | Task | Audio | Transcript |
|---|---|---|---|
| P1 Aryan | Find pending assignments and due dates | [P1_session.mp3](audio_files/P1_session.mp3) | [P1.txt](transcripts/P1.txt) |
| P2 Nancy | Set up a place for assignments and deadlines | [P2_session.mp3](audio_files/P2_session.mp3) | [P2.txt](transcripts/P2.txt) |
| P3 Mahek | Create a group project | [P3_session.mp3](audio_files/P3_session.mp3) | [P3.txt](transcripts/P3.txt) |
| P4 Debansi | Invite a friend to the project | [P4_session.mp3](audio_files/P4_session.mp3) | [P4.txt](transcripts/P4.txt) |
| P5 Nisarg | Add a task with a deadline | [P5_session.mp3](audio_files/P5_session.mp3) | [P5.txt](transcripts/P5.txt) |

## Results

Qualitative findings from the think-aloud transcripts:

| Theme | Participants | Evidence (from transcripts) |
|---|---|---|
| Flowspace easier to get started with or simpler | 5 of 5 | P1 "figure this out quickly"; P2 "easier to get started with"; P3 "more straightforward"; P4 "makes that part easier to understand"; P5 "feels a bit simpler" |
| ClickUp setup or organisation options unclear | 3 of 5 | P2 "quite a lot of options... not sure what to choose"; P3 "not sure which ones we actually need"; P4 unsure whether the invite gives access to the whole workspace or the project |
| ClickUp login or first screen straightforward | 1 of 5 | P1 "pretty straightforward" at login, but took longer to find My Tasks |
| Flowspace sample tasks or guidance helpful | 1 of 5 | P2 "it has already added some sample tasks... helpful" |
| Task completed on Flowspace | 2 of 5 explicitly confirmed | P4 invite added; P5 "the task is there" |

Quantitative measures:

| Measure | ClickUp | Flowspace prototype |
|---|---|---|
| Task completed (out of 5) | Not recorded consistently | Not recorded consistently |
| Average time (min) | Not recorded | Not recorded |
| Average survey rating | Pending | Pending |

## Final conclusion

Did the prototype improve the user experience? The qualitative evidence points that way, but it does not prove it.

All five participants described Flowspace as simpler or easier to start with, and three found ClickUp's options unclear. Those are consistent signals on learnability and clarity.

The study has limits:
- Five participants, all friends or batchmates, so the sample is small and not representative.
- Each participant did a different task, so the platforms cannot be compared directly.
- Completion and time were not recorded consistently, so efficiency cannot be measured.
- Flowspace is a Figma prototype with a fixed path. It cannot show errors, loading, or real use over time, which ClickUp would show.
- The test was not independent: the researcher designed the prototype and chose the tasks, which follow the prototype's path.
- Flowspace removes options and adds guidance. Only the additions participants mentioned have evidence, so the study cannot say which change caused the difference.
- Survey ratings are not yet included.

A stronger test would have all participants do the same tasks on both platforms, record completion and time for each, and include the survey ratings.

## Repository contents

| Folder or file | Contents |
|---|---|
| audio_files/ | Full think-aloud recordings, P1–P5 (MP3) |
| transcripts/ | Written transcripts of the sessions, P1–P5 |
| survey_data/ | Earlier exercises for this website: experiment 1 (website comparison), experiment 2 (empathy map), experiment 3 (lo-fi wireframes), experiment 4 (hi-fi wireframes and design justification D1–D8) |
| end_sem_experiments/ | Experiment 5 (heuristic evaluation), experiment 6 (Maze usability test and report), experiment 7 (accessible redesign) |
| CCA3_Conclusion_Report.docx | Final conclusion report (1–2 pages) |
