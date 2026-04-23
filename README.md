# cursor-portfolio
Personal Portfolio Project
Okay so I suppose this is where I'm supposed to describe that I did.
I've installed Claude Code and Codex as per instruction.
The steps I've took was, after opening the email, I promptly install Cursor IDE, registered an account, opened cursor, found the extension tab (View > Extensions) and I added Claude Code first, and afterwards Codex - Open AI's coding.
Once that's done, I created the public repository on GitHub Web, but since I've never done this before, step 5 was a bit tricky, so what I ended up doing is that I searched "open github repository in cursor" and found this link https://www.youtube.com/watch?v=-YNCOhHi8bk.
I promptly followed the instruction in the video, which is just typing the line "can you clone this repo *github repo link*". But a problem occured in which, it turns out I need git.
Cursor came back with the error "git isn’t installed (or not on PATH) on your machine right now, so I can’t run git clone yet." And gave me two options, 1 is to install Git for Windows, and 2 is to download the repo ZIP, since option 1 is simpler, I ended up installing git.
When installing git, on the installer, the prompt "Choosing the default editor used by Git" came up, and since I didn't know which is better, I googled which one is best for beginner, and found out that GitHub Desktop is the most beginner friendly, which lead me to install GitHub Desktop and chose it as my default editor.
Finished installing git, went back to cursor and entered the line "okay i've installed Git" and cursor retried to clone it again, but it's still blocked, and this message came up "Still blocked in this terminal session: git is not found on PATH yet.

This usually means Cursor’s terminal needs a restart to pick up the new PATH after installation.

Please do one of these, then I’ll clone immediately: 
Restart Cursor, or Open a new terminal in Cursor and run git --version once."
I tried the first option, simply restarted Cursor, and then I entered the line "okay i've restarted cursor" in which cursor tries to verify it again, which ended up working.
And that's it.

Thanks for reading.
