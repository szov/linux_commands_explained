# `showmount` Command Explained

The `showmount` command displays information about NFS (Network File System) mounts on a server. It shows which directories are shared and which clients are currently mounting them.

---

## **Syntax**

showmount [OPTION...] [HOST]

- **HOST** — The hostname or IP address of the NFS server (default: local host).

---

## **Options**

| Option | Description |
|:-------|:-------------|
| `-a` | List both the client hostname/IP and the mounted directory in `computer:directory` format. |
| `-d` | Show only the directories that are mounted. |
| `-e` | Display the list of exported file systems (shares) from the NFS server. |
| `-h` | Show the help menu. |
| `-t` | Limit the output to specific file system types. |
| `-o` | Specify comma-separated mount options. |
| `-l` | Display file system tags. |

---

## **Examples**

### Show all active NFS mounts
showmount -a

### Display all exported file systems on the local host
showmount -e

### Check exports from a remote NFS server
showmount -e 192.168.1.10

---

## **Notes**

- Requires NFS services (`nfs-common` package on most systems).  
- May need superuser privileges (`sudo`) to view remote server information.  
- Useful for diagnosing or auditing NFS mounts on a network.

---

## **References**

- [man showmount](https://linux.die.net/man/8/showmount)  
- `nfs-utils` package documentation
