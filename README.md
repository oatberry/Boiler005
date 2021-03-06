# Boiler005
*A BoilerKey enrollment to OTPAuth QR code conversion utility, written in golang*

Just make it run:
1. Go to [releases](https://github.com/igloo22225/Boiler005/releases)
2. Download the version for your system
3. Run it (from Terminal/Command prompt if your system doesn't automatically open it)

Build from source:
1. Install golang if you don't already have it
2. Run 'go get -u github.com/skip2/go-qrcode/'
3. Run 'go get -u github.com/skratchdot/open-golang'
4. With your current directory set to the source, run 'go build'

### A note on security
Assuming you delete the .png image generated by the application, you use a well-written 2fa application, and your computer isn't compromised, this is likely no more open to compromise than existing solutions.
That said, it isn't the original method, which may recieve updates that change the status quo (for better or worse), potentially making Boiler005 (and all tokens generated by it) inoperable.
Please maintain a backup access method (such as a physical token) to avoid getting locked out!

### Why?
Because it enables Purdue's 2fa to be interoperable with your choice of application. 
Made specifically to help me dissuade friends from auto-login approval scripts on their mobile devices.

### Thanks to
[Skip2](https://github.com/skip2) - QR Code generation library          
[Skratchdot](https://github.com/skratchdot) - Open file library             
[elnardu](https://github.com/elnardu) - For figuring out how the handshake works. URLs and Post information utilized from their [local-boilerkey](https://github.com/elnardu/local-boilerkey) script.             