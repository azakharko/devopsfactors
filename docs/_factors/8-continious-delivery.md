---
title: "Continious Delivery"
number: 8
anchor: continious-delivery
anti_pattern:
    - "Ручная выкатка на окружение по чек-листу"
---

CD - это процесс, описывающий последовательность действий для доставки артефакта. Основной концепт состоит в унификации этого процесса для всех окружений. Существуют разные стратегии доставки: blue/green, canary, и другие. В большинстве случаев будет справедливым утверждение, что чем мельче доставляемые изменения, тем меньше вероятность поломать работающий продукт. Доставка ценности должна быть всегда в рабочем состоянии и по первому требованию бизнеса доставлять ценность клиентам.
Следующим этапом развития *Continious Delivery* является *Continious Deployment*. 