# Cosmic
A website for cool space stuff :D

## Contents
- [About](#about)
- [Hosting it yourself](#running-it-yourself)

## About
The site currently has a homepage and a weather page.

The [weather page](/weather/index.html) shows the weatger conditions in space, amd the.page changes slightly or a lot depending on some conditions.

For exanple, if solar is high, the oage turns red-ish!

And it also has some other smol effects too :page

## Running it Yourself
It's pretty simple to run the page yourself since it just serves static files ;)

For starters, install Python if you haven't already (pretty unlikely):
**Linux**
```bash
apt install python git
```

**Windows**
```powershell
winget install -e --id Python.Python.3; `
winget install -e --id Git.Git;
```

Clone this repository:
```bash
git clone https://github.com/disgustalt/Cosmic.git
```

Move to directory:
**Linux**
```bash
cd ./Cosmic
```

**Windows**
```powershell
cd .\Cosmic
```

Serve the page:
```bash
python -m http.server 8080
```

The page should be at `http://localhost:8080`! :v
