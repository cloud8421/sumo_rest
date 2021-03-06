# Change Log

## [0.2.1](https://github.com/inaka/sumo_rest/tree/0.2.1) (2016-09-14)
[Full Changelog](https://github.com/inaka/sumo_rest/compare/0.2.0...0.2.1)

**Closed issues:**

- Error results from sumo\_rest\_doc's update callback are improperly handled [\#44](https://github.com/inaka/sumo_rest/issues/44)
- Add "\_=\>\_" to the state\(\) types [\#43](https://github.com/inaka/sumo_rest/issues/43)

**Merged pull requests:**

- \[\#44\] update error handled with sr\_json:error/1 [\#46](https://github.com/inaka/sumo_rest/pull/46) ([ferigis](https://github.com/ferigis))
- \[\#43\] state\(\) types fixed [\#45](https://github.com/inaka/sumo_rest/pull/45) ([ferigis](https://github.com/ferigis))

## [0.2.0](https://github.com/inaka/sumo_rest/tree/0.2.0) (2016-09-12)
[Full Changelog](https://github.com/inaka/sumo_rest/compare/0.1.2...0.2.0)

**Fixed bugs:**

- Properly differentiate between sumo\_db's models and modules [\#40](https://github.com/inaka/sumo_rest/pull/40) ([elbrujohalcon](https://github.com/elbrujohalcon))

**Closed issues:**

- Move this project to Rebar3 [\#41](https://github.com/inaka/sumo_rest/issues/41)
- Upgrade dependencies [\#38](https://github.com/inaka/sumo_rest/issues/38)
- rebar3 compile -\> failing [\#30](https://github.com/inaka/sumo_rest/issues/30)
- Update repo and make it ready for hex.pm [\#28](https://github.com/inaka/sumo_rest/issues/28)
- Hex Package [\#9](https://github.com/inaka/sumo_rest/issues/9)
- Use query-string for filtering [\#8](https://github.com/inaka/sumo_rest/issues/8)
- Increase swagger integration [\#7](https://github.com/inaka/sumo_rest/issues/7)

**Merged pull requests:**

- \[\#38\] updated sumo\_db dep and now it is working with OTP-19 [\#39](https://github.com/inaka/sumo_rest/pull/39) ([ferigis](https://github.com/ferigis))
- Updated readme [\#37](https://github.com/inaka/sumo_rest/pull/37) ([HernanRivasAcosta](https://github.com/HernanRivasAcosta))
- Handle params in query-string [\#35](https://github.com/inaka/sumo_rest/pull/35) ([zgbjgg](https://github.com/zgbjgg))
- resolves \#7 [\#33](https://github.com/inaka/sumo_rest/pull/33) ([zsoci](https://github.com/zsoci))
- \[Fix \#30\] Fix rebar3 compilation by updating swagger, trails and sumo\_db dependencies [\#31](https://github.com/inaka/sumo_rest/pull/31) ([harenson](https://github.com/harenson))
- \[Fix \#28\] Update dependencies; Update erlang.mk; Add ruleset to elvis config; Add rebar.config file [\#29](https://github.com/inaka/sumo_rest/pull/29) ([harenson](https://github.com/harenson))
- Version Bump to 0.2.0 [\#42](https://github.com/inaka/sumo_rest/pull/42) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Make the project rebar3 compatible [\#6](https://github.com/inaka/sumo_rest/pull/6) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.2](https://github.com/inaka/sumo_rest/tree/0.1.2) (2016-03-11)
[Full Changelog](https://github.com/inaka/sumo_rest/compare/0.1.1...0.1.2)

**Closed issues:**

- Bump version to 0.1.2 [\#25](https://github.com/inaka/sumo_rest/issues/25)
- Missing iso8601 in sumo\_rest.app.src applications list [\#24](https://github.com/inaka/sumo_rest/issues/24)

**Merged pull requests:**

- \[Fix \#25\] Bump version to 0.1.2 [\#27](https://github.com/inaka/sumo_rest/pull/27) ([harenson](https://github.com/harenson))
- \[Fix \#24\] Add iso8601 to the app.src applications list [\#26](https://github.com/inaka/sumo_rest/pull/26) ([harenson](https://github.com/harenson))

## [0.1.1](https://github.com/inaka/sumo_rest/tree/0.1.1) (2015-12-15)
[Full Changelog](https://github.com/inaka/sumo_rest/compare/0.1.0...0.1.1)

**Closed issues:**

- Version Bump to 0.1.1 [\#22](https://github.com/inaka/sumo_rest/issues/22)
- Path variables are not take in account when building the location header [\#20](https://github.com/inaka/sumo_rest/issues/20)
- Link to sr\_test.app file is broken [\#18](https://github.com/inaka/sumo_rest/issues/18)

**Merged pull requests:**

- \[Fix \#22\] Bump version to 0.1.1 [\#23](https://github.com/inaka/sumo_rest/pull/23) ([harenson](https://github.com/harenson))
- \[Fix \#20\] Rename uri\_path/1 to location/2 and change its functionality... [\#21](https://github.com/inaka/sumo_rest/pull/21) ([harenson](https://github.com/harenson))
- \[Fix \#18\] repair broken link [\#19](https://github.com/inaka/sumo_rest/pull/19) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.0](https://github.com/inaka/sumo_rest/tree/0.1.0) (2015-12-02)
[Full Changelog](https://github.com/inaka/sumo_rest/compare/0.0.1...0.1.0)

**Fixed bugs:**

- Invalid Content-Type for error responses [\#14](https://github.com/inaka/sumo_rest/pull/14) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Add 'patch' to the allowed methods in atom\_to\_method [\#13](https://github.com/inaka/sumo_rest/pull/13) ([elbrujohalcon](https://github.com/elbrujohalcon))

**Closed issues:**

- Fulfil the open-source checklist [\#1](https://github.com/inaka/sumo_rest/issues/1)
- Create a sample application [\#5](https://github.com/inaka/sumo_rest/issues/5)

**Merged pull requests:**

- Version bump to 0.1.0 [\#17](https://github.com/inaka/sumo_rest/pull/17) ([elbrujohalcon](https://github.com/elbrujohalcon))
- README [\#16](https://github.com/inaka/sumo_rest/pull/16) ([elbrujohalcon](https://github.com/elbrujohalcon))
- \[\#1\] Initial step [\#15](https://github.com/inaka/sumo_rest/pull/15) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Update cowboy-swagger dep and remove the hack [\#12](https://github.com/inaka/sumo_rest/pull/12) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Reach 100% Code Coverage on Tests [\#10](https://github.com/inaka/sumo_rest/pull/10) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Create sumo\_single\_entity\_handler [\#4](https://github.com/inaka/sumo_rest/pull/4) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Create sumo\_entities\_handler [\#3](https://github.com/inaka/sumo_rest/pull/3) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Initial project setup [\#2](https://github.com/inaka/sumo_rest/pull/2) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.0.1](https://github.com/inaka/sumo_rest/tree/0.0.1) (2015-11-28)
**Merged pull requests:**

- Release Version 0.0.1 [\#11](https://github.com/inaka/sumo_rest/pull/11) ([elbrujohalcon](https://github.com/elbrujohalcon))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*