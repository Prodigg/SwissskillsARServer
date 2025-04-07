# SwissSkills AR Server

# dependencies

- python 3

# start server Local

To start the server run the following command in `content/ar`:

```
python3 -m http.server
```

Then in the festo diadaktic AR app type the following link:

```
http://IP-ADRESS:8000/index.xml
```

> [!IMPORTANT]
> replace `IP-ADRESS` with the IP-Adress of the computer witch is running the Webserver.

# Milestones

07.12.2024 commit [e120a57](https://github.com/Prodigg/SwissskillsARServer/commit/e120a576cec40a78a45569a7d30e14d8e2eac14a) first text rendering on AR device

09.12.2024 commit [70fc2cb](https://github.com/Prodigg/SwissskillsARServer/commit/70fc2cb90d3fed71d9154338116f587f5aaa801c) first text on imgtarget with marker_20.jpg

10.12.2024 commit [87c8a9b](https://github.com/Prodigg/SwissskillsARServer/commit/87c8a9b7a2d3c35296da28f9170b10ed1325ebea) first communication between test ws server and AR device

Picture of Wireshark picturing communication between test ws server and AR device

![Employee data](Screenshots/firstSuccsessfullCommmunication.png?raw=true "Employee Data title")

25.12.2024 commit [91f59bd](https://github.com/Prodigg/SwissskillsARServer/commit/91f59bd03aaa586e66dfbd01fe14f61f30e73370) first ws communication with NodeRed server

![NodeRed ws communication](Screenshots/firstNodeRedCom.png?raw=true "NodeRed ws communication")
