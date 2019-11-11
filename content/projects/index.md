# Projects

<hr />

## Skedoodle
Skedoodle is a multiplayer party game modelled after telestrations designed to be played on mobile devices. Players will be able to connect from their mobile browser into a lobby displayed on a monitor or TV. Once the game starts, each player is given a word and asked to draw that word. Drawings will be converted into a blob (Binary Large OBject) and processed by the database. Each drawing is passed to another different player. The server sends a blob and the app converts the blob back into an image. The following player has to guess what they think the image is. The guess is passed and the next player has to draw that word. This continues until all the rounds are complete. Players will be able to visually see on the host machine (typically displayed on a big monitor) how their word and drawings have mutated over each player's iteration.

**Tech Stack:** ReactJS, Express, PostgreSQL, Socket.io

**Github:** [Skedoodle]


#### Host Machine View
{{< image src="/skedoodle2.png" alt="skedoodle" position="center" style="height:500px;">}}

#### Mobile Client View
{{< image src="/skedoodle1.png" alt="skedoodle" position="left" style="height:500px;">}}

<hr />

## Scheduler
Interview scheduler that is built using react. The scheduler makes axios requests to a database that stores the data and then updates the state to ensure that the components on the screen are updated in real time.

**Tech Stack:** ReactJS, Express, PostgreSQL

**Github:** [Scheduler]

#### Scheduler View
{{< image src="/scheduler1.png" alt="scheduler1" position="left" style="height:400px;">}}
#### Adding an Appointment View
{{< image src="/scheduler2.png" alt="scheduler2" position="left" style="height:400px;">}}
#### Appointment is Successfully Added and Spots are Updated
{{< image src="/scheduler3.png" alt="scheduler3" position="left" style="height:400px;">}}


[Skedoodle]:https://github.com/etseng02/illustrations
[Scheduler]:https://github.com/etseng02/scheduler