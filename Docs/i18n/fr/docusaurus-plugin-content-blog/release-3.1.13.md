---
slug: release-3-1-13
date: 2023-03-31
title: Version 3.1.13
authors: [momo]
tags: [release]
draft: false
---

:::warning Traduction incomplète !
:::

### Résumé

Fixes compatibility with Avatars 3.0 Manager.

<!--truncate-->

### Bug Fixes

* Reverts name of 'hasInitialized' field in VRC_AvatarParameterDriver to 'initialized' to avoid breaking any existing packages which expect this field name.