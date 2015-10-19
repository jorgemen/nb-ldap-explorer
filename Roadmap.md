# Milestones #

| **Version** | **Date** | **Status** | **Focus / Notes** |
|:------------|:---------|:-----------|:------------------|
| ~~0.1~~     | ~~14-feb~~ | ~~Completed~~ | ~~Very basic LDAP browsing component~~ |
| ~~0.2~~     | ~~16-feb~~ | ~~Completed~~ | ~~Multiple LDAP services + NetBeans 6.7 support~~ |
| ~~0.3~~     | ~~27-feb~~ | ~~Completed~~ | ~~NetBeanifying the code and adding some nicer looking icons~~ |
| ~~0.4~~     | ~~13-mar~~ | ~~Completed~~ | ~~Accepting SSL certificates~~ |
| **0.5**     | **TBD**  | **Not Started** | **LDAP queries**  |
| 0.6         | TBD      | Not Started | LDIF execution    |
| 1.0         | TBD      | Not Started | Bug fixes of previous versions |


# Changelog #

## 0.5 ##

  * Nothing yet

## 0.4 ##

  * Attributes are now sortable by clicking the column headings
  * Possible to give each LDAP server connection a label ([issue #3](https://code.google.com/p/nb-ldap-explorer/issues/detail?id=#3))
  * Fixed NamingException when having more than one server connection / window open ([issue #5](https://code.google.com/p/nb-ldap-explorer/issues/detail?id=#5))
  * Added connection timeout setting to LDAP server connection
  * More friendly attribute names
  * Support for Lotus Notes object classes ([issue #6](https://code.google.com/p/nb-ldap-explorer/issues/detail?id=#6))
  * Silently accepts self-signed SSL certificates
  * Basic filtering


## 0.3 ##

  * Scrolling in the LDAP tree (could only view very small trees in 0.2)
  * Replaced Swing-code with NetBeans classes (mainly replacing JTree with NetBeans nodes)
  * Nicer-looking icons + different icons depending on the type of LDAP entry (from http://rrze-icon-set.berlios.de/gallery.html)
  * Includes an update center for ease of upgrading to future versions

## 0.2 ##

  * Support for NetBeans 6.7
  * Possible to create LDAP connection profiles in the Services window
  * Cleaner browser window with option to see attributes in table and LDIF view.