
#### [Current]
 * [7ae9cb7](../../commit/7ae9cb7) - __(Joshua Hoblitt)__ Merge pull request [#6](../../issues/6) from oholiab/master

Case out unused parameters in rules.pp
 * [f212f03](../../commit/f212f03) - __(Joshua Hoblitt)__ Merge pull request [#7](../../issues/7) from pecastro/master

Allow usage on more recent Fedora systems.
 * [afd6ec5](../../commit/afd6ec5) - __(Paulo E. Castro)__ Reinstate the operatingsystem check.
 * [6cab5a5](../../commit/6cab5a5) - __(Paulo E. Castro)__ Allow usage on more recent Fedora systems.
 * [a9ac08d](../../commit/a9ac08d) - __(Matt Carroll)__ Case out unused parameters in rules.pp

Was breaking because of empty source in puppet 3.6.2

#### v1.1.0
 * [f936f90](../../commit/f936f90) - __(Joshua Hoblitt)__ Merge pull request [#5](../../issues/5) from jhoblitt/feature/v1.1.0

bump version to v1.1.0
 * [292831d](../../commit/292831d) - __(Joshua Hoblitt)__ add el5.x to supported platforms list
 * [183c640](../../commit/183c640) - __(Joshua Hoblitt)__ bump version to v1.1.0
 * [5fc917e](../../commit/5fc917e) - __(Joshua Hoblitt)__ Merge pull request [#4](../../issues/4) from nosolutions/rhel5
 * [5340961](../../commit/5340961) - __(Joshua Hoblitt)__ update travis matrix
 * [308052a](../../commit/308052a) - __(Joshua Hoblitt)__ update .gitignore
 * [df9fe39](../../commit/df9fe39) - __(Joshua Hoblitt)__ update LICNESE copyright notice
 * [904a9ce](../../commit/904a9ce) - __(Klaus Wagner)__ Extend module to support RHEL5 as well because the udev utilies have different names. Also implement a protection method udev.conf in case override is not expected. (New param config_file_replace)
 * [2111a85](../../commit/2111a85) - __(Klaus Wagner)__ Change stdlib uri to http for easier calling behind proxy

#### v1.0.3
 * [64ba826](../../commit/64ba826) - __(Joshua Hoblitt)__ bump version to v1.0.3
 * [00253ed](../../commit/00253ed) - __(Joshua Hoblitt)__ Merge pull request [#3](../../issues/3) from Mayflower/support_ubuntu

add osfamily debian to params
 * [92f8e41](../../commit/92f8e41) - __(codec)__ update spec to fail on OpenSuSE / incl. Debian
 * [2a781a0](../../commit/2a781a0) - __(codec)__ add osfamily debian to params

#### v1.0.2
 * [bf84ffb](../../commit/bf84ffb) - __(Joshua Hoblitt)__ bump version to v1.0.2
 * [19ca764](../../commit/19ca764) - __(Joshua Hoblitt)__ fix resource ordering + implement anchor pattern
 * [c8f12f3](../../commit/c8f12f3) - __(Joshua Hoblitt)__ add simple rspec-system tests
 * [d9fa183](../../commit/d9fa183) - __(Joshua Hoblitt)__ fix erb local variable warning

    Warning: Variable access via 'udev_log' is deprecated. Use '@udev_log' instead. template[/etc/puppet/modules/udev/templates/udev.conf.erb]:4

#### v1.0.1
 * [5dc0074](../../commit/5dc0074) - __(Joshua Hoblitt)__ bump version to v1.0.1
 * [ac1f89d](../../commit/ac1f89d) - __(Joshua Hoblitt)__ add compatibility with older puppet 2.7.x
 * [f8bebb9](../../commit/f8bebb9) - __(Joshua Hoblitt)__ update README boilerplate sections, formatting, and ToC
 * [e077a61](../../commit/e077a61) - __(Joshua Hoblitt)__ add :require to all gems in Gemfile
 * [84ba892](../../commit/84ba892) - __(Joshua Hoblitt)__ add puppet 2.7.3 (fixed version) to travis matrix
 * [22f58cc](../../commit/22f58cc) - __(Joshua Hoblitt)__ change travis puppet 2.7.0 -> 2.7.1

#### v1.0.0
 * [1257c33](../../commit/1257c33) - __(Joshua Hoblitt)__ change version to v1.0.0
 * [ba528ec](../../commit/ba528ec) - __(Joshua Hoblitt)__ change stdlib dep to v3.0.0

The oldest version with `ensure_resource()`

 * [8e01b22](../../commit/8e01b22) - __(Joshua Hoblitt)__ add a blurb about concat to the README
 * [25c837e](../../commit/25c837e) - __(Joshua Hoblitt)__ missing comma in README example
 * [3a469e7](../../commit/3a469e7) - __(Joshua Hoblitt)__ simplify udev::rule implementation
 * [a69f1b8](../../commit/a69f1b8) - __(Joshua Hoblitt)__ rename udev::udevadm -> udev::udevadm::trigger

For naming consistency with udev::udevadm::logpriority

 * [1ca5e24](../../commit/1ca5e24) - __(Joshua Hoblitt)__ README fixes
 * [35266b7](../../commit/35266b7) - __(Joshua Hoblitt)__ add puppet 3.3.0 to travis test matrix
 * [fedd155](../../commit/fedd155) - __(Joshua Hoblitt)__ add syslog verbosity management
 * [db481ed](../../commit/db481ed) - __(Joshua Hoblitt)__ suppress lint warnings
 * [227ab81](../../commit/227ab81) - __(Joshua Hoblitt)__ README update
 * [252b81c](../../commit/252b81c) - __(Joshua Hoblitt)__ fix Modulefile to be valid
 * [8e79572](../../commit/8e79572) - __(Joshua Hoblitt)__ add class udev::rule to manage device rule files
 * [112ebab](../../commit/112ebab) - __(Joshua Hoblitt)__ add class udev::udevadm to manage `udevadm trigger`
 * [b6821fe](../../commit/b6821fe) - __(Joshua Hoblitt)__ add udev package installation support
 * [738cea0](../../commit/738cea0) - __(Joshua Hoblitt)__ Merge puppet-module_skel
 * [4f9f7c8](../../commit/4f9f7c8) - __(Joshua Hoblitt)__ first commit
