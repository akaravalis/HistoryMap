# Meeting 17 Aug 2021
- [ ] create a project timeline in this readme.md
- [ ] add each task as a github issue
- [x] Check the OA auth google
- [ ] check aws api gateway
- [ ] Data Collection and Preparation
- [ ] Design Database and Store Data
- [ ] Research the model suitable for the type of Data
- [ ] Preprocess and Label data to be sufficient
- [ ] Establish a baseline model machine learning model using different algorithms
- [ ] Training and testing
- [ ] Evaluation and Comparison
- [ ] Design User Experience
- [ ] Test and Evaluation of the Project

# Overview

HistoryMap is a Chrome extension designed to help mamange (many) opened tabs, or 'supporting sensemaking' in the context of academic research. As the name indicates, it creates a map of pages you visited, making it easier to find a visited page and understand how pages are linked. Also, you can easily find the important information with the highlight and annotation feature. If you are interested in the academic research, there is [more details here](http://vis4sense.github.io/sensemap/).


## Install

Currently, the recommended way is to install from the source in github (please use the default 'rebuild-mvc' branch), becuase it is not fully completed yet. Follow [the steps here](https://blog.hunter.io/how-to-install-a-chrome-extension-without-using-the-chrome-web-store-31902c780034) ('Method 1: from the source code') if you are not familiar with installing Chrome extension from source code. It will be availalbe from the Chrome Web Store once completed.

An older version is available in the [Chrome app store](https://chrome.google.com/webstore/detail/sensemap/agljnpanahlilmpipaeflmnjkiiecfjb) (called 'SenseMap'). This version lacks the 'user login' and 'saved sessions' in the new version, and quite a few bug fixes. The source code of this version is the 'master' branch. 

## Use

[This video](https://vimeo.com/161322047) shows how HistoryMap works, with an introduction to sense-making. 

There is a simple user guide here: http://vis4sense.github.io/sensemap/#guide. 

## Contribute

There is more details on the [wikipage](https://github.com/Vis4Sense/HistoryMap/wiki) on how to contribute to the development. We currently need help on:
- Improve the design, both the interface and user interaction;
- Implementing [new features](https://github.com/Vis4Sense/HistoryMap/labels/improvement);
- Testing and fixing [bugs](https://github.com/Vis4Sense/HistoryMap/labels/bug);
- Machine learning, i.e., to better support the user by understanding what they try to do (e.g., buy a digital camera).

Please use the [Issues](https://github.com/Vis4Sense/HistoryMap/issues) to **report [bugs](https://github.com/Vis4Sense/HistoryMap/labels/bug)** and **request [new features](https://github.com/Vis4Sense/HistoryMap/labels/improvement)**.
