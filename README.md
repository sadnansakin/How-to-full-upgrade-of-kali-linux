# How-to-full-upgrade-of-kali-linux


## How to update Kali?
To update Kali, first ensure that /etc/apt/sources.list is properly populated:

        ## kali@kali:~$ cat /etc/apt/sources.list
        
        comment - See https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/
        deb http://http.kali.org/kali kali-rolling main contrib non-free

         Additional line for source packages
        comment -  deb-src http://http.kali.org/kali kali-rolling main contrib non-free

kali@kali:~$
After that we can run the following commands which will upgrade us to the latest Kali version.

        ## kali@kali:~$ sudo apt update
        ## kali@kali:~$ sudo apt full-upgrade -y
