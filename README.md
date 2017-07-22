# Extracting-Voice-Over-Audio-from-Witcher-3
How to extract voice over audio from Witcher 3 game
1. Open 'Batch Extraction' file with notepad or notepad++
2. Change the *set W3DIR='Your Witcher 3 install directory'* to where your Witcher 3 is installed
3. Change the *set W3Lang='use the language you wish to extract i.e. en is for english'*
4. Run the batch file by double clicking on it and let it run till it closes. It will create the w3speech folder where it will extract the audio files
5. The extracted files are in a proprietary format (AudioKinetic Wwise) - these need to be converted further.
6. Run the 'Convert to WAV and OGG' batch file.
7. 2 folders will be created Wav and Ogg - both containing their respective formats.
8. Use Witcher 3 dialogue excel file for finding the dialogue you want, use the ID number to finding the sound clip. In case if you don't have excel - extract the text files from 'w3dialog'
