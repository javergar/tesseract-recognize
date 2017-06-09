# NAME

tesseract-recognize - A tool that does layout anaysis and/or text recognition using tesseract and outputs the result in Page XML format.

# INSTALLATION AND USAGE

    git clone https://github.com/mauvilsa/tesseract-recognize
    mkdir tesseract-recognize/build
    cd tesseract-recognize/build
    cmake -DCMAKE_INSTALL_PREFIX:PATH=$HOME ..
    make install
    
    tesseract-recognize --help
    tesseract-recognize IMAGE OUTPUT.xml

# VIEWING RESULTS

The results can be viewed/edited using the Page XML editor available at https://github.com/mauvilsa/nw-page-editor or using other tools that support this format such as http://www.primaresearch.org/tools and https://transkribus.eu/Transkribus/ .

# CONTRIBUTING

If you intend to contribute, before any commits be sure to first execute githook-pre-commit to setup (symlink) the pre-commit hook. This hook takes care of automatically updating the tool version.

# COPYRIGHT

The MIT License (MIT)

Copyright (c) 2015-present, Mauricio Villegas <mauricio_ville@yahoo.com>
