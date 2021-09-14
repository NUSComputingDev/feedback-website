# feedback-website
Source code for the 24th MC anonymous feedback portal. You can find the site at [`feedback.nuscomputing.com`](feedback.nuscomputing.com).

> This codebase contains secure Firebase keys. Do NOT transfer control of the repo to anyone without authorization. Do NOT make this repo public, it's only to be kept private.

## Contents

The folder hierarchy is structured as follows:

```
|- feedback-website
  |- html/
    |- index.html
  |- js/
    |- app.js
  |- styles/
    |- index.css
```

> The main entry point to the website is through `index.html`.

## Usage
1. To run this repo locally, clone this repository and `cd` into it:

```bash
git clone https://github.com/NUSComputingDev/feedback-website.git
cd feedback-website/html/
```

2. Start a `localhost:8080` server:

```bash
python -m http.server 8080
```

If changes on your IDE are not reflected on your browser, change the port to anything else. It's probably a caching error. Changing the port will kill all operations on the previous port. Your changes should now be visible after a reload.

3. Open a browser and visit `localhost:8080/index.html` and you should see the app loaded up. 

> **Note:** If you check the developer panel, it should have the message `"App loaded."` printed to console.