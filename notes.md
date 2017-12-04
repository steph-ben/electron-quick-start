## NodeJs deps
    npm install
    npm install electron
    npm install request-promise
    npm install electron-packager
    npm install request
    npm install jquery

## Python deps
    sudo apt install python-pip -y
    pip install --upgrade pip
    sudo pip install setuptools
    pip install Flask --user
    pip install pyinstaller --user

## Run it to give it a try
    ./node_modules/.bin/electron .

## Package it
    pyinstaller hello.py --distpath dist
    ./node_modules/.bin/electron-packager .

--> The directory it self-sufficient !!!
