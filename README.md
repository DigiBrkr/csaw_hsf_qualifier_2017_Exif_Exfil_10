# exif_exfil
10 points
>Alright, this is your first real case.
>An (sic) renowned hacker, Herbert Hadimioglu (handle of "Wicked") is suspected of worming through government devices and has been avoiding arrest.
>He just recently posted a picture of himself. If you can find where he took the picture, we can detain him.
>Maybe look into how to view Exif data?

## Solving it

This was by far the easiest challenge in the whole CTF.
Based on the instructions we know we need to look at the [Exif data](https://en.wikipedia.org/wiki/Exif) of this image:

![image](https://github.com/DigiBrkr/csaw_hsf_qualifier_2017_Exif_Exfil_10/blob/master/exif_exfil.jpg?raw=true)

The easiest way to do that is simply looking at the properties of the image.
That gets us this:

![image](https://github.com/DigiBrkr/csaw_hsf_qualifier_2017_Herbert_10/blob/master/Screenshot.PNG?raw=true)

`flag{l0cation_locati0n_location}`

## Other writeups of this problem

[csaw-hsf-2017-writeups/exif_exfil-10](https://github.com/ecx86/csaw-hsf-2017-writeups/tree/master/exif_exfil-10)
