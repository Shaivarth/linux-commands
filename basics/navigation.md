Today I started learning the basics of Linux terminal navigation and file management. These commands are the foundation of working efficiently in Linux and are used extensively by developers, system administrators, DevOps engineers, cloud professionals, and cybersecurity practitioners.

The first command I learned was `pwd`, which stands for **Print Working Directory**. This command displays the absolute path of the directory I am currently working in. It is useful whenever I want to verify my current location within the filesystem.

```bash
pwd
```

Example output:

```bash
/Users/shaivarth/developer
```

I then learned the `ls` command, which stands for **List**. It displays all files and folders present in the current directory. This is one of the most frequently used commands for exploring directory contents.

```bash
ls
```

To get more detailed information, I learned `ls -la`. The `-l` flag provides detailed information such as permissions, ownership, file size, and modification timestamps, while the `-a` flag ensures that hidden files (files beginning with `.`) are also displayed.

```bash
ls -la
```

Next, I learned the `cd` command, which stands for **Change Directory**. It is used to move between directories in the filesystem. For example, I can move into a folder using `cd backend`, move back to the parent directory using `cd ..`, or directly jump to my home directory using `cd ~`.

```bash
cd backend
cd ..
cd ~
```

After understanding navigation, I learned how to create directories using the `mkdir` command, which stands for **Make Directory**. This command creates a new folder in the current location.

```bash
mkdir linux-notes
```

Finally, I learned the `touch` command. It is commonly used to create an empty file. For example, the following command creates a new Markdown file named `notes.md` in the current directory.

```bash
touch notes.md
```

Along the way, I also became familiar with some important Linux symbols. The symbol `~` represents the home directory, `.` refers to the current directory, `..` refers to the parent directory, and `/` represents the root directory. Understanding these symbols makes navigation much easier and faster.
