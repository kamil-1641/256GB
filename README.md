## Disclaimer: research content

The repository contains 256GB of data compressed into a 308MB tar file (256GB.tar). The file contains 2 smaller tar archives (128GB1.tar and 128GB2.tar), of which each contains 2 smaller tar archives (64GB1.tar and 64GB2.tar) of which each contains 2 smaller tar archives, this continues down till hitting 1GB, where the contained archives are of .tar.gz type, and contain compressed 1GB text files full of letters "a", for a total of 256 1-gigabyte text files in it's final layer.

256GB_109layers.tar contains this file under 100 additional layers of .tar archives. 256GB_509layers additionally compresses that file once more to shrink it down to 6.92MB and contains it under 500 more layers of .tar archives.

Fully unpacking either of the files would result in using up 256GB of space, and could take a really long time!

The files are meant only for research on detection of malicious archives.

## In compliance with terms of service

https://docs.github.com/en/site-policy/acceptable-use-policies/github-active-malware-or-exploits (07.08.2024)

"Note that GitHub allows dual-use content and supports the posting of content that is used for research into vulnerabilities, malware, or exploits, as the publication and distribution of such content has educational value and provides a net benefit to the security community."

As recomended in the GitHub Terms of Service, the potentially harmful content had been clearly identified and described, and a preferred method of communication had been provided.