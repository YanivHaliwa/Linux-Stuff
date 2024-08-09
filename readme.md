# System Management and Utilities LInux

Welcome to my collection of simple yet powerful Linux tools! These are just everyday scripts and commands I've put together to make life easier when working with Linux. Whether you're managing your system, handling files, or doing some network stuff, you'll find something here to save you time and effort.

Think of these as your handy toolbox for common Linux tasks. They're not fancy – just practical. I use these regularly to simplify my workflow, and I hope they'll do the same for you.


## System Operations
- **update:** Updates and upgrades system packages, including fixing broken dependencies.
- **clean:** Cleans up unused packages and dependencies.
- **sysa:** Manages system services by enabling or disabling them based on the provided arguments.
- **resetnet:** Resets network settings and services.
- **sysinfo:** Displays system information such as hostname, user ID, version, and issue.
- **myusers:** Lists all users and those with home directories.

## Package Management
- **aptsi:** Searches for installed packages with an option to filter for manually installed ones.
- **psearch:** Searches for packages with options to include installed packages and outputs their statuses.
- **updatepips:** Upgrades all installed pip packages and logs any errors.
- **installdeb:** Installs `.deb` packages using `dpkg` and resolves dependencies.
- **aptf:** Installs packages listed in a specified file.

## File and Directory Operations
- **fil:** Analyzes a given file using various tools like `stat`, `file`, `mimetype`, and more.
- **cati:** Displays the content of an executable file.
- **loc:** Searches for files in a specified directory based on a regex pattern.
- **movef:** Moves files from subdirectories to a destination directory and optionally deletes the source folders.
- **search:** Searches for files or folders based on a specified name.
- **txtf:** Locates specific text files in the given target folder.

## Text Processing and Manipulation
- **swf:** Searches for a word or pattern in a specified file.
- **swd:** Searches for text in files within a specified directory.
- **hashline:** Joins lines in a file into a single line and saves it.
- **dupl:** Finds and consolidates duplicate lines in a file.

## Encoding and Decoding
- **encode:** Encodes text into various formats including base64, hex, ROT47, and more.
- **decode:** Decodes various encoded text formats including base64, hex, ROT47, Caesar Cipher, etc.
- **haid:** A Hash Analyzer and Identifier script that helps identify hash types using multiple tools (hashid, Name-That-Hash, hash-identifier, and haiti) and provides relevant information for cracking, including Hashcat modes and John the Ripper formats.

## Network and Security
- **getlink:** Extracts and prints all links from the provided webpage URL.
- **portf:** Scans for open ports on a given IP/domain and identifies services running on them.
- **nmapy:** Automates running initial and detailed Nmap scans on a given IP or domain.
- **dir_finder:** Searches and identifies valid directories on a given domain using a wordlist.
- **port:** Checks if a port is in use and offers to kill the processes using it.
- **soclisten:** Listens on a specified port using `socat`.
- **socremote:** Connects to a remote host using `socat`.
- **mvenom:** Creates a payload with `msfvenom` based on user input.

## Translation and Subtitles
- **trsub:** Downloads and translates subtitles for given video files or directories. for now its to hebrew but you can edit as you want.
- **trw:** Translates given text to Hebrew using various AI models.
- **trf:** Translates subtitle files to Hebrew using different AI translators.
- **vidsubs:** Matches video files with their respective subtitle files.
- **whis** Transcribes audio files using the Whisper model, supporting both CPU and GPU execution, with options to specify the model and language. Outputs the transcription in SRT format with timestamps.
- **ytsub:** Downloads and processes subtitles from YouTube videos, with options to specify language and output format.


## Miscellaneous
- **say:** Converts text to speech and plays it in Hebrew.
- **gitupdate:** Commits changes to a Git repository and pushes them to the remote master branch.
 


 