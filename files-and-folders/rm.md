rm` — Remove Files and Directories

rm deletes files and directories permanently.

⚠️ Danger: rm does not use a trash bin. Deleted files are gone.

---

Remove a file

rm file.txt


---

Remove multiple files

rm *.log


---

Remove a directory recursively

rm -r old-project/


---

Force delete (no prompts)

rm -f file.txt


---

Combine recursive + force

rm -rf /tmp/testdir


⚠️ Use with extreme caution.

---
