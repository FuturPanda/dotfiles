# My Mac Setup : 

- ### Settings : 
  - Trackpad Settings and Accessibility settings drag
    - Trackpad Speed :
    - Three Fingers drag in accessibility settings pv5M6inzV6YLmp-qurtP
  - Dock preferences : auto hide
- ### Run chezmoi
  - ## How to Run : 
    ```shell
    PATH=$PATH:~/bin
    sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $FuturPanda
    ```

    if not working :
    ```shell
    chezmoi git pull https://github.com/FuturPanda/dotfiles.git
    ```
  - Install xcode.
- Execute init.sh :
    ```shell
    chmod +x .config/init.sh && .config/init.sh
    ```


# TODO :
- [ ] Create a Script running on the first launch of chezmoi 

# Dotfiles
My dotfiles are managed by [Chezmoi](https://www.chezmoi.io), the dotfiles manager : 



