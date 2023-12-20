
# CAASPP Hacks

A project dedicated to/for hacking CAASPP secure browser.

## How does it work?

This project exploits the vulnerabilities on the secure browser to achieve Read & Write on the Secure Browser client.

It also externally displays ImGUI to actually control the hack.

## How is the secure client "secure"?

I haven't researched much about the client itself as I just jumped straight to my bypass methods in hopes of it just working.

So far all I know is that the secure client does not launch when certain processes are open. It also marks you as cheating when you attempt to interact with anything outside of CAASPP.

And from hacking-wise, they detect Win-API calls as well as Cheat Engine. But the secure client is usermode so you can probably still bypass in usermode too.

## Methods of hacking the secure client?

I achieved R&W through my own usermode driver. After that I reversed with IDA Pro to find addresses and offsets.

I used ImGUI .Net to display externally topmost over the secure client to interact with the cheat.

Then I purchased OpenAI API key, then made an api that I can send requests to for answers.

I then read the question and the answer options (if multiple choice/interactable) then send a request to my API that contains the question and answers options.

The API returns the Answer, which is then displayed on the IMGUI for you to simply put in.

## Releasing?

No, or at least not yet. I'm hoping to sell the src code to CAASPP, if not I'll release the compiled obfuscated zip file.

And yes, I am open to selling the src code and I will be open to selling it for 
$50-$100.

