# manual-splitter
Building an audio dataset is cumbersome process. Having a tool that eases the steps for creating of appropriate dataset is necessary. By making splitting the audio files and having easier method to create transcription of many audio files would be the aim of this project

# Requirements
## File formats
As an audio dataset consists of audio file and its corresponding transcription, this application allows the modification of both types of files in TXT and MP3/WAV format. 
## Splitting capabilities
Since the main goal of this application is to make the splitting of the audio as easy as possibly while also validating or correcting the transcript text, we need to enable breaking down the data into correct size and set of words from the text copra.

### Audio splitting capability
* Enable WAV/MP3 file loading in the application.
* Enable preferred size to automatically *propose* cutting size.
* Enable ability to see the spectral distribution of the audio file in the GUI so that intelligently breaking down the file could be done heuristically.
* Enable marking the file into different files that indicate area to be cut.
* Enable a summary of the proposed splitting specification before cutting the file.
* Enable splitting the file into described format along with the text.

### Text splitting capability
* Enable loading CSV, TXT formats into the designated area.
* Enable editing the line so as to align the audio with text.
* Enable checking the number of lines to the number of audio file.

### Implementation Details
* Configuration file to read audio and text file simultaneously
* Load multiple files via configuration.
