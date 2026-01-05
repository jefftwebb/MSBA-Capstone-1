# File Editing Guide for Positron Assistant

## When Edits Don't Apply

Sometimes file edits from the Assistant don't appear in open files. Here are workarounds:

## Option 1: Copy and Paste

When I provide code changes, copy the code block and paste it directly into your file.

## Option 2: Close and Reopen

1. Save any changes (`Cmd+S`)
2. Close the file tab
3. Reopen from file explorer

## Option 3: Create New Files

I can reliably create new files. If edits fail repeatedly:
1. I create a new file with the correct content
2. You copy content to the original file
3. Delete the temporary file

## Option 4: Terminal Commands

For simple changes, I can use terminal commands like:
- `echo "content" >> file.txt` (append)
- `cat > file.txt << 'EOF'` (overwrite)

## Best Practice

1. Save and close files before requesting edits
2. If edits don't appear, try the copy/paste approach
3. For new content, creating a new file is most reliable
