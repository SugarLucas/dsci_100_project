# DSCI100-project-g28
This is group 28's project! 

We want to answer a predictive question: Can we use a song's traits to predict whether a song in 2010-2019 on Spotify is explicit or not? Answering this question is noteworthy because Spotify has an explicit content filter that allows users to filter out songs containing language that may be considered offensive to children. However, Spotify's explicit content tag is based on information provided by the rights holder. As a result, not all tracks with explicit content are properly labelled and users must manually report those they missed. Hence, this study is set out to investigate an alternative solution to predict and thus label whether a song may be explicit or not. A rigorous answer to this question could help Spotify enhance its explicit content filter and improve user experience.

The columns of the data set are as follows:
artist: artist of track
song: name of track
duration_ms: duration of track in milliseconds
explicit: The lyrics or content of a song or a music video contain one or more of the criteria which could be considered offensive or unsuitable for children.
year: release year of the track
popularity: the higher the value the more popular the song is
danceability: how suitable the track is for dancing based on tempo, rhythm stability, beat strength, and overall regularity. 0 = least danceable, 1.0 = most danceable.
energy: measure from 0.0 to 1.0, a perceptual measure of intensity and activity
key: key song is in. Integer maps to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C#/D♭, no key = -1
loudness: overall loudness in decibels
mode: modality (major or minor). Major = 1, minor = 0.



For the sake of the project, we will only use songs with a single genre.
