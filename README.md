## Deep_Learning_Projects

This repository contains the jupyter notebooks which i wrote using the open-source datasets available in Kaggle. These notebooks are mainly in the following categories:

1. Sentiment Analysis - Basic Case of Natural Language Processing
2. Image Detection - Basic Case of Computer Vision




























Command to download large files from Google drive using a shareable link

`wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=FILEID' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=FILEID" -O FILENAME && rm -rf /tmp/cookies.txt`
