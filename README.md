# Exiftool
ExifTool is a free and open-source software program for reading, writing, and manipulating image, audio, video, and PDF metadata.

download exiftool here.
https://www.sno.phy.queensu.ca/~phil/exiftool/

script
////TIF check and output to csv file////////////////////Copy paste into terminal after cd directed into folder
/////////////


exiftool -csv -FileSize -AlphaChannelsNames -ColorSpace -ProfileDescription -ImageSize -ICC Profile Name  -XResolution -YResolution -LayerCount -Compression *.tif> NAMEofOUTPUT.csv


How to write metadata from csv to multiple files in directory in terminal, having csv in same directory: (The fullstop means current directory)
exiftool -csv="nameofcsv.csv" .

to remove all metada added if it was messed up:
exiftool -all= -overwrite_original .


///
exiftool -a -u -g1 a.jpg
Print all meta information in an image, including duplicate and unknown tags, sorted by group (for family 1).
this helps to distinguish from different xmps such as xmp-dc xmp-lr  (replace a.jpg with file)
