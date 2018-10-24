# Change Log

## [v1.1.4](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.1.4) (2018-10-24)
[Full Changelog](https://github.com/DEFRA/waste-carriers-front-office/compare/v1.1.3...v1.1.4)

**Merged pull requests:**

- Bump rspec-rails from 3.8.0 to 3.8.1 [\#103](https://github.com/DEFRA/waste-carriers-front-office/pull/103) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `fd941fb` to `bec6d58` [\#102](https://github.com/DEFRA/waste-carriers-front-office/pull/102) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.1.3](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.1.3) (2018-10-18)
[Full Changelog](https://github.com/DEFRA/waste-carriers-front-office/compare/v1.1.2...v1.1.3)

**Implemented enhancements:**

- Modify CSP to allow removal of PII in GTM [\#97](https://github.com/DEFRA/waste-carriers-front-office/pull/97) ([irisfaraway](https://github.com/irisfaraway))

**Merged pull requests:**

- Bump waste\_carriers\_engine from `231e839` to `fd941fb` [\#100](https://github.com/DEFRA/waste-carriers-front-office/pull/100) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `d6b6696` to `231e839` [\#98](https://github.com/DEFRA/waste-carriers-front-office/pull/98) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `3565d4e` to `d6b6696` [\#96](https://github.com/DEFRA/waste-carriers-front-office/pull/96) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.1.2](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.1.2) (2018-10-10)
[Full Changelog](https://github.com/DEFRA/waste-carriers-front-office/compare/v1.1.1...v1.1.2)

**Merged pull requests:**

- Bump waste\_carriers\_engine from `4297b34` to `3565d4e` [\#95](https://github.com/DEFRA/waste-carriers-front-office/pull/95) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `0f1f11b` to `4297b34` [\#94](https://github.com/DEFRA/waste-carriers-front-office/pull/94) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.1.1](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.1.1) (2018-10-05)
[Full Changelog](https://github.com/DEFRA/waste-carriers-front-office/compare/v1.1...v1.1.1)

**Merged pull requests:**

- Bump waste\_carriers\_engine from `75a23f7` to `0f1f11b` [\#93](https://github.com/DEFRA/waste-carriers-front-office/pull/93) ([dependabot[bot]](https://github.com/apps/dependabot))
- \[Security\] Bump nokogiri from 1.8.4 to 1.8.5 [\#91](https://github.com/DEFRA/waste-carriers-front-office/pull/91) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.1](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.1) (2018-09-26)
[Full Changelog](https://github.com/DEFRA/waste-carriers-front-office/compare/v1.0...v1.1)

**Implemented enhancements:**

- Invalidate user session cookies after logout [\#83](https://github.com/DEFRA/waste-carriers-front-office/pull/83) ([irisfaraway](https://github.com/irisfaraway))

**Fixed bugs:**

- Stop users accessing pages with back button after signout [\#85](https://github.com/DEFRA/waste-carriers-front-office/pull/85) ([irisfaraway](https://github.com/irisfaraway))

**Merged pull requests:**

- Bump waste\_carriers\_engine from `9ed1a21` to `75a23f7` [\#89](https://github.com/DEFRA/waste-carriers-front-office/pull/89) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump passenger from 5.3.4 to 5.3.5 [\#88](https://github.com/DEFRA/waste-carriers-front-office/pull/88) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `ae7499f` to `9ed1a21` [\#87](https://github.com/DEFRA/waste-carriers-front-office/pull/87) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rubocop from 0.59.1 to 0.59.2 [\#86](https://github.com/DEFRA/waste-carriers-front-office/pull/86) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.0](https://github.com/DEFRA/waste-carriers-front-office/tree/v1.0) (2018-09-18)
**Implemented enhancements:**

- Configure front-office to send emails via SendGrid [\#73](https://github.com/DEFRA/waste-carriers-front-office/pull/73) ([irisfaraway](https://github.com/irisfaraway))
- Test converting active upper tier regs to transient objects [\#70](https://github.com/DEFRA/waste-carriers-front-office/pull/70) ([irisfaraway](https://github.com/irisfaraway))
- Setup GA for project using the GOOGLE\_TAGMANAGER\_ID environment variable [\#69](https://github.com/DEFRA/waste-carriers-front-office/pull/69) ([baphled](https://github.com/baphled))
- Add specific support for ELB health check calls [\#43](https://github.com/DEFRA/waste-carriers-front-office/pull/43) ([Cruikshanks](https://github.com/Cruikshanks))
- Add Passenger web app server to project [\#7](https://github.com/DEFRA/waste-carriers-front-office/pull/7) ([Cruikshanks](https://github.com/Cruikshanks))

**Fixed bugs:**

- Fix reg to trans test to override Mongo timeout [\#72](https://github.com/DEFRA/waste-carriers-front-office/pull/72) ([Cruikshanks](https://github.com/Cruikshanks))
- Fix routing to ensure /fo/ path is included [\#47](https://github.com/DEFRA/waste-carriers-front-office/pull/47) ([Cruikshanks](https://github.com/Cruikshanks))
- Ignore Passengerfile.json [\#8](https://github.com/DEFRA/waste-carriers-front-office/pull/8) ([Cruikshanks](https://github.com/Cruikshanks))
- Airbrake/Errbit projecy env var wrong name [\#6](https://github.com/DEFRA/waste-carriers-front-office/pull/6) ([Cruikshanks](https://github.com/Cruikshanks))
- Fix changelog generator breaking deploy to heroku [\#5](https://github.com/DEFRA/waste-carriers-front-office/pull/5) ([Cruikshanks](https://github.com/Cruikshanks))

**Merged pull requests:**

- Bump waste\_carriers\_engine from `d1ee300` to `ae7499f` [\#82](https://github.com/DEFRA/waste-carriers-front-office/pull/82) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `c67419b` to `d1ee300` [\#80](https://github.com/DEFRA/waste-carriers-front-office/pull/80) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `8667cef` to `c67419b` [\#78](https://github.com/DEFRA/waste-carriers-front-office/pull/78) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rubocop from 0.59.0 to 0.59.1 [\#75](https://github.com/DEFRA/waste-carriers-front-office/pull/75) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `6d5713b` to `8667cef` [\#71](https://github.com/DEFRA/waste-carriers-front-office/pull/71) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump uglifier from 4.1.18 to 4.1.19 [\#68](https://github.com/DEFRA/waste-carriers-front-office/pull/68) ([dependabot[bot]](https://github.com/apps/dependabot))
- changing registration seed data to cause conviction flag [\#67](https://github.com/DEFRA/waste-carriers-front-office/pull/67) ([timstone](https://github.com/timstone))
- Bump waste\_carriers\_engine from `f33eaaf` to `6d5713b` [\#66](https://github.com/DEFRA/waste-carriers-front-office/pull/66) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rubocop from 0.58.2 to 0.59.0 [\#65](https://github.com/DEFRA/waste-carriers-front-office/pull/65) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump factory\_bot\_rails from 4.11.0 to 4.11.1 [\#64](https://github.com/DEFRA/waste-carriers-front-office/pull/64) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `3a2ac10` to `f33eaaf` [\#63](https://github.com/DEFRA/waste-carriers-front-office/pull/63) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `2d39589` to `3a2ac10` [\#62](https://github.com/DEFRA/waste-carriers-front-office/pull/62) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `9a8822b` to `2d39589` [\#61](https://github.com/DEFRA/waste-carriers-front-office/pull/61) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `ad6efb6` to `9a8822b` [\#60](https://github.com/DEFRA/waste-carriers-front-office/pull/60) ([dependabot[bot]](https://github.com/apps/dependabot))
- new seed data for assisted digital renewals [\#59](https://github.com/DEFRA/waste-carriers-front-office/pull/59) ([timstone](https://github.com/timstone))
- Bump waste\_carriers\_engine from `ff379ae` to `ad6efb6` [\#58](https://github.com/DEFRA/waste-carriers-front-office/pull/58) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `c0aa771` to `ff379ae` [\#56](https://github.com/DEFRA/waste-carriers-front-office/pull/56) ([dependabot[bot]](https://github.com/apps/dependabot))
- Update deprecated static attributes in factories [\#55](https://github.com/DEFRA/waste-carriers-front-office/pull/55) ([irisfaraway](https://github.com/irisfaraway))
- Bump turbolinks from 5.1.1 to 5.2.0 [\#54](https://github.com/DEFRA/waste-carriers-front-office/pull/54) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `058ac7f` to `c0aa771` [\#53](https://github.com/DEFRA/waste-carriers-front-office/pull/53) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump factory\_bot\_rails from 4.10.0 to 4.11.0 [\#52](https://github.com/DEFRA/waste-carriers-front-office/pull/52) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `6a8414e` to `058ac7f` [\#51](https://github.com/DEFRA/waste-carriers-front-office/pull/51) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump devise from 4.4.3 to 4.5.0 [\#50](https://github.com/DEFRA/waste-carriers-front-office/pull/50) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `bd1f376` to `6a8414e` [\#49](https://github.com/DEFRA/waste-carriers-front-office/pull/49) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `642fee6` to `bd1f376` [\#48](https://github.com/DEFRA/waste-carriers-front-office/pull/48) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `fcb4475` to `642fee6` [\#46](https://github.com/DEFRA/waste-carriers-front-office/pull/46) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump uglifier from 4.1.17 to 4.1.18 [\#45](https://github.com/DEFRA/waste-carriers-front-office/pull/45) ([dependabot[bot]](https://github.com/apps/dependabot))
- Change seed email addresses [\#44](https://github.com/DEFRA/waste-carriers-front-office/pull/44) ([irisfaraway](https://github.com/irisfaraway))
- Enable force\_ssl in production [\#42](https://github.com/DEFRA/waste-carriers-front-office/pull/42) ([Cruikshanks](https://github.com/Cruikshanks))
- Raise translation errors when running tests [\#41](https://github.com/DEFRA/waste-carriers-front-office/pull/41) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `c8a2a9e` to `fcb4475` [\#40](https://github.com/DEFRA/waste-carriers-front-office/pull/40) ([dependabot[bot]](https://github.com/apps/dependabot))
- Remove unused ApplicationHelper [\#39](https://github.com/DEFRA/waste-carriers-front-office/pull/39) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `2215c20` to `c8a2a9e` [\#38](https://github.com/DEFRA/waste-carriers-front-office/pull/38) ([dependabot[bot]](https://github.com/apps/dependabot))
- Set config value for metaData.route [\#37](https://github.com/DEFRA/waste-carriers-front-office/pull/37) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `337f3d1` to `2215c20` [\#36](https://github.com/DEFRA/waste-carriers-front-office/pull/36) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rspec-rails from 3.7.2 to 3.8.0 [\#35](https://github.com/DEFRA/waste-carriers-front-office/pull/35) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `c32299c` to `337f3d1` [\#34](https://github.com/DEFRA/waste-carriers-front-office/pull/34) ([dependabot[bot]](https://github.com/apps/dependabot))
- Fix broken footer links [\#33](https://github.com/DEFRA/waste-carriers-front-office/pull/33) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `8e389be` to `c32299c` [\#32](https://github.com/DEFRA/waste-carriers-front-office/pull/32) ([dependabot[bot]](https://github.com/apps/dependabot))
- Set the host in application config [\#31](https://github.com/DEFRA/waste-carriers-front-office/pull/31) ([irisfaraway](https://github.com/irisfaraway))
- WC-356 Cookies page update [\#30](https://github.com/DEFRA/waste-carriers-front-office/pull/30) ([timstone](https://github.com/timstone))
- Use WEBrick in test environment [\#29](https://github.com/DEFRA/waste-carriers-front-office/pull/29) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `d8b6576` to `8e389be` [\#28](https://github.com/DEFRA/waste-carriers-front-office/pull/28) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump passenger from 5.3.3 to 5.3.4 [\#27](https://github.com/DEFRA/waste-carriers-front-office/pull/27) ([dependabot[bot]](https://github.com/apps/dependabot))
- Mount renewals engine in a directory, not root [\#26](https://github.com/DEFRA/waste-carriers-front-office/pull/26) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `cf3d8ce` to `37d42eb` [\#25](https://github.com/DEFRA/waste-carriers-front-office/pull/25) ([dependabot[bot]](https://github.com/apps/dependabot))
- Move users out of engine [\#24](https://github.com/DEFRA/waste-carriers-front-office/pull/24) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `047a7c4` to `cf3d8ce` [\#23](https://github.com/DEFRA/waste-carriers-front-office/pull/23) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump uglifier from 4.1.16 to 4.1.17 [\#22](https://github.com/DEFRA/waste-carriers-front-office/pull/22) ([dependabot[bot]](https://github.com/apps/dependabot))
- Fix seeding after field renaming [\#21](https://github.com/DEFRA/waste-carriers-front-office/pull/21) ([irisfaraway](https://github.com/irisfaraway))
- Bump waste\_carriers\_engine from `38dd85a` to `047a7c4` [\#20](https://github.com/DEFRA/waste-carriers-front-office/pull/20) ([dependabot[bot]](https://github.com/apps/dependabot))
- Set secret\_key\_base when run under prod & rake [\#19](https://github.com/DEFRA/waste-carriers-front-office/pull/19) ([Cruikshanks](https://github.com/Cruikshanks))
- Bump waste\_carriers\_engine from `d0281f2` to `38dd85a` [\#18](https://github.com/DEFRA/waste-carriers-front-office/pull/18) ([dependabot[bot]](https://github.com/apps/dependabot))
- Add branch to WCR renewals Gemfile entry [\#17](https://github.com/DEFRA/waste-carriers-front-office/pull/17) ([Cruikshanks](https://github.com/Cruikshanks))
- Bump rubocop from 0.58.1 to 0.58.2 [\#15](https://github.com/DEFRA/waste-carriers-front-office/pull/15) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump waste\_carriers\_engine from `a1c4067` to `ced04a0` [\#14](https://github.com/DEFRA/waste-carriers-front-office/pull/14) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump uglifier from 4.1.14 to 4.1.16 [\#12](https://github.com/DEFRA/waste-carriers-front-office/pull/12) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump govuk\_elements\_rails from 3.1.2 to 3.1.3 [\#11](https://github.com/DEFRA/waste-carriers-front-office/pull/11) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rubocop from 0.57.2 to 0.58.1 [\#9](https://github.com/DEFRA/waste-carriers-front-office/pull/9) ([dependabot[bot]](https://github.com/apps/dependabot))
- Sync dev and test secret keys across WCR service [\#4](https://github.com/DEFRA/waste-carriers-front-office/pull/4) ([Cruikshanks](https://github.com/Cruikshanks))
- Refactor mongoid config to use URI's [\#3](https://github.com/DEFRA/waste-carriers-front-office/pull/3) ([Cruikshanks](https://github.com/Cruikshanks))
-  Mount the WasteCarriersEngine and start configuration [\#2](https://github.com/DEFRA/waste-carriers-front-office/pull/2) ([irisfaraway](https://github.com/irisfaraway))
- Set up CI [\#1](https://github.com/DEFRA/waste-carriers-front-office/pull/1) ([irisfaraway](https://github.com/irisfaraway))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*