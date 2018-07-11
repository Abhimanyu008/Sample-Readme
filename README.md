License badge Documentation badge Docker badge Support badge



Copyright © 2013-2016 Kurento. Licensed under Apache 2.0 License.

Kurento Utils for Node.js and Browsers
The Kurento Utils project contains a set of reusable components that have been found useful during the development of the WebRTC applications with Kurento.

The source code of this project can be cloned from the GitHub repository.

Installation instructions
Be sure to have installed Node.js and [Bower] in your system:

curl -sL https://deb.nodesource.com/setup_4.x | sudo bash -
sudo apt-get install -y nodejs
sudo npm install -g bower
To install the library, it's recommended to do that from the NPM repository :

npm install kurento-utils
Alternatively, you can download the code using git and install manually its dependencies:

git clone https://github.com/Kurento/kurento-utils
cd kurento-utils
npm install
Screen and window sharing depends on the privative module kurento-browser-extensions. To enable its support, you'll need to install the package dependency manually or use a getScreenConstraints function yourself on runtime. If it's not available, when trying to share the screen or a window content it will throw an exception.

Browser
To build the browser version of the library you'll only need to exec the grunt task runner and they will be generated on the dist folder. Alternatively, if you don't have it globally installed, you can run a local copy by executing

node_modules/.bin/grunt
Acknowledges
Bertrand CHEVRIER for grunt-jsdoc
Kurento
What is Kurento
Kurento is an open source software project providing a platform suitable for creating modular applications with advanced real-time communication capabilities. For knowing more about Kurento, please visit the Kurento project website: http://www.kurento.org.

Kurento is part of FIWARE. For further information on the relationship of FIWARE and Kurento check the Kurento FIWARE Catalog Entry

Kurento is part of the NUBOMEDIA research initiative.

Documentation
The Kurento project provides detailed documentation including tutorials, installation and development guides. A simplified version of the documentation can be found on readthedocs.org. The Open API specification a.k.a. Kurento Protocol is also available on apiary.io.

Source
Code for other Kurento projects can be found in the GitHub Kurento Group.

News and Website
Check the Kurento blog Follow us on Twitter @kurentoms.

Issue tracker
Issues and bug reports should be posted to the GitHub Kurento bugtracker

Licensing and distribution
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

Contribution policy
You can contribute to the Kurento community through bug-reports, bug-fixes, new code or new documentation. For contributing to the Kurento community, drop a post to the Kurento Public Mailing List providing full information about your contribution and its value. In your contributions, you must comply with the following guidelines

You must specify the specific contents of your contribution either through a detailed bug description, through a pull-request or through a patch.
You must specify the licensing restrictions of the code you contribute.
For newly created code to be incorporated in the Kurento code-base, you must accept Kurento to own the code copyright, so that its open source nature is guaranteed.
You must justify appropriately the need and value of your contribution. The Kurento project has no obligations in relation to accepting contributions from third parties.
The Kurento project leaders have the right of asking for further explanations, tests or validations of any code contributed to the community before it being incorporated into the Kurento code-base. You must be ready to addressing all these kind of concerns before having your code approved.
Support
The Kurento project provides community support through the Kurento Public Mailing List and through StackOverflow using the tags kurento and fiware-kurento.

Before asking for support, please read first the Kurento Netiquette Guidelines
