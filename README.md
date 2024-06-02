# Cabrillo syntax highlighting

## Features

This extension enables syntax highlighting of the Cabrillo contest log file format.  The standard file extensions is CBR.

## What is the Cabrillo file format

Ever since software has become a part of amateur radio, there have been as many data formats as there have been ham radio software programmers.  The Cabrillo Specification was originally developed by Trey Garlough, N5KO to provide a method for consistent data formatting that sponsors could use in the submission of contest logs. Contest sponsors including CQ, ARRL, and DARC quickly supported the idea. More importantly and key to its viability, leading program authors such as K1EA, N6TR, K8CC, W5XD, EI5DI and others also embraced the concept.

Since its earliest days, the Cabrillo Specification has been the recognized gold standard for contest logs and has revolutionized the contesting world. It has enabled many contests to support electronic log submission and automate the log checking process. The WWROF administers the Cabrillo Specification on behalf of the contesting community.

Currently the Cabrillo contest log format is widely adopted as the standard format to import and export Radio Amateur contest logbooks between various software applications and to submit the log to the contest organisers.

A Cabrillo log file consists of a header and the actual QSO data.  The QSO data is depicted in a tabular format delimited by whitespaces.  The number of columns and field content is specific for each contest.  Below are a few examples for some of the most popular contests:

- [CQ WW DX Contest](http://www.cqww.com/cabrillo.htm)
- [CQ WPX Contest](http://www.cqwpx.com/cabrillo.htm)
- [CQ WPX RTTY Contest](http://www.cqwpxrtty.com/cabrillo.htm)

Example:

![sample](https://github.com/filipjonckers/cabrillo-syntax-highlighting-vscode/blob/master/images/sample.png?raw=true)

## About the author

Filip Jonckers is a licensed radio amateur since 1993 with the HAM radio callsign ON4FF (and previously ON1AFN).

## What is Amateur Radio

Radio amateurs can be found almost in every country and in various circles.
They represent a motley collection of backgrounds and professions. They have one thing in common: their passion for technology and for radio. Among them were the late King Hussein of Jordan, his fellow King Juan Carlos of Spain and the late Indian Prime Minister Rhajiv Ghandi. Carlos Menem, president of Argentina, also joined radio amateurs. But there is room for you too.

You too can become a radio amateur! You will then join the circle of friends of more than a million licensed radio amateurs worldwide.

## Requirements

None.

## Extension Settings

None.

## Known Issues

None at this time.

## Release Notes

### 1.0.2

Added support for QTC records to support WAE CW/SSB/RTTY Contest.

### 1.0.1

Initial release of Cabrillo file syntax highlighting extension for Visual Studio Code.

## Support and bug reports

Please report any issues via the GitHub repository.  Also any contributions are much appreciated.

## For more information

- [Cabrillo file format specifications](https://wwrof.org/cabrillo/)
- [Submitting An Electronic Contest Log by Sean Kutzko KX9X](https://www.arrl.org/files/file/Contest%20-%20General/Tutorials/Submitting%20An%20Electronic%20Contest%20Log.pdf)
- [GitHub repository](https://github.com/filipjonckers/cabrillo-syntax-highlighting-vscode)
