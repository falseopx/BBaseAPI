# BBaseAPI

BBaseAPI is BaseAPI (developed by MarsQQ) bandaged to make the code less.. sucky.

It's user friendly and doesn't require too much knowledge to use (but brain is required)
I'll just leave the thing here:
To use BaseAPI, you need these 4 requirements before you start:

- API Name (Name of API, Example: BaseAPI)
- API Install Link (Where the API installs the DLL, use a Direct DLL Download hosted preferrably on gitlab, don't install from a text file)

- DLL Name (The name of DLL, pretty self explanitory)
- DLL Pipe (The pipe of the DLL, pretty self explanitory)


To use BaseAPI after setting it up, build it via the Release folder, use it as a reference, and now, you're ready to implement it:

To implement it, you start with:
"Using BaseAPI;"


Under your Public Partial Class, do:


Exploit BaseAPI = new Exploit();


thought note "BaseAPI" can be anything



On your "Public", do:
BaseAPI.LoadExploit();



On your Inject, do:

BaseAPI.Inject();


On your Execute Button, do:
BaseAPI.Execute(texteditor.text);


Credits to: 

Rakion: Execute Code
PareX: Puppy Milk Injection Code
