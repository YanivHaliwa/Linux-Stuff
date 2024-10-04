# System Management and Utilities LInux

Welcome to my collection of simple yet powerful Linux tools! These are just everyday scripts and commands I've put together to make life easier when working with Linux. Whether you're managing your system, handling files, or doing some network stuff, you'll find something here to save you time and effort.

Think of these as your handy toolbox for common Linux tasks. They're not fancy – just practical. I use these regularly to simplify my workflow, and I hope they'll do the same for you.

the files linux_packs_needed.txt and pip_needed.txt - contain list of pip or apt packs that needed for some files to work.

## subtitle Management
- **whis**: Transcribes audio files using OpenAI's Whisper model with optional GPT enhancement.
- **whisi**: Transcribes audio using various Whisper models, including Ivrit-AI and faster-whisper versions.
- **movef**: Moves files from subdirectories to a destination directory.
- **vidsubs**: Matches video files with their corresponding subtitle files and renames them for consistency.
- **trf**: Translates text files (including subtitles) from English to Hebrew using various translation services, including ai models.
- **trw**: Translates words or phrases from English to Hebrew using multiple translation services, including ai models
- **trsub**: Downloads subtitles using subliminal and translates them. for multiple video files in folder (using script: trf,vidsubs)
- **ytsub**: Downloads a YouTube video and transcribes it (using script: whis).


## all search
- **dupl**: Bash script to remove duplicates from a file while preserving order.
- **loc**: Bash script to search for files in a directory using the `locate` command.
- **psearch**: Bash script to search for packages in the APT cache, with optional installed package filtering.
- **search**: Bash script for flexible file and folder searching with various options.
- **swd**: Python script to search for text in files within a directory, with regex support.
- **swf**: Python script to search for a word or pattern in a file, displaying line numbers.
- **txtf**: Bash script to find specific types of sensitive files in a target directory.

## cyber
- **haid**: A hash analysis and identification using multiple linux tools.
- **encode**: A versatile encoding utility for various formats and hash functions.
- **decode**: A comprehensive decoding tool supporting various encoding formats.
- **dir_finder**: An asynchronous directory discovery tool for web servers.
- **getlink**: A simple web scraper to extract links from a given webpage.
- **hashc**: A Bash script wrapper for Hashcat.
- **hashline**: A Python script for processing hash files.
- **johng**: A Bash script for cracking GPG-encrypted files using John the Ripper.
- **johnp**: A Bash script wrapper for John the Ripper.
- **johns**: A Bash script for cracking SSH private keys using John the Ripper.
- **johnw**: A Bash script for cracking shadow file passwords using John the Ripper.
- **johnz**: A Bash script for cracking ZIP file passwords using John the Ripper.
- **mvenom**: A Python script for generating payloads using Metasploit's msfvenom.
- **nmapy**: A Python script for automating Nmap scans with initial and detailed scanning phases.
- **portf**: A Python script for port scanning and service detection.
- **soclisten**: A Python script to set up a listening socket using socat.
- **socremote**: A Python script to establish a remote connection using socat.
- **vtf**: A Bash script for scanning files using VirusTotal's API.
- **vtu**: A Bash script for scanning URLs using VirusTotal's API.

## info
- **aptsi**: Search installed packages, optionally filter for manually installed ones.
- **bati**: Display binary file contents using bat.
- **cati**: Display binary file contents using cat.
- **fil**: Comprehensive file examination tool (type, hashes, content preview, etc.).
- **fiup**: Find files modified within a specified time frame.
- **lf**: List files or directories using lsd.
- **myusers**: Display user account information.
- **sysinfo**: Show system information (hostname, ID, version, etc.).

## System Management

- **update**: Updates and upgrades system packages, including fixing broken dependencies.
- **clean**: Cleans up unused packages and dependencies.
- **sysa**: Manages system services by enabling or disabling them.
- **resetnet**: Resets network settings and services.
- **active**: Checks if a specified process is running.
- **onewin**: Manages multiple windows of a specified process, keeping only one open.
- **port**: A Bash script for checking and managing processes using a specific port.

## Package Management

- **updatepips**: Upgrades all installed pip packages and logs any errors.
- **installdeb**: Installs `.deb` packages using `dpkg` and resolves dependencies.
- **aptf**: Installs packages listed in a specified file.
- **pix**: Installs a Python package using pipx with dependencies.
- **pixfile-i**: Installs multiple Python packages from a file using pipx.
- **pixfile-u**: Uninstalls multiple Python packages from a file using pipx.

## Battery and Power Management

- **batcon**: Analyzes battery discharge patterns and estimates remaining battery time.
- **batlow**: Monitors battery level and sends notifications for low battery or full charge.
- **batstat**: Logs battery state changes (charging/discharging) with timestamps.

## Utility Scripts and Tools

- **gitupdate**: Automates the process of updating a Git repository with new changes.
- **readqr**: Reads and decodes QR codes from image files using a barcode recognition API.
- **say**: Converts text to speech and plays it in Hebrew.
