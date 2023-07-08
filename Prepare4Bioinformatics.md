# Curriculum to Prepare for Computation in Bioinformatics

## Become familiar with Unix/Linux

1.  ## Gain access to a Unix/Linux computer

    1.  Existing server  
If there is a server available, ask the systems administrator to create a user account for you. You will likely need to use secure
shell ([**ssh**](https://www.technology.pitt.edu/security/secure-shell-ssh-and-sftp)) to access the server.

    2. Virtual instance of Linux (Ubuntu) on VirtualBox  
VirtualBox is a virtualization server from Oracle. Please follow the instructions [here](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview)

    3.  MacOS – terminal  

        1. The underlying operating system of MacOS is a variant of Unix derived from the NEXT OS (built as a variant of UNIX without
        the proprietary UNIX constraints, not unlike Linux).  
        2. One can try to follow the Bash exercises in the Mac terminal (bash is usually the default shell). If you experience problems, type “echo $0” and record the name of the shell. If
        it is not bash, it might be best to install VirtualBox and Ubuntu.  


2.  ## Practice using commands in the Bash shell

    1.  There are some resources below. Please try to work through examples and exercises in these resources. Try typing the commands if there is an example output. Some important commands are:

        1.  `cd` – change directory
        2.  `ls` – list directory contents
        3.  `pwd` – present working directory (where am I?)
        4.  `echo` – usually “echo $varname”, prints the content of the variable varname.
        5.  `date` – prints the current date (and time) to the screen
        6.  `cat` – concatenate. cat filename will print the contents of the file. cat can also be used to append files together.
        7.  `tree` – not always installed by default. Displays directory in a text-based tree structure
        8.  `mv` – move a file, also acts to rename a file
        9.  `mkdir` – create a directory
        10. `rm` – remove a file
        11. `rmdir` – remove a directory (if empty)
        12. `touch` – create a file (if name doesn’t exist) or update the file to the current time. Also create a file with a specific date and time.
        13. `exit` – leave the current shell (closes shell and terminal window)

## Bash Resources  
**Elementary Bash**: 
>[Bash for beginners](https://towardsdatascience.com/basics-of-bash-for-beginners-92e53a4c117a) (start here)
> [Intro to Bash syntax and tools](https://opensource.com/article/19/10/programming-bash-syntax-tools)
>
> [Bash guide for beginners](https://www.linuxtopia.org/online_books/bash_guide_for_beginners/index.html)
>
> [Bash Guide for Beginners](https://tldp.org/guides.html) (find on the page: different formats available)
>
> [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) (Greg’s Wiki) (see appropriate tab)
>
> [Bash Guide](https://mywiki.wooledge.org/BashGuide) (Greg’s Wiki) (see appropriate tab)

**Bash Reference manual**: 
> [GNU Bash Reference](https://www.gnu.org/software/bash/manual/bash.html)

**Bash Scripting**: 
> [Introduction to bash scripting](https://www.linode.com/docs/guides/intro-bash-shell-scripting/)
> 
> [Ryan’s Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/)
> 
> [Bash scripting cheatsheet](https://devhints.io/bash)
> 
> [Advanced Bash Scripting Guide](https://tldp.org/guides.html) (find on the page: different formats available)

## Learn R

1.  Download and install R (<https://cran.r-project.org/>)

2.  Download and install RStudio (<https://posit.co/downloads/>)

3.  Install the tidyverse set of packages
    (<https://www.tidyverse.org/packages/>) in your R. **Note** that on
    Windows, it is often easiest to install everything as a personal
    installation, i.e., in your userspace. If you install R, RStudio and
    the packages for everyone on the computer, you need to run the RGUI
    as administrator.

4.  Some beginning resources (free):

    1.  <https://www.rpubs.com/meldataaa/BeginnersGuidetoR>

    2.  > <https://rpubs.com/jbaumann3/994268>

    3.  > <https://rpubs.com/acolumbus/how-to-get-started-with-r>

    4.  > <https://rpubs.com/ShaniahA/946625>

    5.  > <https://rpubs.com/JianKuang/132393>

    6.  > <https://bookdown.org/rwnahhas/IntroToR/> (NOTE: You can look
        > around bookdown.org for more books on R)

5.  The R for Data Scientists book (<https://r4ds.had.co.nz/>) **FREE
    ONLINE**

6.  Handy “cheat sheets” (2-page summaries) for Rstudio and tidyverse
    packages: <https://posit.co/resources/cheatsheets/>

## Learn Python

> This is not required but can be useful

1.  Download python and install <https://www.python.org/downloads/>

2.  Download an integrated development environment (IDE):

    1.  > PyCharm (<https://www.jetbrains.com/pycharm/download/>)

    2.  > PyDev (plugin for eclipse; <https://www.pydev.org/>)

    3.  > Visual Studio
        > (<https://visualstudio.microsoft.com/vs/community/>;
        > <https://visualstudio.microsoft.com/vs/features/python/>)

    4.  > Spyder (<https://www.spyder-ide.org/>)

3.  Learning Resources

    1.  > Tutorialspoint
        > (<https://www.tutorialspoint.com/python/index.htm>)

    2.  > Python Tutorial (<https://www.pythontutorial.net/>)

    3.  > Other websites:
        > <https://medium.com/javarevisited/10-free-python-tutorials-and-courses-from-google-microsoft-and-coursera-for-beginners-96b9ad20b4e6>
