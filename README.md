# ass-subtitle-font-changer
Change the font for your .ASS subtitle files

NOTE:
Don't forget to backup your .ASS file in case something goes wrong.

HOW IT WORKS:
- Download the .CPP file
- Open CMD as administrator
- Go to the .CPP location on CMD (Using cd, of course)
- Type `g++ -o assFontChanger assFontChanger.cpp`
- Type `assFontChanger subtitleFileName.ass fontName`

Once it's done, the changes should be applied to the original subtitle file, that's why you need to have backup in case something goes wrong.

EXAMPLE USAGE:
`assFontChanger 1718390888844.ass Arial`

IMPORTANT CLAIMER:
I used [ZaifSenpai](https://github.com/ZaifSenpai)'s code as reference to create a working code for myself, kudos to him for the reference.

I just wanted to share this code as I only could see [ZaifSenpai](https://github.com/ZaifSenpai)'s work on the field, you can always reach me on Discord for anything related to this: `tolgaflashtr`
