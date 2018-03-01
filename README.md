# my-quick-start

This is my development quick setup and quick start!!

# Usage

First, install git and clone this repository.

```console
$ git clone git@github.com:kseta/my-quick-start.git
```

Install Xcode and run command.


```console
$ sudo xcodebuild -license accept
```

Intall Homebrew.

```console
# see https://brew.sh/
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Intall Ansible.

```console
$ brew install ansible
```

Provisioning, my Mack Book Pro.

```console
$ ansible-playbook -i hosts macos.yml
```

This is all!!

# Other Tasks (TODO)

- Enable rbenv.

    ```
    $ rbenv init
    $ rbenv install 2.4.3
    ```

- Create dotfiles via homesick.

    ```console
     $ gem install homesick
     $ rbenv rehash
     $ homesick clone kseta/dotfiles
     $ cd ~ && homesick symlink dotfiles
    ```

- Intall Apps
    - [Display Menu](https://itunes.apple.com/jp/app/display-menu/id549083868?mt=12)
    - [GIPHY](https://itunes.apple.com/us/app/giphy-capture.-the-gif-maker/id668208984?mt=12)
    - [Keynote](https://www.apple.com/jp/keynote/)
    - [Skitch](https://itunes.apple.com/us/app/skitch-snap-mark-up-send/id490505997?mt=8)
    - [Wunderlist](https://itunes.apple.com/us/app/wunderlist-to-do-list-tasks/id406644151?mt=8)
