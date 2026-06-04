---
Before Day-2
---
I already knew how to navigate basic directories and handle file creation via the terminal. I also had experience managing local repositories and working inside WSL environments.

---
## Day-2 Checklist
- [x] I understand what `PATH` is and why commands like `python` work without full paths
- [x] I can navigate the filesystem without clicking — using `cd`, `ls`, and `pwd` only
- [x] I can read, search, and inspect files using `cat`, `head`, `tail`, `grep`, and `wc`
- [x] I can edit a file using `nano` (open, edit, save, exit)
- [x] I understand pipes (`|`) and redirection (`>`, `>>`, `2>`) and can chain commands
- [x] I can set an environment variable in `.bashrc` and apply it with `source ~/.bashrc`
- [x] I know the difference between `export VAR=value` (available to child processes) and just `VAR=value` (shell-local)

---
After Day-2
---
I learned these things as well, apart from the checklist:
* Streamlining text processing pipelines by chaining `grep` and `wc -l` to quickly count specific occurrences in dataset files.
* Properly isolating error outputs using `2>` to keep terminal logs clean during script execution.

------
Feedback (Suggestions for the TDS Team)
---
The focus on command-line data inspection utilities like `head`, `tail`, and `grep` is incredibly practical for parsing large datasets before loading them into memory. Loving the hands-on approach!

---------
### Personal Notes
* Use `Ctrl + O` then `Enter` to save in nano, and `Ctrl + X` to exit.
* `2>` redirects stderr, while `>` or `1>` redirects stdout. To send both to the same file, use `&>`.
* Remember that modifying `.bashrc` won't affect current sessions unless `source ~/.bashrc` is run manually.
