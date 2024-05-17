# Winamp_model
FUNCTIONAL replica of the old winamp interface that you can upload your own playlists to!<br />
<br />
<img width="1492" alt="Screenshot 2024-05-16 at 5 58 49 PM" src="https://github.com/phaedra-lemay/Winamp_model/assets/142343420/1700253a-4ff9-4e65-bf0c-e4ab3acd18e0">
<br />
Download and double click this html and it will open on your browser.<br />
<br />
To replace the songs just (1)use YouTube to mp3 to convert your songs and then after that (2)upload all your mp3 files onto GitHub (3) rewrite the urls in this format and replace the songs in the winamp.html with the songs you want:<br />
<br />
url: "https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY@VERSION/path/to/your/file.mp3"<br />
Here's what each part of the link represents:<br />
<br />
	<ul>
	<li>https://cdn.jsdelivr.net/gh/: This is the base URL for the jsDelivr CDN.</li>
	<li>USERNAME: This should be replaced with your GitHub username.</li>
	<li>REPOSITORY: This should be replaced with the name of your repository.</li>
	<li>VERSION: This is the version of the repository you want to use. You can use a commit hash, branch name, or release tag.</li>
	<li>path/to/your/file.mp3: This is the path to your MP3 file within the repository.</li>
	</ul>
<br />
To change skins modify this url:<br />
<br />
url: "https://archive.org/cors/winampskin_SKINNAME/SKINNAME.wsz"<br />
Here's what each part of the link represents:<br />
<br />
	<ul>
	<li>https://archive.org/cors/winampskin_: This is the base URL for the skin on archive.ord.</li>
    	<li>SKINNAME: the name of the winamp skin. can be found on https://archive.org/details/winampskins?tab=collection search the collection for the skin you want and click on the skins to figure out their skin names you can use ot plug in to your url.</li>
    i.e. for https://archive.org/details/winamp_skin_internet_archive the SKINNAME=skin_internet_archive<br />
<br />
Another skin resource: https://skins.webamp.org/ ***keep in mind that not all these skin names will work because the url address is built to pull from archive.org so you must find the skin on archive.org as well and use the exact name used on archive.org. this website is just an easier way to look through all the available skins.***<br />
<br />
for an example of what my playlist folder looks like with all my mp3s visit my playlist folder on github: https://github.com/phaedra-lemay/nightshift_playlist/tree/main#:~:text=Settings-,nightshift_playlist,-Public<br />
