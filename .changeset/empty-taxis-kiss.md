---
'openzeppelin-solidity': major
---

`UUPSUpgradeable`, `ProxyAdmin`: Removed `upgradeTo` and `upgrade` functions, and made `upgradeToAndCall` and `upgradeAndCall` ignore the data argument if it is empty. It is no longer possible to invoke the receive function along with an upgrade.