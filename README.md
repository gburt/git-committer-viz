Git Committer Viz
================

Simple tool that should work on any git repo and generate a
visualization of committers.

See some example output: http://banshee.fm/~gburt/commit-charts/


Usage:

    # Add the script to your PATH
    PATH = $PATH:~/Projects/git-committer-viz

    # From within any git repo, you can run
    committer-timeline -- po/ > translator-timeline.html
    committer-timeline -- src/ > committer-timeline.html
    committer-timeline > timeline.html
