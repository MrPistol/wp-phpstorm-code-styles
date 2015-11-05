PhpStorm WordPress Coding Styles
==========================================

This is our own WordPress coding styles for PhpStorm, forked from the WordPress.xml packaged with PhpStorm

## Usage

* Download the `CodepressWordPress.xml` file.
* Copy it to `~/Library/Preferences/WebIde{xx}/codestyles` directory.
* Once downloaded activate the scheme by selecting it in PHPStorm Preferences > Editor > Code Style.

## Development

* Clone the repo.
* Symlink the `CodepressWordPress.xml` file in the code `~/Library/Preferences/WebIde{xx}/codestyles` directory:

	```
	$ cd ~/Library/Preferences/WebIde{xx}/codestyles
	$ ln -s /path/to/repo/CodepressWordPress.xml
	```

* Restart PhpStorm.
* Activate the scheme by selecting 'Codepress WordPress' in PHPStorm Preferences > Editor > Code Style.
* Make changes, submit pull requests etc.