# ChordPro Preview for Atom.io

Show the rendered ChordPro song to the right of the editor. The ChordPro format allows for song information to be expressed in tags delinated by curly braces.

The goal is to enable preview for `.chordpro`, and `.onsong` files.

### Chordpro Formatting
#####{title:} or {t:}
The title of the song.

#####{subtitle:}, {st:} or {su:} 
The artist name or any other byline information. You can specify multiple artists by separating names with a semi-colon. - Kim Walker-Smith; Chris Quilala

#####{album:}
The name of the album where the song is located.

#####{artist:} or {a:}
The artist name or any other byline information. You can specify multiple artists by separating names with a semi-colon. - Kim Walker-Smith; Chris Quilala

#####{author:}
The name of the person who created the chord chart. This is displayed at the bottom of the chord chart and in lyrics projection.

#####{key:} or {k:}
The key of the song written as a key with enharmonic preference and an optional "m" to indicate minor. - alphabetic, e.g. Bb or Em

#####{capo:}
The capo to set as number of frets - numeric

#####{tempo:}
The beats per minute (BPM) - numeric

#####{time:}
The time signature - numeric beat over bar e.g. 3/4

#####{duration:}
The song length for autoscroll - seconds or mm:ss

#####{book:}
The name of the book or books to place the song into. This is a comma-delimited list of book names into which the song will be placed. If the book does not exist, it will be automatically created.

#####{number:}
The number of the song - numeric, use for hymns, years, etc. You can sort songs by the number for reference.

#####{flow:}
The arrangement of sections - list of section labels. See Flow for details on arranging the flow of a song.

#####{midi:}
The MIDI commands to send when the song is viewed. See MIDI Syntax for how to express MIDI commands as text in OnSong.

#####{midi-index:}
The MIDI commands that will trigger this song to be opened in the Song Viewer. See MIDI Syntax for how to express MIDI commands as text in OnSong.

#####{pitch:}
The notes to play when using the Pitch Pipe feature.

#####{keywords:} or {topic:}
The list of tags to use with topic search. See Topics for more information on browsing by topic.

#####{copyright:} or {footer:}
\Specifies copyright footer text to appear at the bottom of the page or lyrics projection.

#####{ccli:} 
The CCLI number of the song.

#####{restrictions:} 
The rights management for the song's comma-delimited list of restrictions. See Restrictions for details on setting restrictions for your song.
