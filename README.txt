FIXFRAME OWNER KIT  -  PRIVATE, keep it on your own devices
=========================================================

What is in this folder
  fixframe-owner.html    The owner tool. Open it with a double click (Chrome, Edge, Firefox or Safari on a computer).
                         It works offline and sends nothing anywhere.
  access.json            The list for GitHub: fingerprints of your 20 invitation codes. This is the ONLY file of
                         this kit that goes into your Fixframe repository.
  invitation-codes.txt   The 20 codes to print or keep, with a column for who got which one.

Switch it on
  1. Upload the files of fixframe-app.zip to your repository as usual (version 1.3.0).
  2. Upload access.json to the same repository (Add file -> Upload files -> Commit).
  3. New visitors are asked for an invitation code at once; phones that already use the app ask at their next
     check of the list (see Good to know).
  To open the app for everyone again: delete access.json from the repository.

Give out a code
  Owner tool -> Invitations: write the person's name next to a code, then "Copy invitation" (or "Copy code").
  Set the address of your app under Settings first, then the invitation text contains a link that fills in the code.

After 10 video exports (MP4 or GIF)
  The app shows a request number such as 07-1011-2615 and asks the user to contact the owner of the app with it
  (by phone, in person or however you agreed; the app sends nothing and shows no contact details).
    07    invitation number  -> you see who is asking
    1011  day and month      (10 November)
    2615  year and hour      (2026, 15 h)
  Owner tool -> Unlock code: type the request number, give the 8-digit code back. The tool keeps a log.

  Without the tool (phone calculator):
    (1011 + 2615) x (1037 + 7) = 3626 x 1044 = 3785544  ->  last four digits 5544, then 1037  ->  5544-1037
  In words: add the two 4-digit groups; add the invitation number to your owner number 1037; multiply;
  keep the last four digits; write 1037 behind them.

Block somebody, new codes, other limit, other owner number
  Change it in the owner tool, then "Download access.json" and upload it to GitHub (it replaces the old file).
  "New batch of 20 codes" can add 20 codes or replace all old ones, for example with every app update.

Keep a backup
  The tool remembers its data in the browser. Use "Save owner file" after changes and keep fixframe-owner.json safe;
  "Load owner file" brings everything back on another computer or browser.

Do NOT upload to GitHub: fixframe-owner.html, fixframe-owner.json, invitation-codes.txt.

Good to know
  - Phones that are already activated read access.json again only every few days (Settings -> "Check the list
    again every ... days", 7 by default; 0 = never after activation). A blocked code stops working at that phone's
    next check with a connection. A phone that stays offline keeps working until its 10 video exports are used up;
    then it needs an unlock code from you.
  - Since app version 1.5.2 a phone that was already activated does not notice a NEW access.json (for example one
    that switches the list on later) before its next check.
  - "Delete all guides and reset" in the app also clears the export counter (and the guides).
  - This keeps honest users in line. It is not copy protection: the app is a public web page, and a programmer
    can read how the check works.
