# Eixftool
ExifTool is a free and open-source software program for reading, writing, and manipulating image, audio, video, and PDF metadata.

download exiftool here.
https://www.sno.phy.queensu.ca/~phil/exiftool/

script
////TIF check and output to csv file
exiftool -csv -FileSize -AlphaChannelsNames -ColorSpace -ExifImageWidth -ExifImageHeight -ImageSize -ICC Profile Name -XResolution -YResolution -LayerCount -Compression *.tif> NAMEofOUTPUT.csv
