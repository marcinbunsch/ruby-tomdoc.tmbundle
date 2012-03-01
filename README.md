Ruby with TomDoc TextMate bundle
--------------------

The TextMate bundle extends Ruby support with automatically generating TomDoc at the top of the method when you do ddef<tab> and ddefs<tab>

Installation
============

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/marcinbunsch/ruby-tomdoc.tmbundle.git "ruby-tomdoc.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

