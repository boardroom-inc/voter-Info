[![Discord][discord-shield]][discord-url]
[![Twitter][twitter-shield]][twitter-url]

<br />
<p align="center">
  <a href="http://app.boardroom.info/">
    <img src="https://i.ibb.co/tBt9dLq/transparentblacktextsmall.png" alt="Logo" width="500" height="100">
  </a>

  <h3 align="center">Boardroom Project Information Repo</h3>

  <p align="center">
    This public repo contains voter information which will be served to display on the Boardroom Governance Portal
    <br />
    <a href="http://app.boardroom.info/"><strong>Browse the Portal »</strong></a>
    <br />
    <br />
    <a href="http://boardroom.info/">Landing</a>
    ·
    <a href="https://discord.com/invite/tgrTFg9">Discord</a>
    ·
    <a href="https://discord.com/invite/tgrTFg9">Get In Touch</a>
  </p>
</p>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#structure">Repo Structure</a></li>
     <li><a href="#new-delgation-pitch">Add New Delegation Pitch</a></li>
     <li><a href="#add-voter-tags">Add Voter Tags</a></li>
</ol>
</details>

## **Structure**
1. The `voterInfo.json` file contains information about voter tags
2. `Delegation Pitches Folder`: Contains files with delegation pitches of voters 
    

##  **Add New Delegation Pitch**
1. Add a new file in the folder `Delegation Pitches` with the format `{VoterAddress}.md` as the filename.
2. Add delegation pitch as content to the file.
2. Raise a PR with the changes.

##  **Add Voter Tags**
1. Edit the file voterinfo.json with the format, 
```
    [VoterAddress]: {
       tags: ['respective tags']
    }
``` 
2. Raise a PR with the changes.

## Contact
Please reach out in Discord with any questions! 
* Boardroom Support Channel - [#❓support](https://discord.gg/CEZ8WfuK8s)

[discord-shield]: https://img.shields.io/badge/Discord-Join-blueviolet?style=for-the-badge&logo=discord&logoColor=white
[discord-url]: https://discord.gg/CEZ8WfuK8s
[twitter-shield]: https://img.shields.io/badge/Twitter-Follow-blue?style=for-the-badge&logo=twitter&logoColor=white
[twitter-url]: https://twitter.com/boardroom_info
