# spectable fails to run because of permission issuies

error:

An error occurred while taking a screenshot.
KWin screenshot request failed:
The process is not authorized to take a screenshot
Potentially relevant information:
- Method: CaptureScreen
- Method specific arguments: "DP-3"


solution:

cd .local/share/applications

then delete

org.kde.spectacle.desktop

notes:

not sure if it is because I have firejail or apparmor installed.
