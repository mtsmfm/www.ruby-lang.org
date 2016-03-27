---
layout: news_post
title: "루비 2.0.0과 루비 2.1 지원 계획"
author: "usa"
translator: "Sunki Baek"
date: 2016-02-24 09:00:00 +0000
lang: ko
---

루비 2.0.0과 루비 2.1 지원 계획을 알려드립니다.

## 루비 2.0.0에 대해

앞서 발표된 것처럼 루비 2.0.0에 대한 지원은 오늘로 종료됩니다. 가장 최신 버전의 버그 및 보안 패치는
더 이상 2.0.0 버전으로 백포트 되지 않을 것이며 패치 릴리스도 더 이상 없을 것입니다.

루비 2.3 혹은 2.2 버전으로 가능하면 빨리 업그레이드하실 것을 강력히 권장합니다.

혹시라도 업그레이드할 수 없는 어쩔 수 없는 사유가 있어서 2.0.0 버전의 릴리스 유지를 원하시면
ruby-core 메일링 리스트로 저희에게 연락 주시기 바랍니다.

## 루비 2.1에 대해

루비 2.1.9의 릴리스는 3월 말까지 하는 것으로 계획하고 있습니다. 이후에는 2.1 버전의 통상적인
유지보수 단계는 끝나게 되며 보안 유지보수 단계가 시작됩니다.
다시 말하면 2.1.9 버전 이후에는 버그 픽스에 대한 백포트는 없을 것이며 보안 패치만 이루어지게 되는
것입니다.

루비 2.3 혹은 2.2 버전으로 업그레이드하는 계획을 세우실 것을 권장합니다.

그런데 루비 2.1.9 릴리스 바로 다음에는 루비 2.1.10 버전이 릴리스 될 예정입니다. 이 버전은
버그 픽스도 아니고 보안 패치도 아닙니다. 지금까지 루비에서는 두 자릿수 버전 넘버를 사용해본 적이
없었습니다. 따라서 두 자릿수 버전 넘버를 중요한 보안 패치 내용 없이 테스트하는 것이 중요하다고
생각했습니다.

루비 2.1.10과 2.1.9는 버전 넘버 이외에 모든 것이 동일할 것입니다. 실제 서버에서 사용하실 필요는
없습니다만 향후 보안 패치를 담게될 2.1.11 버전 이전에 2.1.10 버전을 테스트 해볼 것을 권장합니다.