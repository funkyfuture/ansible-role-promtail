# Changelog

## [1.7.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.7.0) (2020-10-28)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.6.1...1.7.0)

**Implemented enhancements:**

- Chore\(binary\) update promtail to 2.0.0 [\#32](https://github.com/patrickjahns/ansible-role-promtail/pull/32) ([abmurksi](https://github.com/abmurksi))

**Merged pull requests:**

- ci: test with ansible 2.10 [\#36](https://github.com/patrickjahns/ansible-role-promtail/pull/36) ([patrickjahns](https://github.com/patrickjahns))
- fix: fix tests by including new required molecule-docker dependency [\#33](https://github.com/patrickjahns/ansible-role-promtail/pull/33) ([patrickjahns](https://github.com/patrickjahns))

## [1.6.1](https://github.com/patrickjahns/ansible-role-promtail/tree/1.6.1) (2020-09-11)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.6.0...1.6.1)

**Merged pull requests:**

- chore\(binary\): update promtail to 1.6.1 [\#29](https://github.com/patrickjahns/ansible-role-promtail/pull/29) ([abmurksi](https://github.com/abmurksi))

## [1.6.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.6.0) (2020-09-03)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.5.0...1.6.0)

**Fixed bugs:**

- fix: specify provide permissions for file related tasks [\#27](https://github.com/patrickjahns/ansible-role-promtail/pull/27) ([patrickjahns](https://github.com/patrickjahns))

**Merged pull requests:**

- chore\(binary\): update promtail to version 1.6.0 [\#26](https://github.com/patrickjahns/ansible-role-promtail/pull/26) ([secustor](https://github.com/secustor))

## [1.5.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.5.0) (2020-07-29)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.4.0...1.5.0)

**Implemented enhancements:**

- Make role compatible with arm architecture [\#20](https://github.com/patrickjahns/ansible-role-promtail/issues/20)

**Fixed bugs:**

- Replace the rest of the hardcoded references to amd64 with {{ go\_arch }} [\#23](https://github.com/patrickjahns/ansible-role-promtail/pull/23) ([mkeesey](https://github.com/mkeesey))

## [1.4.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.4.0) (2020-05-27)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.3.1...1.4.0)

**Implemented enhancements:**

- feat: add support for arm architecture [\#22](https://github.com/patrickjahns/ansible-role-promtail/pull/22) ([patrickjahns](https://github.com/patrickjahns))
- Promtail 1.5.0 [\#17](https://github.com/patrickjahns/ansible-role-promtail/pull/17) ([patrickjahns](https://github.com/patrickjahns))

## [1.3.1](https://github.com/patrickjahns/ansible-role-promtail/tree/1.3.1) (2020-05-26)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.3.0...1.3.1)

**Fixed bugs:**

- fix: raise privileges of restart handler [\#15](https://github.com/patrickjahns/ansible-role-promtail/pull/15) ([terorie](https://github.com/terorie))

## [1.3.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.3.0) (2020-05-10)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.2.0...1.3.0)

**Implemented enhancements:**

- Include canary [\#1](https://github.com/patrickjahns/ansible-role-promtail/issues/1)
- add support for ubuntu disco [\#13](https://github.com/patrickjahns/ansible-role-promtail/pull/13) ([patrickjahns](https://github.com/patrickjahns))
- Feat add file sd config [\#12](https://github.com/patrickjahns/ansible-role-promtail/pull/12) ([patrickjahns](https://github.com/patrickjahns))

## [1.2.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.2.0) (2020-04-11)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.1.0...1.2.0)

**Fixed bugs:**

- fix: renamed promtail\_config\_scrap\_configs to promtail\_config\_scrape\_configs [\#10](https://github.com/patrickjahns/ansible-role-promtail/pull/10) ([patrickjahns](https://github.com/patrickjahns))

**Merged pull requests:**

- feat: install promtail 1.4.1 by default [\#9](https://github.com/patrickjahns/ansible-role-promtail/pull/9) ([patrickjahns](https://github.com/patrickjahns))

## [1.1.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.1.0) (2020-03-01)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.0.1...1.1.0)

**Implemented enhancements:**

- feat: specify the log level for promtail [\#7](https://github.com/patrickjahns/ansible-role-promtail/pull/7) ([patrickjahns](https://github.com/patrickjahns))

**Merged pull requests:**

- Updated repository settings and added release automation [\#5](https://github.com/patrickjahns/ansible-role-promtail/pull/5) ([patrickjahns](https://github.com/patrickjahns))
- added ansible-later for more indepth static code analysis [\#3](https://github.com/patrickjahns/ansible-role-promtail/pull/3) ([patrickjahns](https://github.com/patrickjahns))

## [1.0.1](https://github.com/patrickjahns/ansible-role-promtail/tree/1.0.1) (2020-02-09)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/1.0.0...1.0.1)

**Fixed bugs:**

- fix: failing installation on ubuntu1604 [\#2](https://github.com/patrickjahns/ansible-role-promtail/pull/2) ([patrickjahns](https://github.com/patrickjahns))

## [1.0.0](https://github.com/patrickjahns/ansible-role-promtail/tree/1.0.0) (2020-02-08)

[Full Changelog](https://github.com/patrickjahns/ansible-role-promtail/compare/87a46bd92a106bffd43e000a4579c1a444bfbf2e...1.0.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
