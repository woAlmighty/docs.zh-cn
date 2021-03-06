---
title: ISOSDacInterface::GetModuleData 方法
ms.date: 02/01/2019
api.name:
- ISOSDacInterface::GetModuleData Method
api.location:
- mscordacwks.dll
api.type:
- COM
f1.keywords:
- ISOSDacInterface::GetModuleData Method
helpviewer.keywords:
- ISOSDacInterface::GetModuleData Method [.NET Framework debugging]
topic_type:
- apiref
author: hoyosjs
ms.author: juhoyosa
ms.openlocfilehash: 4cc4266f569c3fb3e70227ec2543b962f7bd4b1d
ms.sourcegitcommit: 8699383914c24a0df033393f55db3369db728a7b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/15/2019
ms.locfileid: "65632037"
---
# <a name="isosdacinterfacegetmoduledata-method"></a>ISOSDacInterface::GetModuleData 方法

获取对应于在给定地址加载该模块的数据。

[!INCLUDE[debugging-api-recommended-note](../../../../includes/debugging-api-recommended-note.md)]

## <a name="syntax"></a>语法

```
HRESULT GetModuleData(
    CLRDATA_ADDRESS moduleAddr,
    DacpModuleData *data
);
```

## <a name="parameters"></a>参数

`moduleAddr`\
[in]要检索其信息的模块的地址。

`data`\
[out][DacpModuleData 结构](dacpmoduledata-structure.md)来保存已加载模块的信息。

## <a name="remarks"></a>备注

提供的方法属于`ISOSDacInterface`接口，并对应于虚拟方法表 13 槽。

## <a name="requirements"></a>要求

**平台：** 请参阅[系统需求](../../../../docs/framework/get-started/system-requirements.md)。  
**标头：** None  
**库：** None  
**.NET Framework 版本：**[!INCLUDE[net_current_v47plus](../../../../includes/net-current-v47plus.md)]  

## <a name="see-also"></a>请参阅

- [调试](index.md)
- [ISOSDacInterface 接口](isosdacinterface-interface.md)
