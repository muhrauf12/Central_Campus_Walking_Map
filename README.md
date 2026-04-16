## [UM Central Campus Walking Map]

For this Project I wanted to focus on walking in the sense of getting from A to B, specfically on U of M Campus. The motivation for this was that digital maps tend to lack when it comes to walking directions, often misssiing the shortest path between two places because of insuffiecent informatioun. I explored this by making a interactive map that shows you the fastest way to walk between two locations. During the process of this it made me reconsider alot of things about walking directions. For starters, the fastest walk between two places often means cutting through buildings and I wanted my map to reflect that, but complications rose from even that as you can only cut through during certain parts of the day. Also on campus construction flucates alot, and even if my map reflected contruction from today, in a week it would probably change. The underlaying map I used also was outdated which completly changed some of the paths that I would use today, so I settled on making the map reflect current day campus rather than the underlying image. Also it was really tedius to define what was walkable and what wasn't, so i didnt get around to defining everything, just core parts. Theres just alot of considerations that you have to make which is why many places tend to not have very accurate walking maps unlike driving maps.

<img width="1416" height="831" alt="Screenshot 2026-04-15 at 9 45 33 PM" src="https://github.com/user-attachments/assets/614928e3-378e-45e8-8cc1-23f8cdadb60a" />

## Running

Requires a local web server 

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Usage

- Click **Start** or **End** to place a pin
- **Clear route** resets the pins

## Admin mode

 `http://localhost:8080?admin` To edit walk zone

