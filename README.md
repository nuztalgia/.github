<div align="center"><h1>
<picture><img src="https://user-images.githubusercontent.com/95021853/204664528-7db6fe7f-44eb-420d-8fb2-8da178073c44.png" width=120></picture>
<br><code>.github</code>
</h1></div>

Hi there! This repository holds all of my default [community health files].
These files govern all repos owned by my personal [GitHub account](/../../..).
Exceptions are made for individual repos on a **per-file**[^exceptions] basis.

Aside from the two caveats mentioned [below](#license), the contents of this
repo are licensed under [CC0](/LICENSE) and are therefore in the public domain.
Feel free to use and/or adapt any of my files for your own projects if you find
them helpful! 💜

## Contents

- 📁 [`ISSUE_TEMPLATE/`](/.github/ISSUE_TEMPLATE/)[^file-naming]
  - 🐛 [`bug_report.yml`](/.github/ISSUE_TEMPLATE/bug_report.yml)
  - ✨ [`feature_request.yml`](/.github/ISSUE_TEMPLATE/feature_request.yml)
- 🤝 [`code_of_conduct.md`](/.github/code_of_conduct.md)
- 💝 [`contributing.md`](/.github/contributing.md)
- 📜 [`developer_certificate.md`](/.github/developer_certificate.md)[^dev-cert]
- 💫 [`issue_template.md`](/.github/issue_template.md?plain=1)
- 🌟 [`pull_request_template.md`](/.github/pull_request_template.md?plain=1)
- 🔐 [`security.md`](/.github/security.md)

## License

For the most part, the files in this repository are entirely covered by the
[Creative Commons Zero v1.0 Universal](/LICENSE) license. The only exceptions
are as follows:

- [`code_of_conduct.md`](/.github/code_of_conduct.md) is an abridged adaptation
  of the [Contributor Covenant](https://www.contributor-covenant.org/), which is
  released under [CC-BY-4.0].

- [`developer_certificate.md`](/.github/developer_certificate.md) contains a
  copy of the [Developer Certificate of Origin], which states that it may be
  copied and distributed, as long as its text isn't altered. This restriction
  only applies to the [DCO document] itself. The other parts of the file were
  written by me ([@nuztalgia](https://github.com/nuztalgia)) and are licensed
  under [CC0](/LICENSE), like the rest of this repo.<br>&ZeroWidthSpace;

[community health files]:
  https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file
[cc-by-4.0]:
  https://github.com/EthicalSource/contributor_covenant/blob/release/LICENSE.md
[developer certificate of origin]: https://developercertificate.org/
[dco document]:
  https://github.com/nuztalgia/.github/blob/main/.github/developer_certificate.md#dco-v11-full-text

[^exceptions]:
    If `example-repo` has a file with the same name as one of the files included
    here, then the file in `example-repo` takes precedence **for that repository
    only**. There's no need to manually cross-check file names, though - the
    appropriate guidelines for each repo should automatically be surfaced in
    GitHub's UI.

[^file-naming]:
    With the exception of `LICENSE` and `README.md` (arguably the most important
    files in a repo), I prefer lowercased file names - see sindresorhus/ama#197.
    Unfortunately, at the time of writing, GitHub does not seem to support a
    lowercased name for the `ISSUE_TEMPLATE` directory.

[^dev-cert]:
    The Developer Certificate of Origin isn't one of GitHub's natively-supported
    community health files. Nevertheless, it lives in this repository because it
    serves a similar purpose, and because it's referenced on more than one
    occassion by the other files in its directory.
