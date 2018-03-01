---
title: "런타임 오류: 어셈블리 mscorlib.dll 없거나 로드할 수 없습니다"
ms.topic: article
ms.prod: xamarin
ms.assetid: 1027E16C-2C14-4BB5-AAAB-342F3E28E22E
ms.technology: xamarin-ios
author: bradumbaugh
ms.author: brumbaug
ms.openlocfilehash: fd5ba59841142306df7c65e97e0f16ff5654d5b2
ms.sourcegitcommit: 6cd40d190abe38edd50fc74331be15324a845a28
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/27/2018
---
# <a name="runtime-error-the-assembly-mscorlibdll-was-not-found-or-could-not-be-loaded"></a>런타임 오류: 어셈블리 mscorlib.dll 없거나 로드할 수 없습니다

```
<Warning>: The assembly mscorlib.dll was not found or could not be loaded.
<Warning>: It should have been installed in the `/Developer/MonoTouch/Source/monotouch/builds/install/target64/lib/mono/2.0/mscorlib.dll' directory.
<Warning>: Service exited with abnormal code: 1
```

이 문제는 발생 때는 *숨겨진* `.monotouch-32` 및 `.monotouch-64` 에서 누락 된 폴더는 `.xcarchive` 서명에 / IPA 만들기, 런타임 오류를 발생 시키는 합니다.

