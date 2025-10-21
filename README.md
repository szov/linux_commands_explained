# 🐧 Linux Commands Explained

A collection of **Linux commands explained clearly — one command each day**.  
Each file in this repository breaks down a single Linux command with syntax, options, examples, and notes — designed to help learners, sysadmins, and hackers alike understand how Linux works under the hood.

---

## 📚 Project Goal

To build a simple, well-structured reference guide that explains **one Linux command every day** in a clean and consistent Markdown format.

---

## 📖 Repository Structure


Each file contains:
- **Command description**
- **Syntax**
- **Options table**
- **Examples**
- **Notes**
- **References**

---

## 🧠 Example Format

Example file structure (`showmount_explained.md`):

```markdown
# `showmount` Command Explained

The `showmount` command displays information about NFS (Network File System) mounts on a server. It shows which directories are shared and which clients are currently mounting them.

## Syntax
showmount [OPTION...] [HOST]

## Options
| Option | Description |
|:-------|:-------------|
| `-a` | List both client hostname/IP and mounted directory. |
| `-e` | Display the list of exported file systems. |
| `-h` | Show help menu. |

## Examples
showmount -e 192.168.1.10

## Notes
Requires NFS utilities and may need sudo privileges.

## References
man showmount
🗓️ Daily Updates

🔹 A new Linux command is added every day.
🔹 Each entry follows the same easy-to-read format.
🔹 Perfect for quick learning or revision.

💡 How to Use

Browse files directly on GitHub.

Use search (Ctrl + F) to find a specific command.

Copy Markdown examples to your own notes or wiki.

Great for building a personal Linux cheat sheet.

🤝 Contributing

Want to help expand the collection?

Fork the repo

Add a new file named <command>_explained.md

Follow the same documentation format

Submit a pull request

Your contribution will be reviewed and merged!

⭐ Support

If you find this repo helpful:

Leave a ⭐ on GitHub — it helps a lot!

Share it with friends learning Linux.

🧩 Author

Created by szov
Learning and documenting Linux, one command at a time 🐧
