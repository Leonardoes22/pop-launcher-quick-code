# Quick Code
Open frequently visited directories in **VSCode** directly from the **Pop!_OS Launcher**.

## Installation

**Requirements**
- [fzf](https://github.com/junegunn/fzf)
- [zoxide](https://github.com/ajeetdsouza/zoxide)
- [pop-launcher](https://github.com/pop-os/launcher)

**Install**
```shell
make install
```

## To Do
- [ ] Improve search mechanism
    - [ ] Verify need to use both zoxide vs fzf
    - [ ] Improve workspaces search code
    - [ ] Improve path renaming mechanism
- [x] Crawl VSCode Workspaces directory (`~/.config/Code/User/workspaceStorage`)
- [x] Make name more user readable by making it relative path `~/..`
- [ ] Improve compatibility
    - [ ] Create an installation script
    - [ ] Better handle vscode and icon path
- [ ] Additional Features
    - [x] Change icon to vscode if there is a VS Code workspace
    - [ ] Make it also work with files
    - [ ] Open a new file outside of workspace

