# safe-crossing
# Safe Crossing: Smart Roadside Warning and Hotspot Map

A low-cost, solar-powered warning system for dangerous highway and hill-road crossings, built for the Seva First Innovation Challenge (Eastern Region).

## The problem
On the highway between Islampur and Siliguri, many stretches are dark and empty at night, so vehicles drive at full speed. Bushes hide people, cattle, goats and dogs until they step onto the road. On 6 November 2026 at Madaripur I observed 4-5 people crossing the road. Drivers and people crossing get no early warning.

## The idea
- Lights on the highway and on the side road glow one by one, brighten and flash faster as a vehicle gets closer.
- A signal facing the crossing shows "vehicle coming" so people wait. It never says "safe to cross".
- Detections are logged on a map so authorities can see which spots need permanent fixes.

## What is in this repository
| Item | What it is | Status |
|---|---|---|
| `index.html` | Interactive night highway simulation | Working simulation |
| `mountain.html` | Interactive hill-bend simulation | Working simulation |
| `firmware-draft/` | ESP32 code for the sensor nodes | Draft, [compiles / does not compile yet] |
| `circuit/` | Tinkercad circuit design | Design only, not built |

## Live demo
- Highway: [your Pages link]
- Hill bend: [your Pages link]/mountain.html

## Honest status
- The simulations show how the system would behave. They are not tests of real sensors.
- The hardware has not been built or tested on a road.
- Sensor ranges, false alarms, fog, rain and battery behaviour still need real testing.
- Any installation on a road needs permission from the road authority.

## Planned next steps
1. Longer crossing survey at [place].
2. Build a table-top demo with an ESP32, a distance sensor and LEDs.
3. Test sensors outdoors, then request permission for a small pilot.
4. Add the hotspot map web app.

## Built with
HTML, CSS and JavaScript (canvas) for the simulations. ESP32 with C++/Arduino for the planned hardware.

## Author
Bidhan Chandra Paul, B.Tech CSE (1st year), Siliguri Institute of Technology
