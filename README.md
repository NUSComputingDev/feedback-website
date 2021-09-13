# feedback-website
Source code for the 24th MC anonymous feedback portal

## Contents

The folder hierarchy is structured as follows:

```
|- feedback-website
    |- html
        |- index.html
    |- js
        |- app.js
    |- styles
        |- index.css
```

## Usage
To run this repo locally, clone this repository and `cd` into it:

```bash
git clone https://github.com/NUSComputingDev/feedback-website.git
cd feedback-website/html/
```

Start a `localhost:8080` server:

```bash
python -m http.server 8080
```

Open a browser and visit `localhost:8080/index.html` and you should see the app loaded up.

If you check the developer panel, it should have the message `"App loaded."` printed to console.