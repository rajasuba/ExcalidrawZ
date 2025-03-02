## 0.4.2

* Bug fixed: Export image stuck in loading...
* Optimization: Auto add export file extension for user.

## 0.4.1

* Optimize sidebar UI.
* Support Chinese handwriting font.

## 0.4.0

* New sidebar design

*  New `Share` button. You can export image/export file/archive all files. `MacOS 13.0 only`

  <img src="https://github.com/chocoford/ExcalidrawZ/assets/28218759/5d49daa4-323b-4145-bcb3-1f7a2cdedd19" alt="export image" style="zoom:50%;" />

* New file history. Protects your works.

  <img src="https://github.com/chocoford/ExcalidrawZ/assets/28218759/b4feb7df-4278-4a5c-8c78-c83200efc99b" alt="File History" style="zoom:50%;" />

* Bugs fixed.

## 0.3.5

* Add `Settings`
  * support changing color scheme
  * support manually checking updates & enable/disable auto update.

## 0.3.4

* Add `export image` feature.

  ![image-20230404024927888](assets/CHANGELOG/image-20230404024927888.png)

## 0.3.3

* Add backward compability: now app can be run on macOS 12.0 and newer.

## 0.3.2

* Optimize UI: now user can hide sidebar.
* Add `import`&`exportAll` in command menu.

## 0.3.1

* **Important**: fix the bug that will cause saving files failed.
* optimize deletion & recover mechanism.
* fix the bug user first come to app without group selection.
* fix the bug that will cause infinite loop when current file is `nil`.
* fix the bug that may cause saving empty data to existed file.

## 0.3.0

* Migrate storage from file system to core data.
* Hide the dropdown menu button in `excalidraw.com`
* App now can create groups to store files.
* App now can remember group selection.
* File group moving is now available.
* Files that being deleted will be move to `trash`.
* Context menu on `file` and `folder` is now available.

## 0.2.4

* test `Sparkle` framework for sandbox app.

## 0.2.3

* fix bug in x86 mac: import file failed.

## 0.2.2

* Test `Sparkle` framework

## 0.2.1

* Integrates `sparkle` framework for updates