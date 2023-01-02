# LABO Automation en Orchestration

Dit labo bevat de basis opstelling voor de modules automation en orchestration.

Er zijn 3 varianten van het labo

- De **clean** variant zonder enige config
- De **base** variant met een basis, correcte config
- De **lab** variant met een basis config met configuratie fouten

Voor de **base** en **lab** opstellingen vind je een labo in de `gns3` map en de respectievelijke startup configs in `startup-configs`.

## Opstelling
![Opstelling](lab-02-01-layout.png)

Je kan alle startup configuraties vinden in de `startup-config` map. Een voorgeconfigureerd GNS3 labo kan je vinden in de `gns3` map.

## Devices

* 1 x Internet toegang
* 1 x L2 SW
* 2 x IOSv
* 6 x IOSvL2
* 3 x VPCS
* 1 x Ubuntu machine
  * De Ubuntu machine is verbonden via een cloud node. Zodoende kan je je eigen virtuele machine gebruiken binnen GNS3

## Verificatie

Als de basis opstelling correct uitgevoerd is kan de ubuntu machine het management ip van elk toestel pingen.