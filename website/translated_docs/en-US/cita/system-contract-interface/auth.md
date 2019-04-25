---
id: auth
title: Authorization Management Contract
---

<h2 class="hover-list">Authorization Management</h2>

* [queryPermissions](#queryPermissions)
* [queryAccounts](#queryAccounts)
* [queryAllAccounts](#queryAllAccounts)
* [checkResource](#checkResource)
* [checkPermission](#checkPermission)

* * *

### queryPermissions

查询账户拥有的权限

* 参数
    
    `address` - 待查询的账户地址

* 返回值
    
    `address[]` - 权限地址列表

### queryAccounts

查询拥有某个权限的所有账户

* 参数
    
    `address` - 待查询的权限地址

* 返回值
    
    `address[]` - 账户地址列表

### queryAllAccounts

查询拥有权限的所有账户

* 参数
    
    `address` - 待查询的权限地址

* 返回值
    
    `address[]` - 账户地址列表

### checkResource

> 废弃

### checkPermission

* 参数
    
    `address` - 待判断的账户地址 `address` - 待判断的权限地址

* 返回值
    
    `bool` - 账户拥有权限则为真，反之则反