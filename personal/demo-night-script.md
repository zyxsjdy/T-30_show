# Demo Night script

Five minutes, spoken from the page. No slides.

Open https://zyxsjdy.github.io/T-30_show/bridging_signal_blind_spots.html, refresh, and leave it at the top. The buttons then read **Hover**, **Independent**, and **Every step**. Stay in the browser the whole five minutes. Do not press **Guide me**, and do not click the mast. Point at it.

On this page the mast sends, and the two drones listen. The charts are saved test results. The laptop is not measuring a live signal.

| Time | Section on the page | What you do |
| --- | --- | --- |
| 0:00–0:45 | Title, with the city picture below | Talk. No clicks. |
| 0:45–1:20 | **The link** | Point. One click: the block. |
| 1:20–1:50 | **Two paths for the low drone** | Two button clicks. |
| 1:50–2:15 | **What the signal looks like** | Point at the four waves. Skip the power bar. |
| 2:15–2:45 | **What changes the estimate** | Two button clicks, in the order below. |
| 2:45–3:45 | Stay where you are | Talk. |
| 3:45–4:45 | Stay where you are | Talk. |

If the path section runs long, skip the waves and go straight to the buttons.

## The problem — 45 seconds

Radio signals travel best in a straight line. Put a building in the way, and you get a dead zone where the signal drops out. That matters if you lose connection on the street. It matters if an emergency crew needs a drone link when roads are blocked. And it matters to anyone planning a city network.

My work is the measurement behind that. If we bounce the signal off a wall panel of tiny mirrors, can we still tell what that path is doing? This page shows that story in pictures.

## The demo — 2 minutes

Scroll so **The link** fills the screen.

> Here is the whole scene in one picture. Up on the roof, a mast sends the signal. Two drones are listening. The high drone is up in the open sky, hearing the mast directly. The low drone is down near the street. This block is a building sitting right in the way. That panel on the wall is made of small mirrors, and the low drone catches the signal on the bounce. The other towers are just a backdrop. I drew the drones and mirrors larger than life so you can see them from the back.

Click the block once. Do not read the text box.

> That red dashed line is the straight path. The building blocks it, so we leave it out.

Scroll to **Two paths for the low drone**. **Straight path left out** is already selected.

> Here is the same idea, drawn flat. The straight path to the low drone is crossed out.

Click **Panel path in the equation**.

> This is the path our test keeps: mast, to mirror, to low drone. The high drone stays in both views. It never needed the mirror in the first place.

Scroll to **What the signal looks like**. Stop when all four waves are visible. Do not stop on the power bar.

> The smooth line is the actual path. The fuzzy line is what arrives, noise and all. The high drone is flying, so its path keeps changing. The low drone is hovering beside a fixed mirror, so its path sits in a narrow band.

Scroll to **What changes the estimate**.

> These buttons replay a saved test on the laptop. Right now the high drone is hovering, each moment stands on its own, and a fresh test beep arrives at every step. Both ways of guessing land almost together.

Click **Sticky, 0.95**. Then click **Every 4th step**. Leave **Hover** selected. Do not press **Independent** after this. That pair has no saved score, and the chart goes blank.

> Now the path changes slowly, and a new beep comes only every fourth step. This is where our newer guess pulls ahead. Still, flying matters far more than which method you pick. Put this same drone into a cruise, and both guesses get worse.

## Users and traction — 1 minute

Nobody outside this room has seen this page yet. Tonight is the very first test. After this talk, I want to know if someone who does not work on radios can say two things back to me: a building blocks the straight path, and the wall of mirrors gives the low drone a path anyway.

Next, I will sit down with people outside the lab, ask them to say it back, and rewrite any line where they stumble.

## Key learning and what’s next — 1 minute

The big surprise was the drone behind the building: it can actually be the easier one to measure. It hovers almost still beside a fixed mirror, while the high drone's clear path keeps changing as it flies.

The hard part is the city itself. Modeling real-world city physics is tough, so this environment uses simplified assumptions. Refining the algorithm for truly accurate estimation, and designing an optimal quantum circuit, remain complex, ongoing challenges.

The next step is to keep working on these challenges—and when possible, do some real-world testing.

## If someone asks

- “Is this running live?” — No. The laptop is not measuring a live signal—it is replaying saved results from a controlled test.
- “Are the drones the cell towers?” — No. The rooftop mast sends the signal, and the two drones only listen.
- “Where is the quantum computer?” — Not on this laptop. We simulated a small quantum step ahead of time, saved the scores, and loaded them into the chart.
