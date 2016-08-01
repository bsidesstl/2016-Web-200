API Access Violation is a challenge where competitors have to connect to a server and get an API key which gives them higher level access in order to find the flag.

Competitors will connect to the sinatra server and navigate the pages to find the flag (MCA-618584AA) most pages require an API key to function correctly.
Any 8 character sequence that begins DAPI or MAPI will work.  You can also connect to /api/key-request/mobile or /api/key-request/desktop to generate a key.  A list of methods can be found at /help

## Solution ##

Connect to /getPicture/DAPI1234/Flag.png and view the source code.