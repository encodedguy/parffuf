# parffuf
Fuzz many live hosts with ffuf in different modes
(In Development)

# Why to use?
When researchers hunt on BBPs, in the recon phase many hosts with 403,404,401,etc. status codes arises. Most of the times we only hunt on hosts with 200 status codes. But, this way we leave the surface which is Forbidden to see and maybe some files and directories are visible there after scanning with some generic wordlists.

# Installation
`git clone https://github.com/encodedguy/parffuf`

# Usage
`cd parffuf`

`bash parffuf.sh <hosts.txt> <wordlist.txt> <rate>`

# Recommendations
<hosts.txt>: should contains urls with newlines like this: https://rashahacks.com
<wordlist.txt>: should contain a wordlist with directories which are probable to see, or are technologically mapped.
<rate>: is in requests per second and depends on the program policy.

# Credits
@encodedguy
