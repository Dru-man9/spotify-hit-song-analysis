# spotify-hit-song-analysis

## The Question
What audio features actually drive a song's popularity?

## Dataset
1,686 high-popularity Spotify tracks (popularity score > 68) 
across 29 audio and descriptive features via Kaggle.

## Key Findings
- Energy, danceability, valence, and tempo all returned 
  Pearson r < 0.03 — none predict popularity
- 75% of top hits (popularity ≥ 90) cluster in 90–130 BPM
- Sad songs (valence 0.2–0.4) matched euphoric tracks at 
  76.4 avg popularity
- Latin and Hip-Hop are most danceable yet rank mid-table 
  in popularity — genre identity outweighs audio features

## Tools Used
- Claude for Excel (statistical analysis + pivot tables)
- Claude (To generate questions for a situation in order to put into Claude for Excel)
- Excel (data organization and visualization)

## Files
- `High_Popularity_Spotify_Data_Analysis.xlsx` — full analysis
- `high_popularity_spotify_data.csv` — raw dataset
