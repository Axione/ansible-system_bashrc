# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0](https://github.com/lotusnoir/ansible-system_bashrc/compare/2.0.0...2.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`b69bd62`](https://github.com/lotusnoir/ansible-system_bashrc/commit/b69bd629fbdc24ec2639ad3d263ca8549eda95c6)
- add version on molecule play image to maintain support on old release [`339bfe6`](https://github.com/lotusnoir/ansible-system_bashrc/commit/339bfe634e1e90fb7bb512dd72973797cc984083)
- update molecule [`f857ffc`](https://github.com/lotusnoir/ansible-system_bashrc/commit/f857ffc0e53fc44eeac0ccf3aefd8bd6ddd5503c)
- add redhat 9 to default supported distrib [`2eaaec4`](https://github.com/lotusnoir/ansible-system_bashrc/commit/2eaaec4f87876cde81391f89b36d4489c52c2146)
- add redhat 8 to default supported distrib [`1bf9b52`](https://github.com/lotusnoir/ansible-system_bashrc/commit/1bf9b5222036a9d2382274641768e549badb7525)
- sort testing distrib to avoid random changes [`00d3acf`](https://github.com/lotusnoir/ansible-system_bashrc/commit/00d3acfc07e92b38aee7e22e818e8deb8a707bba)
- update pre-commit and lint fix [`50328c5`](https://github.com/lotusnoir/ansible-system_bashrc/commit/50328c5324afd0cae20464e73c1f0079a825e7a6)
- remove rhel7 support and remove docker dind on pipeline [`f201465`](https://github.com/lotusnoir/ansible-system_bashrc/commit/f20146598907980a9889e87e88dcccd36a3b44da)
- remove lint from pipeline [`20da104`](https://github.com/lotusnoir/ansible-system_bashrc/commit/20da104ad0e436040093dd2f74323ca7db9a9d74)
- remove pipelines tests, moved in precommits [`44a7979`](https://github.com/lotusnoir/ansible-system_bashrc/commit/44a7979c555430d822c0ccb8fad07935a6253fa7)

## [2.0.0](https://github.com/lotusnoir/ansible-system_bashrc/compare/1.1.0...2.0.0) - 2023-09-27

### Commits

- fix default bash config when user is specified in users_configure [`12e2632`](https://github.com/lotusnoir/ansible-system_bashrc/commit/12e2632b5b10560f42578bca226a6cdbf1a718d3)
- update readme [`bccb37b`](https://github.com/lotusnoir/ansible-system_bashrc/commit/bccb37bd4486da819ffb76a3005f875001e81cce)
- add vars and conditions [`50cc617`](https://github.com/lotusnoir/ansible-system_bashrc/commit/50cc617d5b2a148d8f5a91025aa96d5370299e3b)
- major changes, in order to be more flexible and fix system deployment [`9c72a43`](https://github.com/lotusnoir/ansible-system_bashrc/commit/9c72a43e766ec0eb1565f09ca38a2d3eedc7b21b)
- update readme + precommit + include vars [`e0094e1`](https://github.com/lotusnoir/ansible-system_bashrc/commit/e0094e1a4c0409cb2a3a553f8159c41303d0d123)
- change import tasks to include in order to support facts on name [`2d535ed`](https://github.com/lotusnoir/ansible-system_bashrc/commit/2d535ed39b132ca3c418388c499ee5cda22e1d5e)

## [1.1.0](https://github.com/lotusnoir/ansible-system_bashrc/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`e181c83`](https://github.com/lotusnoir/ansible-system_bashrc/commit/e181c839194a39671b5aa0fcd3ff0c701efafc7e)

## [1.0.0](https://github.com/lotusnoir/ansible-system_bashrc/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`8025014`](https://github.com/lotusnoir/ansible-system_bashrc/commit/8025014505d4ee122695eec73e4b2d341c82018a)
- add precommit for lint [`63cb4ff`](https://github.com/lotusnoir/ansible-system_bashrc/commit/63cb4ffb2af2b738073f47d7ce46d532f346e5ed)
- fix checks [`6e11918`](https://github.com/lotusnoir/ansible-system_bashrc/commit/6e11918196089b221630847a7ba4c1d9e68f7ce7)
- add new molecule all scenario [`919d69f`](https://github.com/lotusnoir/ansible-system_bashrc/commit/919d69f9f944a1d17110b6f57684b4513f44e075)
- change tasks and vars to do nothing by default [`dc154e5`](https://github.com/lotusnoir/ansible-system_bashrc/commit/dc154e5305cba398146e8ea89c0c9028816c118f)
- split distro for molecule tests on ci [`92e17d2`](https://github.com/lotusnoir/ansible-system_bashrc/commit/92e17d24945452f86b66834b130f4b732df4551f)
- update checks and Readme [`b4f0c48`](https://github.com/lotusnoir/ansible-system_bashrc/commit/b4f0c480c18a6ccedab59fc315018b3a2d8a1d30)
- add molecule fix for ora9 [`712f941`](https://github.com/lotusnoir/ansible-system_bashrc/commit/712f9415dcbd98f096b505e98acd4445ad6cd035)
- add ora9 support [`cb8bd3d`](https://github.com/lotusnoir/ansible-system_bashrc/commit/cb8bd3d01c1d2ae977d6eb87fdc25280acf12c7f)
- update alias [`55a55d5`](https://github.com/lotusnoir/ansible-system_bashrc/commit/55a55d528a5e6ad89963b24d6152898ace321fc8)

## [0.3.0](https://github.com/lotusnoir/ansible-system_bashrc/compare/0.2.2...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`45de180`](https://github.com/lotusnoir/ansible-system_bashrc/commit/45de180a45840c519e5af540379af380b1fa9bcc)
- minor: add oracleLinux support + little fixes [`aa9cec3`](https://github.com/lotusnoir/ansible-system_bashrc/commit/aa9cec3ecebea53f178aaf881ede5f930b9df320)

## [0.2.2](https://github.com/lotusnoir/ansible-system_bashrc/compare/0.1.2...0.2.2) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`7b567c8`](https://github.com/lotusnoir/ansible-system_bashrc/commit/7b567c841a1354f771f98d911dc8dd9ef964a26a)
- fix: remove unsupported centos8 + minor fixes [`670f0e3`](https://github.com/lotusnoir/ansible-system_bashrc/commit/670f0e379b366380ada10fb6c640f8f623d04200)
- fix: add a space on the prompt for a better visual [`f33ee6a`](https://github.com/lotusnoir/ansible-system_bashrc/commit/f33ee6a88b62f3739d26e8e49fe0b86dd18e0029)

## [0.1.2](https://github.com/lotusnoir/ansible-system_bashrc/compare/0.1.1...0.1.2) - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`ba04aeb`](https://github.com/lotusnoir/ansible-system_bashrc/commit/ba04aebe67509c6b640f683727e02d9f29aa00b0)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`2b00262`](https://github.com/lotusnoir/ansible-system_bashrc/commit/2b002620c0286957dfe1ba20ce11a1eb31c86d0e)

## [0.1.1](https://github.com/lotusnoir/ansible-system_bashrc/compare/0.1.0...0.1.1) - 2021-11-15

### Commits

- fix: gitlab-ci changelog [`8412ac3`](https://github.com/lotusnoir/ansible-system_bashrc/commit/8412ac345d7f1064acb042ca1cb05d521b7c5f4b)
- fix: gitlab stages [`d04c110`](https://github.com/lotusnoir/ansible-system_bashrc/commit/d04c1100c93d2dbc05a970eb82ecc0cb1a024713)
- Added: test add [`695466e`](https://github.com/lotusnoir/ansible-system_bashrc/commit/695466e3a3f84bf131da86bb6fd364941a100138)

## 0.1.0 - 2021-11-15

### Commits

- test: automatic changelog on CI [`4885143`](https://github.com/lotusnoir/ansible-system_bashrc/commit/4885143b6061f724035a0dabdb5f1f13379a9e9e)
- initial commit [`c8b1a7d`](https://github.com/lotusnoir/ansible-system_bashrc/commit/c8b1a7d40ac6b468b8f872ef7235b13cf39bbbd1)
