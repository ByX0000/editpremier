EditPremier
AI-Powered Video Editing with Claude Code
Turn your raw footage into polished rough cuts — automatically. EditPremier uses Claude Code to analyze video footage, generate transcripts, and build ready-to-import timelines for Adobe Premiere Pro, Final Cut Pro, and DaVinci Resolve.

Based on the open-source ButterCut project.


What It Does

Transcribes audio using WhisperX
Analyzes video frames and generates visual transcripts
Creates rough cuts with intelligent clip selection
Exports native timeline formats (FCPXML, Premiere XML)
Interactive workflow — Claude asks your preferences and makes editorial decisions

Demo
Show Image
Quick Start
bash# Clone
git clone https://github.com/ByX0000/editpremier.git && cd editpremier

# Open Claude Code
claude

# Install dependencies
> Install ButterCut
Claude will handle system checks and install Ruby, Python, FFmpeg, and WhisperX as needed.
For manual setup → docs/installation.md
Usage
1. Create a Library
A library organizes your footage with audio/visual transcripts.
You: "I want to build a new library"
Claude: [Guides setup → processes videos → generates transcripts]
2. Create a Rough Cut
You: "Let's create a new roughcut"
Claude: [Analyzes footage → asks preferences → exports timeline]
You choose focus, duration, pacing, and target editor. Claude handles the rest.
3. Import & Edit
Open the exported XML/FCPXML in your editor and refine from there.
Requirements

Claude Code
Ruby, Python 3, FFmpeg, WhisperX
Final Cut Pro / Adobe Premiere Pro / DaVinci Resolve

Credits
Originally built by barefootford. Inspired by work from Chris Hocking and Andrew Arrow.
License
MIT
