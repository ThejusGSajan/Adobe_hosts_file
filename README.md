# Sync Adobe Host File Blocklist
---
Certain members of the high seas using "definitely genuine" Adobe software might still face pesky pop-ups that ruin their workflow. Something along the likes of "unlicensed" or "disabled" while reading a PDF or editing a snapshot or montages should ring a bell.

This is a simple executable that automates the processes mentioned [here](https://www.reddit.com/r/GenP/wiki/redditgenpguides/#wiki_.28....29_1.FE0F.20E3_host_file_block_list_.28updated_regularly.29). 

### Features
---
-  Keeps those annoying "unlicensed" and "disabled" pop-ups from ruining your creative mood
- This thing is smaller than your average cat meme. It runs fast, does its job, and gets out of the way.
- Only Adobe telemetry gets blocked. Your Netflix binge and Reddit feed remain safe.

### How to use
---
1. Download the latest release.
2. Use the following command in PowerShell (as admin):
`Stop-Process -Name “Adobe Desktop Service” -force`
Note: You might get an error message starting with: "Stop-Process: Cannot find a process with the name..." like in the image. Ignore and continue. ![ignore error message](https://b.thumbs.redditmedia.com/kbmRrE_CMsxMdZISJ1zQ-GsP2mY3gJlsrAHpWYs3QTk.png)
3. Run the exe.

#### Notes
---
1. The hosts file blocklist is kept updated frequently. Whenever you face pop-ups, running the latest release should populate the `hosts` file with the latest IPs to be blocked. To verify whether the `hosts` file has been updated or not, search for "Last update" within the same.
2. The exe will most probably be flagged as a trojan by the antivirus software running in your system (or even Windows Defender) but rest assured that it's a false positive. Temporarily pause real-time scanning or whitelist the exe to run it. (Don't forget to toggle real-time scanning back on afterwards, if you'd paused it.)

### Credits
---
- [Ignacio Castro](https://github.com/ignaciocastro/a-dove-is-dumb) for keeping the list updated.
- The people behind [r/GenP](https://www.reddit.com/r/GenP/)


### Disclaimer
All resources provided by this software are strictly for **educational purposes**. This software is provided "as is" with no express or implied warranties, is **not affiliated** with or endorsed by Adobe Systems Incorporated, and is not intended to bypass or modify any licensing protections. By using this software, you accept full responsibility for your actions and compliance with all applicable terms, laws, and regulations. You are responsible for ensuring you have a valid license for all software used with this tool. The developer will not be held liable for any damages, legal consequences, or other liabilities arising from its use.