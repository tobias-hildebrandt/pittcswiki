---
title: "Getting Started with Linux"
---

Linux is a popular free/libre/open source operating system kernel that allows users and developers a great level of control, customization, and freedom. 

Please note that Linux is technically only a kernel and not a complete operating system. The de-facto standard userland that is used with the Linux kernel is GNU (though other userlands such as BusyBox and Android also exist). Thus, some people insist on calling the entire combination GNU/Linux or GNU+Linux. In this guide, for simplicity, we will use the term Linux to refer this combination.

# Is Linux Right For You?

## Pros
- Freedom and Choice
  - You can uninstall any program that you don't like -- no more Candy Crush or Microsoft Edge (unless you want it!)
  - You choose the graphical user interface suits you best (or choose to not have one at all) -- see [our section on desktop Linux](#desktop-linux)
  - You get to choose a distribution that uses a packaging system that fits your use case: stable, but older or newer, but less tested -- see [our section on packaging](#packaging)
  - You are able to change anything you want to, assuming you know how to do it! Linux and most programs written for it are [free software](https://www.gnu.org/philosophy/free-sw.en.html)
  - Linux is supported on many different device architectures and devices, from servers to desktops to embedded systems!
  - You control your privacy! Most Linux distributions have telemetry disabled by default, so it's up to you if you want to send any usage data
- Safety
  - Less viruses target Linux than Windows -- many users don't even run an antivirus program (the best antivirus is your brain!)
  - Security issues are patched faster: with more people looking at the source code, vulnerabilities and bugs are spotted and patched at a quicker pace -- see [Linus's Law](https://en.wikipedia.org/wiki/Linus%27s_law)
  - There is a clear separation between permission levels -- see [our section on permissions](#permissions)
  - Most software you download will come from a trusted source: your distribution's package repository -- see [our section on packaging](#packaging)
- Community/Industry
  - You can find a vast amount of resources/tutorials/guides online
  - Linux is a very popular choice for servers in industry
    - 100% of the top 500 supercomputers in the world run Linux ([source](https://itsfoss.com/linux-runs-top-supercomputers/))
- Skills
  - Learning how to use Linux will help you learn more about operating systems and computers in general
  - Skills in Linux can transfer to other operating systems too!

## Cons
- Learning Curve
  - Linux does take a while to learn, even with all the resources that are out there
  - It is sometimes difficult to determine if information is up to date, since Linux has been around for over 30 years!
  - The command line is scary for newcomers who haven't had much experience with it
    - While lots of vital operations are available via a graphical interface, there are some things that can only be done on the command line
- Windows Software Compatibility
  - While lots of Windows software can be run on Linux through a compatibility layer such as Wine, many applications cannot
  - Most video games do not support Linux out of the box
    - Though with [Wine](https://www.winehq.org/)/[Proton](https://www.protondb.com/) (a wrapper and extension of Wine developer by Valve), 77% of the top 1000 games on Steam can be played at a "Gold" level or higher!
  - Nvidia drivers on Linux can be a pain -- see [our section on Nvidia](#nvidia)
  <!-- TODO: move to #nvidia or #hardware -->
    - Nvidia (the company) doesn't contribute to their cards' open source driver `nouveau`[,](https://youtu.be/_36yNWw_07g) so they are not usually not as good as the proprietary drivers 
    - Nvidia's proprietary drivers are infamous for: being difficult to install and update; breaking the graphical system; incompatibility with certain cards
    - Luckily, AMD *does* contribute to their cards' open source driver `amdgpu`

<!-- distributions, brief synopsis, beginner recommendations -->
# Distributions
A Linux *distribution* (often shortened to just *distro*) is a complete operating system, including the Linux kernel, a userland (most often GNU), and a package manager. The word "distribution" comes from the fact that the software is *distributed* together as a single entity. Most distributions also include a window system (X or Wayland), a window manager (AKA wm), and a desktop environment (AKA dm). Most end-users install a distribution of Linux instead of installing all the components separately. Some examples of distributions include: Ubuntu, Debian, Fedora, Red Hat Enterprise Linux (RHEL), Arch, and Manjaro.

Linux distributions differ in a few ways: their packaging/versioning philosophy, their target use and audience, and governance.

## Packaging and Versioning
A software package is collection of software and data. A package is typically encapsulated in an archive file (similar to a zip or rar file). 

<!-- command line basics -->

<!-- packages -->

<!-- hardware compatibility, nvidia, laptops -->

<!-- desktop linux -->

<!-- free software / ideology -->

<!-- how is linux developed, ecosystem, organizations -->

<!-- beginner guides -->

<!-- other resources -->

<!-- opinions -->