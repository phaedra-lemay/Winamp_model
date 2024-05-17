# Winamp_model
 replica of the old winamp interface that you can upload your own playlists to!

Download and double click this html and it will open on your browser.

To replace the songs just (1)use YouTube to mp3 to convert your songs and then after that (2)upload all your mp3 files onto GitHub (3) rewrite the urls in this format and replace the songs in the winamp.html with the songs you want:

url: "https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY@VERSION/path/to/your/file.mp3"
Here's what each part of the link represents:
	•	https://cdn.jsdelivr.net/gh/: This is the base URL for the jsDelivr CDN.
	•	USERNAME: This should be replaced with your GitHub username.
	•	REPOSITORY: This should be replaced with the name of your repository.
	•	VERSION: This is the version of the repository you want to use. You can use a commit hash, branch name, or release tag.
	•	path/to/your/file.mp3: This is the path to your MP3 file within the repository.

To change skins modify this url:

url: "https://archive.org/cors/winampskin_SKINNAME/SKINNAME.wsz"
Here's what each part of the link represents:
	•	https://archive.org/cors/winampskin_: This is the base URL for the skin on archive.ord.
    •	SKINNAME: the name of the winamp skin. can be found on https://archive.org/details/winampskins?tab=collection search the collection for the skin you want and click on the skins to figure out their skin names you can use ot plug in to your url.
    i.e. for https://archive.org/details/winamp_skin_internet_archive the SKINNAME=skin_internet_archive

for an example of what my playlist folder looks like with all my mp3s visit my playlist folder on github: https://github.com/phaedra-lemay/nightshift_playlist/tree/main#:~:text=Settings-,nightshift_playlist,-Public
