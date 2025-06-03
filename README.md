Download the txt file then using hashcat bruteforce the password of the jwt 


hashcat -a 0 -m 16500 <jwt_token> /path/to/wordlists


If secret is found use hashcat -a 0 -m 16500 <jwt_token> /path/to/wordlists --show it'll display it in a hex form use a online decoder to decode or pass it to gemini
