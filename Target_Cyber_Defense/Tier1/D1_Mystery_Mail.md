# D1. Mystery Mail (100)
**Objective:** Identify the sender's IP address using the attached email file.

## Challenge Materials
- File: `extortion_note.eml`

## Resources and Notes
- Tool: Text editor (Mousepad on Kali Linux)

## Write-Up

The email file was opened using a text editor (Mousepad in Kali Linux) to inspect its contents. 
There were 3 IP addresses in the email headers.

Based on standard email structure, the original sender's IP address is in the first **Received** header, which was located on the fourth line of the file.

**Flag:** `252.44.98.29`

![extortion_note.eml](./images/D1.png)