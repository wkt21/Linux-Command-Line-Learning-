cp` — Copy Files and Directories

cp copies files or directories from one location to another.

---

Copy a file

cp file.txt /tmp/


---

Copy and rename

cp file.txt backup.txt


---

Copy a directory recursively

cp -r src/ src-backup/


---

Preserve timestamps and permissions

cp -p config.yaml config.yaml.bak


---

Interactive copy (prompt before overwrite)

cp -i file.txt /tmp/
