<!-- TEMPLATE-TOKENS:START
  Replace every ${...} placeholder below before publishing this repository.
  Created with SMPTE/repo-admin-tools/create-repos.sh? They are filled in for you and
  this comment block is removed automatically. Filling them in by hand is fine too -
  delete this block when you are done.

    ${doc_number}       Display document number.  e.g.  ST 2140-1   |  AG-31
                        Note the AG form is hyphenated, per AG-02 and AG-16.
    ${title}            Document title.           e.g.  Interoperable Master Format - Core
    ${repository}       This repository's BARE public name, with no owner prefix and no
                        -private suffix.          e.g.  st2140-1
    ${repo_suffix}      -private   for a private working repo (the usual case)
                        (empty)    for a public repo published under its own name, e.g. an AG
    ${visibility_note}  One italicised line stating who can see this repository:
                        private:  _This repository is private and accessible only to SMPTE Standards Community members._
                        public:   _This repository is public._
TEMPLATE-TOKENS:END -->

# SMPTE _${doc_number}_ - _${title}_

${visibility_note}

* [Latest version](https://doc.smpte-doc.org/${repository}${repo_suffix}/main/)
* [Latest version (all artifacts)](https://doc.smpte-doc.org/${repository}${repo_suffix}/main/pub-artifacts.html)

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md) and [PATENTS.md](./PATENTS.md) for
important notices.

Unless specified otherwise, the contents of this repository are licensed as
indicated at [LICENSE.md](./LICENSE.md).

All published version(s) of this document can be found at <https://pub.smpte.org/doc/${repository}/>

## Reporting issues

Issues should be reported at <https://github.com/SMPTE/${repository}/issues>.
