Supplemental Materials:

This archive contains the study instruments, task repositories, example code, and supporting media for the two user studies reported in the paper. Participant-data CSV files are intentionally omitted from this version. The materials are organized as follows:

1. ELIGIBILITY AND DEMOGRAPHIC SURVEYS (root level)
   - eligibility-survey.pdf         Screening survey used to recruit participants.
   - demographic-survey.pdf         Pre-study questionnaire on participants' backgrounds.

2. CONTROLLED STUDY (control-study/)
   A within-subjects study comparing Delta (Library B) against a plain React baseline
   (Library A). Participants completed two matched formula-augmentation tasks.

   control-study/
   ├── set-up.pdf                   Session setup instructions.
   ├── final-survey.pdf             Post-study survey comparing the two libraries.
   │
   ├── task-a/                      Task A — Library A (React baseline)
   │   ├── task.pdf                 Task prompt given to participants.
   │   ├── guide.pdf                API/library reference guide provided during the task.
   │   ├── post-task-form.pdf       Post-task questionnaire administered after Task A.
   │   ├── current.mov              Screen recording of the formula's state before the task.
   │   ├── result.mov               Screen recording of the expected result after the task.
   │   └── task-a-repo/             Starter code repository participants edited (React/
   │                                TypeScript, Vite, Tailwind). Only src/App.tsx was
   │                                intended to be modified. A completed reference solution
   │                                is provided as src/solution.tsx.
   │
   └── task-b/                      Task B — Library B (Delta)
       ├── task.pdf                 Task prompt given to participants.
       ├── guide.pdf                API/library reference guide provided during the task.
       ├── post-task-form.pdf       Post-task questionnaire administered after Task B.
       ├── current.mov              Screen recording of the formula's state before the task.
       ├── result.mov               Screen recording of the expected result after the task.
       └── task-b-repo/             Starter code repository participants edited (React/
                                    TypeScript, Vite, Tailwind). Only src/App.tsx was
                                    intended to be modified. A completed reference solution
                                    is provided as src/solution.tsx.

3. OBSERVATIONAL STUDY (observational-study/)
   A study in which participants used Delta to author interactive
   formula explanations of their own design, starting from two tutorial exercises
   and then completing two open-ended tasks.

   observational-study/
   ├── set-up.pdf                       Session setup instructions.
   │
   ├── observation-study-repo/          Starter code repository used by participants.
   │   └── src/
   │       ├── App.tsx                  Main entry point.
   │       ├── tutorial-1/              Tutorial 1 starter and solution files.
   │       ├── tutorial-2/              Tutorial 2 starter and solution files.
   │       └── task/                    Task 1 and Task 2 starter files.
   │
   ├── task-1/                          Materials for Task 1
   │   ├── tutorial-1.pdf               Tutorial 1 instructions (guided walkthrough).
   │   ├── tutorial-1.mov               Screen recording of the expected tutorial result.
   │   ├── task-1.pdf                   Open-ended task prompt.
   │   └── post-task-survey.pdf         Post-task survey administered after Task 1.
   │
   └── task-2/                          Materials for Task 2
       ├── tutorial-2.pdf               Tutorial 2 instructions (guided walkthrough).
       ├── tutorial-2.mov               Screen recording of the expected tutorial result.
       ├── task-2.pdf                   Open-ended task prompt.
       └── post-task-survey.pdf         Post-task survey administered after Task 2.

4. EXAMPLE GALLERY CODE (example-gallery-code/)
   Source code for the interactive formula examples shown in the paper and/or
   video supplement. Each file is a self-contained React/TypeScript component
   built with Delta. Some examples appear in different versions across the
   paper and video (e.g., with or without an accompanying graph, or with a
   different number of formula variants).

   example-gallery-code/
   ├── kinetic-energy.tsx               Featured in paper.
   ├── probability.tsx                  2-formula version featured in paper;
   │                                    3-formula version featured in video.
   ├── half-life.tsx                    Formula-only version featured in paper;
   │                                    formula + graph version featured in video.
   ├── average.tsx                      Featured in paper.
   ├── vector-addition.tsx              Formula-only version featured in paper;
   │                                    formula + graph version featured in video.
   ├── matrix-multiplication.tsx        Featured in paper and video.
   ├── wave-formula.tsx                 Featured in paper and video.
   ├── gradient-descent.tsx             Featured in paper and video.
   └── gravitational-force.tsx          Featured in video.
