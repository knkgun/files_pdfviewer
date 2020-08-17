files_pdfviewer
======

This application integrates the [PDF.js](https://mozilla.github.io/pdf.js/) library into Nextcloud's Viewer.
You can view PDF files as well as Adobe© Illustrator files (AI)

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/owncloud/files_pdfviewer/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/nextcloud/files_pdfviewer/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/owncloud/files_pdfviewer/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/nextcloud/files_pdfviewer/?branch=master)
[![Build Status](https://travis-ci.org/owncloud/files_pdfviewer.svg)](https://travis-ci.org/nextcloud/files_pdfviewer)


## 🏗 Development setup

1. ☁ Clone this app into the `apps` folder of your Nextcloud: `git clone https://github.com/nextcloud/files_pdfviewer.git`
1. ☁ Clone the viewer app into the `apps` folder of your Nextcloud: `git clone https://github.com/nextcloud/viewer.git`
2. 👩‍💻 In the folder of the files_pdfviewer app, run the command `npm ci && npm run dev` to install dependencies and build the Javascript.
3. ✅ Enable the app through the app management of your Nextcloud (viewer should be enabled by default)
4. 🎉 Partytime! Help fix [some issues](https://github.com/nextcloud/files_pdfviewer/issues) and [review pull requests](https://github.com/nextcloud/files_pdfviewer/pulls) 👍


### 🧙 Advanced development stuff

To build the Javascript whenever you make changes, you can also use `npm run build`. Or `npm run watch` to automatically rebuild on every file save.

You run all tests by using `make test`.


## ♥ How to create a pull request

This guide will help you get started:
- 💃 [Opening a pull request](https://opensource.guide/how-to-contribute/#opening-a-pull-request)


## ✌ Code of conduct

The Nextcloud community has core values that are shared between all members during conferences, hackweeks and on all interactions in online platforms including [Github](https://github.com/nextcloud) and [forums](https://help.nextcloud.com). If you contribute, participate or interact with this community, please respect [our shared values](https://nextcloud.com/code-of-conduct/). 😌
