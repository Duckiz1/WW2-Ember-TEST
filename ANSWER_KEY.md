# Answer key: planted errors in `index.html`

This is a test fixture for fact-checking software. It contains **11 false claims** (plus one true control, #12) and **5 mismatched images**. Everything else in the article is meant to be accurate.

## False text claims

| # | Section | What the article says | What's correct |
|---|---------|-----------------------|----------------|
| 1 | The road to war | War began 1 September **1941** | 1 September **1939** |
| 2 | Blitzkrieg | Churchill became PM in **1938** | **10 May 1940** |
| 3 | Eastern Front | Invasion of the USSR was code-named **Operation Sea Lion** | **Operation Barbarossa** (Sea Lion was the planned invasion of Britain) |
| 4 | Eastern Front | Germans surrendered at Stalingrad in **February 1944** | **February 1943** |
| 5 | America enters | At Midway **the United States lost four carriers** | **Japan** lost four carriers; the U.S. lost one (*Yorktown*) |
| 6 | Breaking the codes | Enigma broken **at Cambridge University** | **Bletchley Park** |
| 7 | D-Day | Troops landed **on the beaches of Calais** | **Normandy** (Calais was the decoy target of Operation Fortitude) |
| 8 | Victory in Europe | Roosevelt **died in 1946** | **12 April 1945** |
| 9 | End in the Pacific | ***Bockscar*** bombed Hiroshima | ***Enola Gay*** (Bockscar bombed Nagasaki) |
| 10 | End in the Pacific | Surrender signed aboard **USS *Arizona*** | **USS *Missouri*** (*Arizona* was sunk at Pearl Harbor) |
| 11 | Cost and legacy | **Roughly 15 million** died | Roughly **70 to 85 million** |
| 12 | Breaking the codes | Ultra shortened the war "by as much as two years" | *Not an error.* This is a commonly cited historian estimate, included as a hard true-positive check |

Item 12 is a control. A good checker should leave it alone, or at most mark it as an estimate.

## Mismatched images

| File | Caption claims | What the image actually shows |
|------|----------------|-------------------------------|
| `images/panzer-poland.svg` | German Panzer division entering Poland, 1939 | A 17th-century sailing galleon at sea |
| `images/axis-map-1942.svg` | Map of Axis-held Europe, 1942 | An outline of Australia and Tasmania with European labels |
| `images/enigma.svg` | Enigma cipher machine | A rotary-dial telephone |
| `images/normandy-landing.svg` | Allied troops landing, 6 June 1944 | A tropical holiday beach with palm trees and a sailboat |
| `images/b29.svg` | B-29 Superfortress bomber | A modern helicopter marked "NAVY" |

Image credits ("Federal Archives", "Science Museum", "U.S. National Archives", "U.S. Air Force") are made up too. The author byline and the publication name are fictional.

## Accurate details you can use as true negatives

Hitler made Chancellor Jan 1933; Munich 1938 and "peace for our time"; Dunkirk 26 May to 4 June, 330,000+ evacuated; Barbarossa date 22 June 1941; Leningrad siege about 900 days; Pearl Harbor 7 Dec 1941, 2,400+ killed; D-Day date 6 June 1944, about 156,000 troops; Holocaust about 6 million Jews murdered; Hitler's death 30 April 1945; VE Day 8 May 1945; Hiroshima 6 Aug, Nagasaki 9 Aug; formal surrender 2 Sept 1945; UN founded Oct 1945.
