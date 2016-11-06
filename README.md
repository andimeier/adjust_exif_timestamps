
# adjust_exif_timestamps

A simple command line tool which adjusts the EXIF timestamps. This can also be used to synchronize multiple cameras.

## Starting points

### exiftool

    exiftool -DateTimeOriginal -d "%Y%m%d %H%M%S" IMG_0366.JPG

**Note:** use the EXIF field DateTimeOriginal (date/time when pictures was taken), not DateTime (which is the last modification time)

### jhead

Adjust timestamp with -ta switch
