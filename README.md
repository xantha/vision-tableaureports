# vision-tableaureports
tableau reports for VPM

vision performance management is a BI module that we license from deltek. 

this works hand in hand with the sql server analysis cubes in the vision-datawarehouse repository.

the module licenses an older version of Tableau (and we have to go through Deltek for any Tableau issues). 

Currently (18 May 2021) running
Tableau Server Version: 9.3.5 (9300.16.0726.1843) 64-bit

infrastructure
- Tableau server (prod: visionpm / dev: visionpmdev)
- postgresql (prod: visionpm / dev: visionpmdev)
- SQL Server Analysis Services (prod: sqlclust / dev: sqldclust)

There's a stock set of reports that come with the module and Carrie R built many reports, Sean and Stephen have also contributed. Jane L and Jon R are now producing reports as well.

In order to develop and publish reports, the Deltek Vision Performance Management branded version of Tableau Desktop 9.3 must be installed.

User base: 40 user license, limited to C, BULs, Group Leaders, a few people in accounting, and the sweng team. 

