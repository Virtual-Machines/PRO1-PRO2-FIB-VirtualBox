# PRO1 PRO2 FIB VirtualBox [DOWNLOAD](https://github.com/Virtual-Machines/PRO1-PRO2-FIB-VirtualBox/releases/download/latest/P1P2FIB.ova) - [VIDEO](https://www.youtube.com/watch?v=F_EHtmjNEYY)

[**Your OPINION is important**](https://github.com/Virtual-Machines/PRO1-PRO2-FIB-VirtualBox/issues/1) - Last update: 2019-12-28

![PRO1PRO2](https://raw.githubusercontent.com/Virtual-Machines/PRO1-PRO2-FIB-VirtualBox/master/PRO1PRO2.png)

- Minimal Lubuntu 18.04.3 as a lightweight base
- Linux Kernel 5 HWE (Hardware Enablement)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- Kate and Konsole updated and properly configured
- Doxygen, the documentation generator. Use "doxygen -g" to create a DoxyFile
- C++ programming language through g++ compiler with p1 and p2 flags (p1++ and p2++ alias included on bashrc):

alias p1++="g++ -ansi -O2 -DNDEBUG -D_GLIBCXX_DEBUG -Wall -Wextra -Werror -Wno-uninitialized -Wno-sign-compare -Wshadow"

alias p2++="g++ -D_GLIBCXX_DEBUG -O2 -Wall -Wextra -Werror -Wno-sign-compare -std=c++11"

- Chromium browser with Jutge.org, PRO1 and PRO2 websites bookmarks
- Only included Helloworld C++ source file and compiler execution example because you must solve Jutge.org list problems by yourself (I know it's hard at the beginning but you will learn).
- Compile and run example: p1++ helloworld.cc -o helloworld.x && ./helloworld.x
- User and pass of system is the same: **lubuntu**
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"

[**OPINION**](https://github.com/Virtual-Machines/PRO1-PRO2-FIB-VirtualBox/issues/1)
