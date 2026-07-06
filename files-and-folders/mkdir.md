files-and-folders/mkdir.md

`mkdir` — Create Directories

mkdir creates new directories with optional parent creation.

---

Create a single directory

mkdir project


---

Create nested directories

mkdir -p project/src/assets


-p prevents errors if parents already exist.

---

Set permissions at creation

mkdir -m 755 public


---

Verify directory creation

ls -ld project
