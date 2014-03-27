Podfile
=======

brew git
===

	$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
	$ brew install git

rbenv
===

	$ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
	$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
	$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
	$ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build

cocospod
===

	$ [sudo] gem install cocoapods
	$ pod setup
	$ pod search RestKit
	$ cd /path/to/MyProject
	$ nano Podfile
	$ pod install