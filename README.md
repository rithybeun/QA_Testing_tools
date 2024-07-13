# Config Appium-Doctor Android

	nano ~/.zshrc  # For zsh
	# or
	nano ~/.bash_profile  # For bash


	#Config Android

	export ANDROID_HOME=~/Library/Android/sdk
	export ANDROID_SDK_ROOT=$ANDROID_HOME
	export PATH=$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$PATH


	#Config Java Path

	export JAVA_HOME=$(/usr/libexec/java_home)
	export PATH=$JAVA_HOME/bin:$PATH

# Missing Carthage

	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
	brew install carthage
	carthage version


