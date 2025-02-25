## What's This?

This is a script that allows you to install Ubuntu in your termux application without a rooted device

## Changelogs
- Add Ubuntu jammy
- Add Ubuntu 20.04 || 22.04 || 24.10
- Add Hosts

## Important

**• If you have to use ubuntu in termux with a x86/i\*86 architecture or prefer ubuntu 19.10 you can use this branch -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10**

**• If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file**

### Installation steps

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/fitriaaliyah/ubuntu-termux.git`
7. Go to script folder: `cd ubuntu-termux`
8. Give execution permission: `chmod +x libubuntu_24_10.sh`
9. Run the script: `./libubuntu_24_10.so -y`
10. Now just start ubuntu: `./startubuntu.sh`

## Credits
- MFDGaming
- Ubuntu
- Rachel For Update
