# Exiftool
ExifTool is a free and open-source software program for reading, writing, and manipulating image, audio, video, and PDF metadata.

download exiftool here.
https://www.sno.phy.queensu.ca/~phil/exiftool/

script
////TIF check and output to csv file////////////////////Copy paste into terminal after cd directed into folder
/////////////


exiftool -csv -FileSize -AlphaChannelsNames -ColorSpace -ProfileDescription -ImageSize -ICC Profile Name  -XResolution -YResolution -LayerCount -Compression *.tif> NAMEofOUTPUT.csv
