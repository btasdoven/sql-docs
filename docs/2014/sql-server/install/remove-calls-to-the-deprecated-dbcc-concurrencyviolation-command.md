---
title: "Remove calls to the deprecated DBCC CONCURRENCYVIOLATION command | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 2cc9f6ff-de36-4e94-bd04-59f5c45c4911
caps.latest.revision: 7
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
---
# Remove calls to the deprecated DBCC CONCURRENCYVIOLATION command
  Upgrade Advisor detected the use of the DBCC CONCURRENCYVIOLATION command. This command is no longer available. Executing this command returns error 2526.  
  
## Component  
 [!INCLUDE[ssDE](../../includes/ssde-md.md)]  
  
## Description  
 No recent version of edition of [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] includes a workload governor; therefore the command has been removed.  
  
## Corrective Action  
 Update applications and scripts to remove references to this deprecated command.  
  
## External Resources  
  