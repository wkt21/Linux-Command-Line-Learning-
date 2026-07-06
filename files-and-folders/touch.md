Create an empty file

touch file.txt


Creates file.txt if it does not exist.

---

Create multiple files

touch file1.txt file2.log file3.conf


---

Update modification time only

touch -m file.txt


---

Set a specific timestamp

touch -t 202501010101 file.txt


Format: [[CC]YY]MMDDhhmm[.ss]

---

Verify timestamps

ls -l file.txt
