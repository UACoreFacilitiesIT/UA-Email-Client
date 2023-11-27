# Changelog

All notable changes to this project can be found here.
The format of this changelog is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

#### 2022/05/18 [0.1.9](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

Refactors the environment setup to use poetry.

#### 2022/05/18 [0.1.8](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

Updated constructor to allow caller to supply their own AWS credentials.
Updated send_email to make Template use optional (i.e. can send raw emails)

#### 2022/01/18 [0.1.7](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

Update the data type check for the data attribute of the send_email function to actually check if the value is None.

Write a test suite for the client.

#### 2022/01/14 [0.1.6](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

When storing a template, remove the path components so that the template to use when sending an email doesn't also need to include the path components.

#### 2021/10/13 [0.1.5](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

Defined errors and added documentation.

#### 2021/07/31 [0.1.4](https://github.com/UACoreFacilitiesIT/UA-Email-Client)

Added ability to use default subjects.

#### 2021/07/31 [0.1.3](https://github.com/UACoreFacilitiesIT/UA-Email-Client/commit/5a188208602c0534596ccbef94becb56c97ffb7f)

Added ability to create default subjects. Updated logging.

#### 2021/07/29 [0.1.2](https://github.com/UACoreFacilitiesIT/UA-Email-Client/commit/d066e8dac13bc80f2e59af37264b4a2af25747e5)

Created initial version.
