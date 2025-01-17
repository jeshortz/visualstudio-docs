---
description: "A DCOM error occurred when the local machine tried to communicate with the remote machine."
title: "Unable to initiate DCOM communication"
ms.date: "11/04/2016"
ms.topic: "error-reference"
f1_keywords:
  - "vs.debug.error.unmarshal_server_failed"
dev_langs:
  - "CSharp"
  - "VB"
  - "FSharp"
  - "C++"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# Error: Unable to initiate DCOM communication

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
A DCOM error occurred when the local machine tried to communicate with the remote machine. This is caused by a firewall on the remote server or broken Windows authentication on the remote machine.

### To correct this error

- If the remote machine has Windows Firewall enabled, see [Remote Debugging](../debugger/remote-debugging.md) for instructions about how to configure the firewall for local debugging.

- To restore Windows authentication, try rebooting both machines. Examine event logs on local and remote machines for Kerberos errors and contact domain administrators for known problems.

## See also
- [Remote Debugging](../debugger/remote-debugging.md)
