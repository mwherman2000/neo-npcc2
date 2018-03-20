# neo-npcc2

NEO Persistable Classes (NPC) Compiler 2.1 (npcc) - Compiler for the NEO Persistable Classes (NPC) Platform 2.1

[NEO Blockchain C# Center of Excellence](https://github.com/mwherman2000/neo-csharpcoe/blob/master/README.md)

The `neo-csharpcoe` project is an "umbrella" project for several initiatives related to providing tools and libraries (code), frameworks, how-to documentation, and best practices for enterprise application development using .NET/C#, C#.NEO and the NEO Blockchain.

The `neo-csharpcoe` is an independent, free, open source project that is 100% community-supported by people like yourself through your contributions of time, energy, passion, promotion, and donations. To learn more about contributing to the `neo-csharpcoe`, click [here](https://github.com/mwherman2000/neo-csharpcoe/blob/master/CONTRIBUTE.md).

CURRENT NPC V2.0 PROJECT can be found [here](https://github.com/mwherman2000/neo-persistableclasses/blob/master/README.md) ([https://github.com/mwherman2000/neo-persistableclasses/blob/master/README.md](https://github.com/mwherman2000/neo-persistableclasses/blob/master/README.md)).

PREVIOUS NPC V1.0 PROJECT can be found [here](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/README.md) ([https://github.com/mwherman2000/neo-persistibleclasses/blob/master/README.md](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/README.md)) (with the mispelled project name :-)). 

## What is NPC?

* NEO Persistable Classes 
* Long name: NEO Persistable Class (NPC) Platform 2.1
* Byline: An Efficient Entity-based Platform for enterprise application development using .NET/C#, C#.NEO and the NEO Blockchain.

## What is the subset of C# supported by the NEO compiler and NEO VM?

* Watch this 20-minute segment of the video: [NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://www.youtube.com/watch?v=qwteL1BiCjM&t=4m30s) (first 20 minutes starting at timecode [4:30](https://www.youtube.com/watch?v=qwteL1BiCjM&t=4m30s))

   [![NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://img.youtube.com/vi/qwteL1BiCjM/0.jpg)](https://www.youtube.com/watch?v=qwteL1BiCjM&t=4m30s) 

* ...or click on the presentation below but the video is better ([PDF](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/Docs/videos/NPCdApp-HowTo%20v0.4-Recording.pdf)) (slides 5-22):

    [![NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://img.youtube.com/vi/qwteL1BiCjM/1.jpg)](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/Docs/videos/NeoPersistableClasses-Bluepaper%20v0.21-Recording.pdf) 


## npcc version v1 - Autogeneration of NPC Level 0-4 C#.NPC Smart Classes

* Input NPC Model Class Project: Plain Old C# Classes

  ![C#.NPC Model Class Project](./Docs/images/npcc-v1-parser-point.png)

* **npcc** Compiler Output

  ![**npcc** Compiler Output](./Docs/images/npcc-v1-parser.png)

* Autogenerated C#.NPC NeoContract smart contract project

  A. Input Model Class Project: Plain Old C# Class(es)
  
  B. Autogenerated NoeContract Smart Contract Project

  C. `Line` Entity C#.NPC Partial Classes

  D. `NeoEntityModel` C#.NPC Classes

  E. `Point` Entity C#.NPC Partial Classes

  ![Autogenerated Visual Studio NeoContract smart contract project](./Docs/images/npcc-v1-main.png)

## npcc version v0 - initial results

* Input NPC Class C#.NPC Source File

  ![Input NPC Class](./Docs/images/npcc-v0-parser-point.png)

* **npcc** Parser Output

  ![**npcc** Parser Output](./Docs/images/npcc-v0-parser.png)

## NEO Persistable Class (NPC) 1.0: Deep Dive (NEO Community Bluepaper)

* Watch this video: [NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://www.youtube.com/watch?v=qwteL1BiCjM) (90 minutes)

   [![NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://img.youtube.com/vi/qwteL1BiCjM/0.jpg)](https://www.youtube.com/watch?v=qwteL1BiCjM) 

* ...or click on the presentation below but the video is better ([PDF](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/Docs/videos/NPCdApp-HowTo%20v0.4-Recording.pdf)):

    [![NEO Persistable Classes 1.0: Deep Dive (Video 2 of 3) [Update 1]](https://img.youtube.com/vi/qwteL1BiCjM/1.jpg)](https://github.com/mwherman2000/neo-persistibleclasses/blob/master/Docs/videos/NeoPersistableClasses-Bluepaper%20v0.21-Recording.pdf)

## NPC Levels of Layered Persistance Supported

There are a number of different levels when it comes to applying the NPC Framework to classes in C#.NPC. There are:

* NPC Level 0 Basic
* NPC Level 1 Managed
* NPC Level 2 Persistable
* NPC Level 3 Deletable (Bury/Tombstone)
* NPC Level 4 Collectable
* NPC Level 5 Extendible (roadmap)
* NPC Level 6 Authorized (roadmap)
* NPC Level 7 Optimized (roadmap)

## Who is Michael Herman?

Michael Herman (Toronto) ([photo](https://raw.githubusercontent.com/mwherman2000/neo-dotnetquickstart/master/EN-us/images/mwherman2000.jpg))

Independent Blockchain Developer
* [NEO Blockchain C# Center of Excellence](https://github.com/mwherman2000/neo-csharpcoe/blob/master/README.md)

Michael Herman is a independent developer and writer who contributes to several NEO Blockchain projects including:
* NEO developer tool suite (neo-lux, neo-debugger and neo-gui-developer projects)
* mwherman2000/neo-persistableclasses project – home of the NEO Persistable Class Framework (NPC) for efficient entity-based smart contract development using C#.NEO
* mwherman2000/dotnetquickstart project – home of the NEO Blockchain Quick Start Guide for .NET Developers. 

Michael is also the founder of the [NEO Blockchain C# Center of Excellence](https://github.com/mwherman2000/neo-csharpcoe/blob/master/README.md) as well as the first Canadian NEO Blockchain Meetup group (NEO Blockchain Toronto). He has helped bootstrap several additional Meetups worldwide including NEO Blockchain Vancouver, NEO Blockchain Cancun, and NEO Blockchain Turkey.

### Contact

* E: mailto:neotoronto@outlook.com
* F: https://www.facebook.com/neotoronto/
* G: https://github.com/mwherman2000/neo-windocs
* M: https://www.meetup.com/NEO-Blockchain-Toronto
* T: https://www.twitter.com/neotoronto
* B: http://www.hyperonomy.com
* L: https://www.linkedin.com/in/mwherman/

### Feedback

* >In just 10 days you [made] tons of progress, you're probably [one of] the fastest learners around here. 
