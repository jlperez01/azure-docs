---
title: List, update, and delete image resources using PowerShell
description: List, update, and delete image resources within your shared image gallery using Azure PowerShell.
author: cynthn
ms.service: virtual-machines
ms.subservice: shared-image-gallery
ms.workload: infrastructure-services
ms.topic: how-to
ms.date: 04/27/2020
ms.author: cynthn
ms.reviewer: akjosh

---

# List, update, and delete image resources using PowerShell 

**Applies to:** :heavy_check_mark: Linux VMs :heavy_check_mark: Windows VMs :heavy_check_mark: Flexible scale sets :heavy_check_mark: Uniform scale sets

You can manage your shared image gallery resources using Azure PowerShell.

[!INCLUDE [virtual-machines-common-gallery-list-ps.md](../../includes/virtual-machines-common-gallery-list-ps.md)]

[!INCLUDE [virtual-machines-common-shared-images-update-delete-ps](../../includes/virtual-machines-common-shared-images-update-delete-ps.md)]

## Next steps

[Azure Image Builder (preview)](./image-builder-overview.md) can help automate image version creation, you can even use it to update and [create a new image version from an existing image version](./linux/image-builder-gallery-update-image-version.md).