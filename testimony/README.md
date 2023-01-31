# Blockchain Commons Testimony

From time to time, the Blockchain Commons is called upon to testify about blockchain technology before local, state, and federal agencies who are making decisions and laws regarding the future of these technologies. This repo contains any such testimony that is public.

## Additional Information

| Number                    | Title         | Agency | Version | Owner                                                  | 
|---------------------------|---------------|--------|-----|----------------------------------------------|
| [BCT-2018-001](testimonies/bct-2018-001.md) | **9/19/18.** Engaging on Fund Innovation & Cryptocurrency-related Holdings | USA SEC | 1.0.0 | Christopher Allen |
| [BCT-2021-001](testimonies/bct-2021-001.md) | **10/22/21.** DAO | Wyoming | 1.0.0 | Christopher Allen |

_Also see our [Research](https://github.com/BlockchainCommons/Research/blob/master/README.md) and our [Wallet Improvement Proposals](https://github.com/BlockchainCommons/wips/blob/master/README.md)._

### BCT Number

Please number all Bitcoin Testimony BCTs with a four-digit number representing the current year (`YYYY`) followed by a three-digit sequence number for that year (`SSS`). For example: `bct-2020-001` is the first BCT for 2020, `bct-2020-017` is the 17th, and `bct-2021-001` is the first BCT for 2021.

_Note that the sequence number reverts to 001 at the start of each year._

### BCT Title

Please be sure that your title is concise, yet informative. 

### BCT Agency

This is the local, state, or federal agency that the testimony was directed at.

### BCT Version

When updating BCTs, please use [semantic versioning](https://semver.org/) for your version number.

Most briefly: your version number should be of the form X.Y.Z, where `X` is the major number ("0" for a BCT in progress; "1" for a fully drafted BCT; and "2" or higher for a new version that has introduced a backward-incompatible change), `Y` is the minor number (for a backward-compatible new feature), and `Z` is the patch number (for fixing typos and making other clarifications that don't fundamentally change what the BCT means).

But please consult the semantic versioning document for more information and adjust appropriately for the fact that these are textual BCTs, not software.

For Testimony, most versions will likely settle at 1.0.0, but versioning might be used if revisions are sent or if similar Testimony is sent to multiple agencies.

### BCT Owner

Please list the person primarily responsible for the BCT, and moving it forward, as the owner. If there are multiple authors, they should be listed on the BCT itself, not on this overview.

## Status - Ongoing

Blockchain Testimony is ongoing. 

## Origin, Authors, Copyright & Licenses

Unless otherwise noted (either in this [/README.md](./README.md) or in the file's header comments) the contents of this repository are Copyright © 2020 by Blockchain Commons, LLC, and are [licensed](./LICENSE) under the [spdx:BSD-2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html).

In most cases, the authors, copyright, and license for each file reside in header comments in the source code. When it does not, we have attempted to attribute it accurately in the table below.

This table below also establishes provenance (repository of origin, permalink, and commit id) for files included from repositories that are outside of this repo. Contributors to these files are listed in the commit history for each repository, first with changes found in the commit history of this repo, then in changes in the commit history of their repo of their origin.

| File      | From                                                         | Commit                                                       | Authors & Copyright (c)                                | License                                                     |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------ | ----------------------------------------------------------- |
| exception-to-the-rule.c or exception-folder | [https://github.com/community/repo-name/PERMALINK](https://github.com/community/repo-name/PERMALINK) | [https://github.com/community/repo-name/commit/COMMITHASH]() | 2020 Exception Author  | [MIT](https://spdx.org/licenses/MIT)                        |

## Financial Support

Testimony is a project of [Blockchain Commons](https://www.blockchaincommons.com/). We are proudly a "not-for-profit" social benefit corporation committed to open source & open development. Our work is funded entirely by donations and collaborative partnerships with people like you. Every contribution will be spent on building open tools, technologies, and techniques that sustain and advance blockchain and internet security infrastructure and promote an open web.

To financially support further development of `$projectname` and other projects, please consider becoming a Patron of Blockchain Commons through ongoing monthly patronage as a [GitHub Sponsor](https://github.com/sponsors/BlockchainCommons). You can also support Blockchain Commons with bitcoins at our [BTCPay Server](https://btcpay.blockchaincommons.com/).

## Contributing

We encourage public contributions through issues and pull requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [Contributor License Agreement](./CLA.md).

### Discussions

The best place to talk about Blockchain Commons and its projects is in our GitHub Discussions areas.

[**Blockchain Commons Discussions**](https://github.com/BlockchainCommons/Community/discussions). For developers, interns, and patrons of Blockchain Commons, please use the discussions area of the [Community repo](https://github.com/BlockchainCommons/Community) to talk about general Blockchain Commons issues, the intern program, or topics other than those covered by the [Gordian Developer Community](https://github.com/BlockchainCommons/Gordian-Developer-Community/discussions) or the 
[Gordian User Community](https://github.com/BlockchainCommons/Gordian/discussions).
### Other Questions & Problems

As an open-source, open-development community, Blockchain Commons does not have the resources to provide direct support of our projects. Please consider the discussions area as a locale where you might get answers to questions. Alternatively, please use this repository's [issues](./issues) feature. Unfortunately, we can not make any promises on response time.

If your company requires support to use our projects, please feel free to contact us directly about options. We may be able to offer you a contract for support from one of our contributors, or we might be able to point you to another entity who can offer the contractual support that you need.


### Credits

The following people directly contributed to this repository. You can add your name here by getting involved. The first step is learning how to contribute from our [CONTRIBUTING.md](./CONTRIBUTING.md) documentation.

| Name              | Role                | Github                                            | Email                                 | GPG Fingerprint                                    |
| ----------------- | ------------------- | ------------------------------------------------- | ------------------------------------- | -------------------------------------------------- |
| Christopher Allen | Principal Architect | [@ChristopherA](https://github.com/ChristopherA) | \<ChristopherA@LifeWithAlacrity.com\> | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

## Responsible Disclosure

We want to keep all of our software safe for everyone. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner. We are unfortunately not able to offer bug bounties at this time.

We do ask that you offer us good faith and use best efforts not to leak information or harm any user, their data, or our developer community. Please give us a reasonable amount of time to fix the issue before you publish it. Do not defraud our users or us in the process of discovery. We promise not to bring legal action against researchers who point out a problem provided they do their best to follow the these guidelines.

### Reporting a Vulnerability

Please report suspected security vulnerabilities in private via email to ChristopherA@BlockchainCommons.com (do not use this email for support). Please do NOT create publicly viewable issues for suspected security vulnerabilities.

The following keys may be used to communicate sensitive information to developers:

| Name              | Fingerprint                                        |
| ----------------- | -------------------------------------------------- |
| Christopher Allen | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

You can import a key by running the following command with that individual’s fingerprint: `gpg --recv-keys "<fingerprint>"` Ensure that you put quotes around fingerprints that contain spaces.
