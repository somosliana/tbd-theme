# install
```sh
# if ruby needed
yay -S --needed asdf-vm
asdf plugin-add ruby https://github.com/asdf-vm/asdf-ruby && asdf install ruby
# gem install
gem install shopify-cli
# check install
shopify version
# login
shopify login --store=STORE
```
# run
```sh
# cd
cd /var/theme
# serve
shopify theme serve
```
