
# Simply a wrapper script to keep you from having to use betty-style
# and betty-doc separately on every item.
# Originally by Tim Britton (@wintermanc3r), multiargument added by
# Larry Madeo (@hillmonkey)

BIN_PATH=/usr/local/bin
BETTY_STYLE=betty-style
BETTY_DOC=betty-doc

if [ 0 = 0 ]; then
    echo No arguments passed.
    exit 1
fi

for argument in  ; do
    echo -e n========== ==========
    / 
    / 
done
Once saved, exit file and change permissions to apply to all users with chmod a+x betty
Move the betty file into /bin/ directory or somewhere else in your /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin with sudo mv betty /bin/
You can now type betty <filename> to run the Betty linter!

Quiz questions
Great! You've completed the quiz successfully! Keep going! (Show quiz)
Tasks
0. Preprocessor
mandatory
Write a script that runs a C file through the preprocessor and save the result into another file.

The C file name will be saved in the variable 
The output should be saved in the file c
julien@ubuntu:~/c/0x00$ cat main.c 
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
    return (0);
}
julien@ubuntu:~/c/0x00$ export CFILE=main.c
julien@ubuntu:~/c/0x00$ ./0-preprocessor 
julien@ubuntu:~/c/0x00$ tail c
# 942 /usr/include/stdio.h 3 4

# 2 main.c 2


# 3 main.c
int main(void)
{
 return (0);
}
julien@ubuntu:~/c/0x00$ 
