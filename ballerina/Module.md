## Package overview

This Package bundles the latest OracleDB drivers so that the OracleDB connector can be used in ballerina projects easily.

## Compatibility

| |        Version         |
|:---|:----------------------:|
|Ballerina Language | **Swan Lake 2201.3.0** |
|OracleDB Driver(ojdbc10) |      **19.6.0.0**      |
|XDB |      **21.3.0.0**      |
|Xmlparserv2 |      **21.3.0.0**      |


> The above OracleDB drivers are released under the [Oracle Free Use Terms and Conditions](https://www.oracle.com/downloads/licenses/oracle-free-license.html). 

## Usage

To add the OracleDB driver dependency the project, simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/oracledb;
import ballerinax/oracledb.driver as _;
```
