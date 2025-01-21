# Part I

mkdir first

cd first

touch person.txt

mv person.txt another.txt

cp another.txt copy.txt

rm copy.txt

cd ..
cp -r first second

rm -r second


# Part II

# 1. What does the `man` command do? Type in `man rm`. How do you scroll and get out?
# The `man` command displays the manual page for a command. To scroll, use the arrow keys or Page Up/Page Down. To exit, press `q`.

# 2. Look at the `man` page for `ls`. What does the `-l` flag do? What does the `-a` flag do?
# The `-l` flag displays detailed information about files. The `-a` flag shows all files, including hidden ones.

# 3. How do you jump between words in the terminal?
# Use `Ctrl + Left Arrow` or `Ctrl + Right Arrow` to jump between words.

# 4. How do you get to the end of a line in terminal?
# Use `Ctrl + E` to move to the end of a line.

# 5. How do you move your cursor to the beginning in terminal?
# Use `Ctrl + A` to move to the beginning of a line.

# 6. How do you delete a word (without pressing backspace multiple times) in terminal?
# Use `Ctrl + W` to delete a word.

# 7. What is the difference between a terminal and shell?
# A terminal is the interface that allows users to interact with the shell. The shell is the program that interprets and executes commands.

# 8. What is an absolute path?
# An absolute path specifies the complete path to a file or directory, starting from the root directory (e.g., `/home/user/file.txt`).

# 9. What is a relative path?
# A relative path specifies a location relative to the current directory (e.g., `./file.txt` or `../folder`).

# 10. What is a flag? Give three examples of flags you have used.
# A flag is an option or argument passed to a command to modify its behavior. Examples:
# - `-l` (detailed list in `ls`)
# - `-a` (show hidden files in `ls`)
# - `-r` (recursive remove in `rm`)

# 11. What do the `r` and `f` flags do with the `rm` command?
# The `-r` flag removes directories and their contents recursively. The `-f` flag forces deletion without confirmation.