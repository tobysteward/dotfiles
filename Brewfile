# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade --all

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
install findutils
# Install GNU `sed`, overwriting the built-in `sed`
install gnu-sed --with-default-names
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
install bash
brew tap homebrew/versions
install bash-completion2

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install homebrew/dupes/grep
install homebrew/dupes/screen

# Install other useful binaries

install git
install openssl
install php55
install php-cs-fixer
install composer

# Remove outdated versions from the cellar
cleanup
