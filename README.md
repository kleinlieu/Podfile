Podfile
=======

oh my zsh
===

	$ curl -L http://install.ohmyz.sh | sh

homebrew
===

	$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

git
===

	$ brew install git

rbenv
===

	$ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
	$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
	$ echo 'eval "$(rbenv init -)"' >> ~/.zshrc
	$ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build

cocoapods
===

	$ [sudo] gem install cocoapods
	$ pod setup
	$ pod search RestKit
	$ cd /path/to/MyProject
	$ nano Podfile
	$ pod install
