# Chopping Block TextMate Bundle for ActionScript Development

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/choppingblock/actionscript-chop-tmbundle.git "ActionScript Chop.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/choppingblock/actionscript-chop-tmbundle/tarball/master
    tar zxf choppingblock-actionscript-chop-tmbundle*.tar.gz
    rm choppingblock-actionscript-chop-tmbundle*.tar.gz
    mv choppingblock-actionscript-chop-tmbundle* "ActionScript Chop.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
