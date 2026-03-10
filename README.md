# Document-Converter-Suite

## Team Name: 

Crazy Coders

## Team Members: 

S.Mahesh Naik

C.Manoj Kumar


## Documentation

I got tired of using "free" online converters that were either covered in ads, forced me to create an account, or—worst of all—uploaded my private documents to their servers.

DocFlow is my solution to that. It’s a clean, fast, and entirely private document toolkit that runs 100% in your browser. Your files never leave your computer.

# What it actually does

I built this to cover the "daily essentials" of document management:

PDF Merging: Drag, drop, and combine. Simple as that.

The Sniper Split: Extract specific pages (like 1, 4-6) without breaking the rest of the file.

Fast Compression: Strips out the junk to make your PDFs email-ready.

Quick Conversions: Turns .docx files into PDFs without needing a Word subscription.

Custom Watermarking: Add "Confidential" or "Draft" stamps with total control over how they look.

Text Peeking: A quick way to grab metadata or raw text from a PDF without opening a full editor.

# How I built it

The goal was a "zero-install" experience. I used Tailwind CSS for the dark-mode/glassmorphism UI because it looks great and stays lightweight. The heavy lifting is done by PDF-Lib and Mammoth.js, which are incredible libraries for client-side file manipulation.

I also integrated a local Data SDK so your conversion history stays saved in your browser, not on a server database somewhere.

# Use it yourself

You don't need a build process or a server.

Download the code.

Open index.html in your browser.

Start converting.

# A note on Privacy

I’m a big believer in data sovereignty. Most "free" tools online are data-harvesting machines. DocFlow doesn't even have a "backend" in the traditional sense—it uses your own computer's processing power to do the work. If you're handling sensitive stuff like resumes, contracts, or IDs, this is the way to go.

# Want to help?

If you're a dev and have an idea for a new tool (maybe Image-to-PDF or a built-in signer), feel free to fork the repo and send a PR. I'd love to see where this goes.

## Features

### File Conversion

PDF to Word (.docx)

PDF to Excel (.xlsx)

PDF to PowerPoint (.pptx)

Word to PDF

Excel to PDF

PowerPoint to PDF

### PDF Tools

Merge Multiple PDFs

Split PDF into Separate Pages

### Tech Stack

Frontend Design: Canva (UI Design)

Backend: (Add your backend technology here)

File Processing Libraries: (Add libraries used, if any)

Deployment: Self-hosted / Local Server Compress PDF Files

Add Watermarks to PDF
