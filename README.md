## How to instal it?
1) First download and install [Node.js >10](https://nodejs.org/en/) & [and optionally Console: Microsoft PowerShell-Core](https://docs.microsoft.com/pl-pl/powershell/scripting/install/installing-powershell?view=powershell-6) & [and optionally editor: Microsoft VSCode](https://code.visualstudio.com/download)
2) Create a folder anywhere on your computer and run the consoles there.and write the following lines in it, each time confirming them with an enterem
    -    ```PowerShell
         git clone https://github.com/cisowscy-com-software/haplo-ft-get.git
         ```
    -    ```PowerShell
         cd haplo-ft-get
         ```
    -    ```PowerShell
         npm i
         ```

![alt text][logo]

## How to cofigure it?

- SET USER&PASS -> open file `./config/user.json`, and put in your UserName & Password, and save it.
- SET MAX RAM -> open files `./step0.cmd` & `./step1.cmd`, and change the default value of `6144` (6GB RAM) to another good one for your hardware, suggests no less than 3GB, or 50% of your RAM power.

## How to usage it?

1) For get links to all resultats of distribution haplogroup

    - Double-click on `./step0.cmd` and when it's finish and the window disappears by itself. Double-click on `./step1.cmd`

    The first command retrieves the pagination of the alphabetical index, the second one for everyone a single element, retrieves and checks all the links needed to retrieve the content. The first process will last up to a minute, the second, even a few hours. Depends on computer performance, internet speed, and simultaneous different PC load.
    **The average speed of the script `./step1.cmd` in my case is 1432 projects per hour.**
    
2) reconstruction of the result of info of project, (filtering, sorting, splitting)
     -  coming soon..
3) For get distribution of haplogroups Y-DNA, by map.
     -  coming soon..
4) For get distribution of haplogroups mtDNA, by map.
     -  coming soon..
5) For get distribution of haplogroups Y-DNA, by SNPs.
     -  coming soon..
6) For get distribution of haplogroups mtDNA, by SNPs.
     -  coming soon..
7) For get distribution of haplogroups Y-DNA, by STRs.
     -  coming soon..
8) reconstruction of the result of data of project, (filtering, sorting, splitting) and build sqlite database of all data.
     -  coming soon..
9) in the longer term, building an offline tool for automation analysing, filtering, and generating reports based on genetic, cartographic and migratory data 
----------
## Anyone who wants to help in the development of grinding will be good seen :)

[logo]: ./doc/logo.jpg ""
