## Licenses
This section provides a recommendation on how to communicate software or document licenses information in a project.

### Software Code Licenses

Ideally, the project SHOULD communicate the software license information via three different metods:

* In the README file
* Inside of the repository with a ```License.txt``` document
* Inside of each code file created by the group

#### Statement in README File
Insert in the README file one of these statements (depending of the license type):

```
![APM license](https://img.shields.io/badge/License-MIT-brightgreen)

![APM license](https://img.shields.io/badge/License-Apache_2.0-brightgreen)

![APM license](https://img.shields.io/badge/License-Mozilla_Public_License_2.0-brightgreen)
```

The README file will display one of these three licenses:

* ![APM license](https://img.shields.io/badge/License-MIT-brightgreen)

* ![APM license](https://img.shields.io/badge/License-Apache_2.0-brightgreen)

* ![APM license](https://img.shields.io/badge/License-Mozilla_Public_License_2.0-brightgreen)

In addition, it is recommended to include a plain text statement of the license in the README file, for accessibility purposes as well as enabling parsing by automated tooling. This can be done by including a "License" section with one of the following, as appropriate:

* This project is licensed under the MIT license.

* This project is licensed under the Apache-2.0 license.

* This project is licensed under the Mozilla Public License, version 2.0 (MPL-2.0).


#### License File in the Repository
Insert in the repository a file called ```License.txt```. 

The Maintainer or Chair can copy the corresponding license file from the [templates/license](https://github.com/OpenManufacturingPlatform/templates/tree/development/License) repository and upload it to the project repository.


#### License Reference in each Source Code File
The recommendation is that projects SHOULD use [SPDX short-form license identifiers](https://spdx.dev/ids/) in all source code and documentation files that are **original to the project**.


Each source code created by the project SHOULD have one of these SPDX license identifiers: (depending of the type of source code license allocated to the project)

* **for a MIT license:**

```
# SPDX-License-Identifier: MIT
# Copyright Contributors to the Open Manufacturing Platform
```

* **for a Apache 2.0 license:**

```
# SPDX-License-Identifier: Apache-2.0
# Copyright Contributors to the Open Manufacturing Platform
```

* **for a Mozilla Public License 2.0 license:**

```
# SPDX-License-Identifier: MPL-2.0
# Copyright Contributors to the Open Manufacturing Platform
```

If the project needs to include source code or documents from a different upstream project, the recommendation is to retain those files in **unmodified form**  _**(don't add identifiers)**_.

Also consider to:

* keep these files in sync with upstream project
* ask the upstream project to insert the identifiers on their source code files / documents.

### Technical Document License
In projects where the main deliverables are technical documents, each document MUST have a legal disclaimer.

The legal disclaimer to insert in each project document SHOULD be:

```
© OMP 2020, All rights reserved.

“THESE MATERIALS ARE PROVIDED “AS IS.”  The parties expressly disclaim any warranties 
(express, implied, or otherwise), including implied warranties of merchantability, non-infringement, 
fitness for a particular purpose, or title, related to the materials. The entire risk as to 
implementing or otherwise using the materials is assumed by the implementer and user. 

IN NO EVENT WILL THE PARTIES BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF 
INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES 
OF ACTION OF ANY KIND WITH RESPECT TO THIS DELIVERABLE OR ITS GOVERNING AGREEMENT, WHETHER 
BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT 
THE OTHER MEMBER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.”
```

new test line.

