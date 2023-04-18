
![Banner](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/banner.png)


# yt-dlp-playlist-parallelizer

yt-dlp Playlist Parallelizer is a shell script designed to speed up the process of downloading videos from YouTube playlists. The script utilizes the job parallelization feature of the shell and allows users to download multiple videos from a playlist simultaneously with options for custom settings and options.


## Installation

To install the yt-parallel script for parallelizing YouTube playlist downloads, you can follow these steps:

Open a terminal in your system, or if you're using Termux, launch the Termux app.
Run the following command on your terminal to download the yt-parallel script from it's GitHub repository and make it executable.

For Desktop Linux:
``` 
sudo curl -s https://raw.githubusercontent.com/sonothamin/yt-dlp-playlist-parallelizer/main/yt-dlp-playlist-parallelizer >> /bin/yt-parallel && sudo chmod +x $PREFIX/bin/yt-parallel
```

For Termux:
``` 
curl -o $PREFIX/bin/yt-parallel -L https://raw.githubusercontent.com/sonothamin/yt-dlp-playlist-parallelizer/main/yt-dlp-playlist-parallelizer && chmod +x $PREFIX/bin/yt-parallel
```
And that's it! With these simple steps, you can install and use the yt-parallel script to download YouTube playlists fast and quick.

## How it works

This script is used for parallelization of yt-dlp downloads of a playlist. The script presents a menu to the user to select from several options, including downloading a playlist, selecting settings, and obtaining help. The user can also choose to specify the external downloader, set the output folder, and toggle yt-dlp options.

The download function prompts the user for the playlist URL, sets the output folder, and allows the user to select the number of sequential downloads and download options. The parse_script function changes the format of the URLs to include the specified download options and the number of threads, creates a script, Playlist-download.sh, and runs it.

The settings function presents a menu for the user to select options for external downloader, output folder, yt-dlp options, and updating yt-dlp.

The script uses the dialog command to create interactive menus for the user. The sed command is used to modify the URLs to include the specified download options and number of threads. Finally, the chmod command changes the permissions of the script to make it executable.

## Screenshots

![Screenshot 1](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/1.png)

![Screenshot 2](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/2.png)

![Screenshot 3](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/3.png)

![Screenshot 4](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/4.png)

![Screenshot 5](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/raw/main/Screenshots/5.png)

## Contributing

Contributions are always welcome! Whether it's bug reports, feature requests, documentation updates, or code improvements, feel free to open an issue or a pull request on the repo, and I'll be happy to review and merge your changes. Together, we can make the project even better!


## License

This software is licensed under the GNU General Public License (GPL) version 3.0. This license grants you the freedom to use, modify, and distribute the software as long as you adhere to the terms and conditions of the license. You are also required to distribute the source code of any modifications you make to the software under the same license terms. The GPL also includes provisions to protect users' privacy, prevent patent aggression, and ensure that any Digital Restrictions Management (DRM) is removable. For more information about the GPL, please see the [GNU GPL v3 LICENSE](https://github.com/sonothamin/yt-dlp-playlist-parallelizer/blob/main/LICENSE)  file included in this repository or visit the GNU website.

