## The ML-repo Zen
*In order of significance*

1. Progress bar everything that takes time - use **tqdm**!
2. Replace *train-eval-test* logic with *(train-eval)/predict*.
3. Make resumable everything that can be resumed.
4. Checkpoint all big intermediary calculations.
5. Make model loading possible in **two** lines of code (import and load) and inference in **three**.
6. Make inference possible from raw data (numpy arrays, text etc).
7. Allow batch compute on inference.
8. Learn to package: you could use argparse :)
9. Allow issues section for community discussion, even if you want to unsubscribe yourself.
10. Don't hesitate to require some knowledge of python (or any) but not some knowledge of how you think.
11. Support multiple cudatoolkits: don't crush someones PC by a reckless environment.yml file.
12. Run a memory stress test for a synthetic dataset and report it in README.
13. Don't indulge to providing *proof of concept* but try to provide something useful - this will totally **prove your concept**.
14. Make your work citable.
15. Make docker **train** easy and batch calculation possible for docker **predict**.
16. Respect creators: Don't ask from someone to google-search for you or don't expect to get an answer to a question that is outside the specificity of the repo.
17. Respect users: Above + answer their questions if you can or else notify them that you can't.
