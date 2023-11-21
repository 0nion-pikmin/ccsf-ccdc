# ccsf-ccdc
City College of San Francisco's CCDC repo (2023)


Below is from Travis, a previous CCSF CCDC team member: https://github.com/traviskp/ccdc/tree/master

This repo contains some of the commands used to assist in securing systems for the Collegiate CyberDefense Competition. Our team (City College of SF) finished 2nd place in the 2019 Western Regional Qualifiers. Having everyone up to date on how to work the systems in front of them was key.

In the post event discussion, the red team brought up how once they compromised one system, this gave them information about everyone's system. Hence the logic behind sharing these commands.

Need to focus on that dialing in the inital network diagram and pinpoint which boxes are being scored. Nmap is great for listining the boxes, but knowing how they are linked needs improvement. Diagrams provided can help, but usuall only include names.

Password change management sharing amongst team mates. Our system involved sheets of paper with passwords on them and blank lines to the right to include the box and username. Using loose sheets of paper made things tricky as they would get moved around the room.

Pushing updates from the windows update server / group policy management. We could have saved a lot of time by knowing active directory better.

Knowing what services should / should not be running on Linux or Windows. Makes it easier to pinpoint vulnerable or malicious services running.

Change Logs . Important to keep a record of what you did so if you break it, can revert. System imaging...

Keep digging through https://github.com/trimstray/the-practical-linux-hardening-guide
