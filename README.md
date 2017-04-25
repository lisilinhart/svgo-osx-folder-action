## OS X Folder Action for SVGO, v0.0.1

1. install [SVGO](https://github.com/svg/svgo)
2. `curl -sS https://raw.githubusercontent.com/svg/svgo-osx-folder-action/master/install.sh | sh`
3. attach Folder Action to some folder:

    ![screenshot 1](https://raw.github.com/svg/svgo-osx-folder-action/master/screenshots/1.png)

    ![screenshot 2](https://raw.github.com/svg/svgo-osx-folder-action/master/screenshots/2.png)

4. drag-n-drop `.svg`-files to this folder
5. hurray, your files are optimized!

### Use in NVM
To make it work in NVM, edit Script File in ~/Library/Scripts/Folder/Folder Action Scripts and edit Line 9 to the following:
`do shell script "/bin/bash -l -c 'source ~/.nvm/nvm.sh && svgo \"" & file_path & "\"'"` 

![](//mc.yandex.ru/watch/18561160)

