---
# required metadata

title: Security limitations for SQL Server on Linux | Microsoft Docs
description: This topic describes SQL Server on Linux restrictions.
author: BYHAM 
ms.author: rickbyh 
manager: jhubbard
ms.date: 11/16/2016
ms.topic: article
ms.prod: sql-linux
ms.technology: database-engine
ms.assetid: 64da74cc-14bf-4636-a55e-8cc1fce2aaff

# optional metadata

# keywords: ""
# ROBOTS: ""
# audience: ""
# ms.devlang: ""
# ms.reviewer: ""
# ms.suite: ""
# ms.tgt_pltfrm: ""
# ms.custom: ""

---
# Security limitations for SQL Server on Linux

SQL Server on Linux currently has the following limitations: 

* Only SQL Server authentication is currently available.
* A standard password policy is provided. MUST_CHANGE is the only option you may configure.  
* Extensible Key Management is not supported. 
* Using keys stored in the Azure Key Vault is not supported.
* SQL Server generates its own self-signed certificate for encrypting connections. Currently, SQL Server cannot be configured to use a user provided certificate for SSL or TLS. 

For more infomation about security features available in SQL Server, see the [Security Center for SQL Server Database Engine and Azure SQL Database](https://msdn.microsoft.com/library/bb510589.aspx).

## Next steps

For common security tasks, see [Get started with security features of SQL Server on Linux](sql-server-linux-security-get-started.md).   
For a script to change the TCP port number, the SQL Server directories, and configure traceflags or collation, see [Configure SQL Server on Linux with mssql-conf](sql-server-linux-configure-mssql-conf.md).