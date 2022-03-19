# nuxt-web3-temp

## Build Setup

```sh
# nodenvのinstall
$ brew install nodenv

# zshの場合
$ echo 'eval "$(nodenv init - --no-rehash)"' >> ~/.zshrc
$ source ~/.zshrc

# fishの場合
$ echo 'eval (nodenv init - | source)' >> ~/.config/fish/config.fish
$ source ~/.config/fish/config.fish

$ nodenv install 16.14.2

$ make setup
```

## Local Build
```sh
$ yarn dev
```