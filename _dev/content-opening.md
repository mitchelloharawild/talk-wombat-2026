# Opening slides: content and structure

Slot: 8:45–9:00 am Tue 1 Dec, Room 8.03 (15 min, pretalx lists Mitchell as speaker), straight into Rob's keynote.

## Core idea

**Ten years of WOMBAT.** February 2016 at Melbourne Zoo → December 2026. The seventh event, as there wasn't one every year, so say "10 years", not "10th WOMBAT" (the 2019 site calls itself the third).

The line through the day: two 2016 speakers are back.

* **Hadley Wickham**: 2016 keynote → 2019 keynote → 2026 conversation (and Monday's tutorial)
* **Rob Hyndman**: 2016 talk "Making forecasting easier" and session chair → 2026 keynote

Left implicit: the slides do not call this out.

## Proposed structure

Housekeeping early, memory lane last: the energy builds into the keynote.

| # | Slide | Content | Visual / style | Min |
|---|---|---|---|---|
| 0 | Title (holding) | Welcome to WOMBAT 2026 | existing title slide | – |
| 1 | Acknowledgement of Country | 2026 wording, both flags | `.country` | 1 |
| 2 | Welcome | What WOMBAT is, who is in the room | `image-right`, 2025 crowd | 1 |
| 3 | Organising committee | six people, photos and roles | person cards (new, small CSS) | 0.5 |
| 4 | Safety and help | evacuation, code of conduct, who to ask | callouts | 1.5 |
| 5a | Recording and social media | filming, opting out, hashtag, Bluesky, posting etiquette | callouts | 0.5 |
| 5b | Badge stickers | badge illustration and sticker legend | two columns | 0.5 |
| 6 | Online | website, live program, Wi-Fi | callouts | 0.5 |
| 7 | **Ten years of WOMBAT** | section divider, "2016 – 2026" | `#` divider | – |
| 8 | Each WOMBAT in turn | website snapshot (year, theme, venue, keynote), then a few photos | `.past-event`, then photos |  |
| 8a | 2016 photos | the room, then "Were you there?" | `.image-full`, stills `2250` and `2403` |  |
| 8b | 2017, 2019, 2024, 2025 photos | photo walls | `.photo-slide` |  |
| 8c | 2022 photos | **needs your photos** | `.photo-slide`, commented out in `index.qmd` |  |
| 8d | 2026 | website snapshot, no theme, no photos yet | `.past-event` |  |
| 14 | Today | the program | existing `## Today's program` | 1 |
| → | Keynote | existing session slide | | |

If short on time, cut photo slides first, then merge 3 into the closing thanks (2025 showed the committee up front).

### Alternatives considered

* Memory lane straight after the Acknowledgement: stronger start, but latecomers miss it and housekeeping deflates the run into the keynote.
* Live `background-iframe` of past sites: needs Wi-Fi and breaks the self-contained deck. Use screenshots, linked.

## Past events

Source: <https://wombat.numbat.space/about/past-events.html>, checked against each site. Screenshots are in `opening/websites/`; each links to `https://wombat.numbat.space/<year>`.

| Year | Theme | Dates | Venue | Keynote |
|---|---|---|---|---|
| 2016 | Making Data Analysis Easier | 18–19 Feb | Melbourne Zoo | Hadley Wickham |
| 2017 | Reproducible Data Analysis | 29 May – 2 Jun | NAB, 700 Bourke St | Yihui Xie |
| 2019 | Making Data Analysis Easier | 28–29 Nov | State Library Victoria | Hadley Wickham, Galit Shmueli |
| 2022 | Communicating with Data | 6–7 Dec | Royal South Yarra Lawn Tennis Club | Amanda Cox |
| 2024 | Open the World with Open Source | 22–23 Oct | Monash, Melbourne CBD | Michael Lawrence |
| 2025 | Designing Data Driven Discoveries | 29–30 Sep | Monash, Melbourne CBD | Nicola Rennie |
| 2026 | *none on the website* | 30 Nov – 1 Dec | Monash, Melbourne CBD | Rob Hyndman |

Fun in the progression:

* 2016, 2017, 2022 and 2024 share one website look, with the same wombat plot
* 2019 reused the 2016 theme
* 2022 was a virtual tutorial day plus 60 people in a tennis club
* 2024 gave WOMBAT mugs to the first 40 workshop registrations
* From a zoo, to a bank, a library, a tennis club, then home to Monash

The 2026 capture is the home page as it looked on 25 Nov.

## 2016 at the zoo

From the 2016 site (`~/github/WOMBAT2016`):

* Bong Su room. "Turn off at the orangutans"
* Lunch listing: "Orangutans at 12:00, Gorillas at 12:30"
* "Free zoo time" both afternoons, "Twilight music" on the Friday evening
* Registration included zoo entrance; sold out, with a waiting list
* Keynote advertised as "EDA = visualise + manipulate + model", delivered as "Managing many models" (purrr, broom, nested data frames, cupcake recipes)
* Hadley was "Chief Scientist, RStudio" (now Posit)
* Also spoke in 2016 and involved in 2026: Di Cook, Nick Tierney (tutorials)
* Recording: <https://www.youtube.com/watch?v=uc4Tx8d_ZZg>

### Video stills

1920 × 1080, in `opening/stills-2016/`, named by seconds into `keynote_hadley_wickham.mkv`.

| Still | Shows | Use |
|---|---|---|
| `0005-title-card` | Event title card | unused |
| `2250-room-wide` | Whole room, screen, roof beams, crowd | 8a (hero) |
| `2403-crowd-front-wide` | Crowd from the front, backpacks | 8a |
| `2575-front-row-wide` | Front row, audience question, bamboo | spare |
| `1424-crowd-back-jungle` | Crowd against the greenery | spare |
| `2258-crowd-front` | Crowd, taking notes | spare |
| `2991-crowd-front-late` | Closer crowd | spare |
| `0220-front-row-projector` | Front row and projector | spare |
| `1272-crowd-back-wide` | Backs of crowd, dark; text overlays well | 7 spare |
| `0500-crowd-back-screen` | Crowd and screen from behind | spare |
| `0985-crowd-side-ceiling` | Crowd side-on | spare |
| `2309-crowd-front-close` | Crowd, individuals prominent | spare |
| `2466-question-standing` | Standing attendee with microphone | spare |
| `1171-hadley-pointing` | Hadley pointing at purrr code | spare |
| `1918-laptop`, `2205-note-taking` | Details, no faces | texture tiles |

The stills show identifiable attendees. The recording is already public; prefer wide shots over single faces.

## Photos by year

| Year | Have | Need |
|---|---|---|
| 2016 | stills, zoo map, speaker headshots | any candid or zoo photos |
| 2017 | crowd, question, Nick Tierney | – |
| 2019 | crowd, tea, Di Cook, break | – |
| 2022 | **none** (Amanda Cox headshot only) | tennis club |
| 2024 | workshop crowd, Elio Campitelli | – |
| 2025 | 9 in `WOMBAT2025/img/thank-you/`; `~/Downloads/PXL_20250930_052152856.jpg` (full room); `img/workshop.jpg` is the same shot as `IMG_4538` | – |

Best 2025: `IMG_4538` (full room), `4492` (crowd), `4473` (break), `4679` (social), `4652` (Rob on the conversation panel). Drop yours in `_dev/opening/photos/<year>/`. If a year stays empty, its website screenshot stands alone.

## Reused from 2025

* Evacuation: "Woop woop woop - evacuate now", stairs beside the lifts to the lobby, assemble at the park to the west
* Code of conduct: be kind, respectful, considerate. Contacts in 2026: Di Cook, Rob Hyndman, Michael Lydeamore, Mitchell, Krisanat
* Email: <buseco-ebs.wombat@monash.edu>
* Wi-Fi: `eduroam`, `Monash Guest Wi-Fi`
* Social hour and hashtag, details below

Changed for 2026:

* Committee: Mitchell O'Hara-Wild (general chair), Krisanat Anukarnsakulchularp (program chair), Maliny Po (visitor logistics), Janith Wanniarachchi (webmaster & AV lead), Elio Campitelli (social media), Tina Rashid Jafari (volunteers)
* Badge stickers: red dot = no photos, green = looking for work, blue = hiring, pronoun stickers. **In 2025 green marked organisers**, so do not reuse that line
* Hashtag `#WOMBAT2026`
* Bluesky: [@wombat.numbat.space](https://bsky.app/profile/wombat.numbat.space)
* Live program: <https://wombat.numbat.space/live.html>

## Decided

* Evacuation procedure: same as 2025
* Recorded: yes. Social event: yes, **venue and time still to add** (TODO in `index.qmd`)
* No mention of celebrating Rob's career; no other opening speakers planned
* No then-and-now slide: avoid drawing that much attention to it
* 2016 photos are stills `2250` and `2403` full-bleed; no 2016 photo wall
* No title card recreation or 2016 program (zoo map) slide
* Live program: website embedded in a slide
* Photos follow each year's website snapshot: all built except 2022, which has none yet
