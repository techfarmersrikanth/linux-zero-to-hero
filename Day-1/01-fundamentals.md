# What is Linux ?
- Just like Windows, iOS, and Mac OS, Linux is an operating system. In fact, one of the most popular platforms on the planet, Android, is powered by the Linux operating system. 

## What is Operating system ?
- An operating system is software that manages all of the hardware resources associated with your desktop or laptop. To put it simply, the operating system manages the communication between your software and your hardware.

## Without the operating system (OS), the software wouldn’t function.

The Linux operating system comprises several different pieces:

# Bootloader :
-  The software that manages the boot process of your computer. For most users, this will simply be a splash screen that pops up and eventually goes away to boot into the operating system.

# Kernel :
- This is the one piece of the whole that is actually called ‘Linux’. The kernel is the core of the system and manages the CPU, memory, and peripheral devices. The kernel is the lowest level of the OS.

# Init system :
- This is a sub-system that bootstraps the user space and is charged with controlling daemons. One of the most widely used init systems is systemd, which also happens to be one of the most controversial. It is the init system that manages the boot process, once the initial booting is handed over from the bootloader (i.e., GRUB or GRand Unified Bootloader).

# Daemons :
- These are background services (printing, sound, scheduling, etc.) that either start up during boot or after you log into the desktop.

# Graphical server :
- This is the sub-system that displays the graphics on your monitor. It is commonly referred to as the X server or just X.
# Desktop environment :
- This is the piece that the users actually interact with. There are many desktop environments to choose from (GNOME, Cinnamon, Mate, Pantheon, Enlightenment, KDE, Xfce, etc.). Each desktop environment includes built-in applications (such as file managers, configuration tools, web browsers, and games).
# Applications :
- Desktop environments do not offer the full array of apps. Just like Windows and macOS, Linux offers thousands upon thousands of high-quality software titles that can be easily found and installed. Most modern Linux distributions (more on this below) include App Store-like tools that centralize and simplify application installation. For example, Ubuntu Linux has the Ubuntu Software Center (a rebrand of GNOME Software) which allows you to quickly search among the thousands of apps and install  them from one centralized location.

## Why use Linux?
- This is the one question that most people ask. Why bother learning a completely different computing environment, when the operating system that ships with most desktops, laptops, and servers works just fine?

To answer that question, I would pose another question. Does that operating system you’re currently using really work “just fine”? Or, do you find yourself battling obstacles like viruses, malware, slow downs, crashes, costly repairs, and licensing fees?
If you struggle with the above, Linux might be the perfect platform for you. Linux has evolved into one of the most reliable computer ecosystems on the planet. Combine that reliability with zero cost of entry and you have the perfect solution for a desktop platform.

That’s right, zero cost of entry… as in free. You can install Linux on as many computers as you like without paying a cent for software or server licensing.

Let’s take a look at the cost of a Linux server in comparison to Windows Server 2016. The price of the Windows Server 2016 Standard edition is $882.00 USD (purchased directly from Microsoft). That doesn’t include Client Access License (CALs) and licenses for other software you may need to run (such as a database, a web server, mail server, etc.). For example, a single user CAL, for Windows Server 2016, costs $38.00. If you need to add 10 users, for example, that’s $388.00 more dollars for server software licensing.  With the Linux server, it’s all free and easy to install. In fact, installing a full-blown web server (that includes a database server), is just a few clicks or commands away (take a look at Easy LAMP Server Installation to get an idea how simple it can be).

If zero cost isn’t enough to win you over–what about having an operating system that will work, trouble free, for as long as you use it? I’ve used Linux for nearly 20 years (as both a desktop and server platform) and have not had any issues with ransomware, malware, or viruses. Linux is generally far less vulnerable to such attacks. As for server reboots, they’re only necessary if the kernel is updated. It is not out of the ordinary for a Linux server to go years without being rebooted. If you follow the regular recommended updates, stability and dependability are practically assured.

## Open source
- Linux is also distributed under an open source license. Open source follows these key tenets:

The freedom to run the program, for any purpose.
The freedom to study how the program works, and change it to make it do what you wish.
The freedom to redistribute copies so you can help your neighbor.
The freedom to distribute copies of your modified versions to others.
These points are crucial to understanding the community that works together to create the Linux platform. Without a doubt, Linux is an operating system that is “by the people, for the people”. These tenets are also a main factor in why many people choose Linux. It’s about freedom and freedom of use and freedom of choice.

## What is a “distribution?”
- Linux has a number of different versions to suit any type of user. From new users to hard-core users, you’ll find a “flavor” of Linux to match your needs. These versions are called distributions (or, in the short form, “distros”). Nearly every distribution of Linux can be downloaded for free, burned onto disk (or USB thumb drive), and installed (on as many machines as you like).

Popular Linux distributions include:

LINUX MINT
MANJARO
DEBIAN
UBUNTU
ANTERGOS
SOLUS
FEDORA
ELEMENTARY OS
OPENSUSE
Each distribution has a different take on the desktop. Some opt for very modern user interfaces (such as GNOME and Elementary OS’s Pantheon), whereas others stick with a more traditional desktop environment (openSUSE uses KDE).

You can check out the top 100 distributions on the Distrowatch.

And don’t think the server has been left behind. For this arena, you can turn to:

# Red Hat Enterprise Linux
# Ubuntu Server
# Centos
# SUSE Enterprise Linux
Some of the above server distributions are free (such as Ubuntu Server and CentOS) and some have an associated price (such as Red Hat Enterprise Linux and SUSE Enterprise Linux). Those with an associated price also include support.

## Which distribution is right for you?
Which distribution you use will depend on the answer to three simple questions:

How skilled of a computer user are you?
Do you prefer a modern or a standard desktop interface?
Server or desktop?
If your computer skills are fairly basic, you’ll want to stick with a newbie-friendly distribution such as Linux Mint, Ubuntu , Elementary OS or Deepin. If your skill set extends into the above-average range, you could go with a distribution like Debian or Fedora. If, however, you’ve pretty much mastered the craft of computer and system administration, use a distribution like Gentoo. If you really want a challenge, you can build your very own Linux distribution, with the help of Linux From Scratch.

If you’re looking for a server-only distribution, you will also want to decide if you need a desktop interface, or if you want to do this via command-line only. The Ubuntu Server does not install a GUI interface. This means two things your server won’t be bogged down loading graphics and you’ll need to have a solid understanding of the Linux command line. However, you can install a GUI package on top of the Ubuntu Server with a single command like sudo apt-get install ubuntu-desktop. System administrators will also want to view a distribution with regards to features. Do you want a server-specific distribution that will offer you, out of the box, everything you need for your server? If so, CentOS might be the best choice. Or, do you want to take a desktop distribution and add the pieces as you need them? If so, Debian or Ubuntu Linux might serve you well.