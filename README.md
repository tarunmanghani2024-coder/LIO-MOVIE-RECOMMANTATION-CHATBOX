
# LIO-MOVIE-RECOMMANTATION-CHATBOX

## Overview
Lio Movie Chatbot is a fullscreen Tkinter-based Python application that recommends age-appropriate movies based on user mood, age group, language preference, and personality quiz responses. It maps answers to 8 genres (A-H) using a tally system and displays clickable YouTube trailers.[11]

## Features
- Fullscreen dark blue theme (#191970) with cyan buttons (#00CED1)
- Personalized flow: username → mood (Good/Bad/Okay) → age group → language (Hindi/English) → 2 personality questions
- Tally system tracks preferences across 8 genres: Romance (A), Thriller (B), Comedy (C), SciFi/Fantasy (D), Historical/Crime (E), Marvel (F), DC (G), Indian Movies (H)
- Age-appropriate recommendations (Under 15, Under 18, 18-25, 25+) with YouTube links
- Escape key toggles fullscreen; Restart/Exit buttons

## Genres & Sample Movies
| Genre | Code | Sample Movie | YouTube Link |
|-------|------|--------------|--------------|
| Romance | A | The Notebook | https://www.youtube.com/watch?v=FC6biTjEyZw [11] |
| Thriller | B | Inception | https://www.youtube.com/watch?v=8hP9D6kZseM [11] |
| Comedy | C | Superbad | https://www.youtube.com/watch?v=4eaZ_48ZYog [11] |
| SciFi/Fantasy | D | Interstellar | https://www.youtube.com/watch?v=zSWdZVtXT7E [11] |
| Historical/Crime | E | Sherlock Holmes | https://www.youtube.com/watch?v=Ih0iu80u04Y [11] |
| Marvel | F | Avengers: Endgame | https://www.youtube.com/watch?v=TcMBFSGVi1c [11] |
| DC | G | The Dark Knight | https://www.youtube.com/watch?v=EXeTwQWrcwY [11] |
| Indian Movies | H | 3 Idiots | https://www.youtube.com/watch?v=K0eDlFX9GMc [11] |

## Setup & Run
1. Clone repo: `git clone https://github.com/tarunmanghani2024-coder/LIO-MOVIE-RECOMMANTATION-CHATBOX.git`
2. Install: `pip install tkinter` (usually pre-installed)
3. Run: `python CODE-2.py` or call `start_main_chatbot()`
4. Press Escape to exit fullscreen[11]

## Config (lio_movie_chatbot.json)
- Version: 2.0
- Background: #191970, Button: #00CED1, Text: #FFFFFF
- Age groups: ["Under 15", "Under 18", "18-25", "25+"]
- Languages: ["English", "Hindi"][11]

## Tech Stack
- Python 3 + Tkinter for GUI
- webbrowser for YouTube links
- Custom genres dictionary with nested age filtering[1]

