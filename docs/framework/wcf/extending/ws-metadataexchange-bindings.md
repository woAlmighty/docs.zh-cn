---
title: WS-MetadataExchange 绑定
ms.date: 03/30/2017
ms.assetid: 10f8de5d-b81d-4ea7-b37e-7f2c00c39714
ms.openlocfilehash: 03e6e6d5ee7e69b397acd0f51b8037f02c1804ec
ms.sourcegitcommit: 9b552addadfb57fab0b9e7852ed4f1f1b8a42f8e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "61795468"
---
# <a name="ws-metadataexchange-bindings"></a>WS-MetadataExchange 绑定
本主题说明如何为各种传输构造默认的元数据交换绑定。  
  
## <a name="the-default-bindings"></a>默认绑定  
  
|默认绑定名称|绑定的构造方式|  
|--------------------------|------------------------------------|  
|mexHttpBinding|一个禁用传输级安全性的 <xref:System.ServiceModel.WSHttpBinding>。|  
|mexHttpsBinding|一个支持传输级安全性的 <xref:System.ServiceModel.WSHttpBinding>。|  
|mexNamedPipeBinding|一个 <xref:System.ServiceModel.Channels.CustomBinding>，它具有使用默认值的 <xref:System.ServiceModel.Channels.NamedPipeTransportBindingElement>。|  
|mexTcpBinding|一个 <xref:System.ServiceModel.Channels.CustomBinding>，它具有使用默认值的 <xref:System.ServiceModel.Channels.TcpTransportBindingElement>。|
