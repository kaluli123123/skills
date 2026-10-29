---
"mattpocock-skills": patch
---

Make `write_env` assign the shell variable it persists so later wizard stages read the saved value during the same run.

Remove the unused red color variable so the wizard template passes ShellCheck.
