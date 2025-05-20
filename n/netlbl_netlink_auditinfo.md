# Function: <code>netlbl_netlink_auditinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d4da)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e66a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818102ae)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f8da)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818820a9)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188297e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188368e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff818b418a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6959)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b722e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7f2e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff818dab3a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd22a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddafe)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de80e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff8196071a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81962e1a)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819636ee)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196441e)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9efd)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc669)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcf45)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdcc5)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819f11cd)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f38b9)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4185)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4e65)
Location: net/netlabel/netlabel_user.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a6047d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62ce9)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a635f5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64325)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a970ad)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a998c9)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a1a5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9aea5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92edd)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95103)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b955d5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b966a5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2b2d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4d63)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5225)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6315)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91c4e)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93e8c)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9437d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9549d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e56e)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c6062c)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60b1d)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61c9d)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81e0073e)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02ab0)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03056)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e042d6)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd555e)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd79b0)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7fb6)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd92b6)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff820511fe)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820536a0)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ca6)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054f86)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff821239b8)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125ea5)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126489)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127869)
Location: net/netlabel/netlabel_user.h:33
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffff800010d6667c)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d691cc)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69df0)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ab00)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (c0e65ce4)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c0e678b0)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68354)
Location: net/netlabel/netlabel_user.h:34
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e69064)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (c000000000ea2848)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea5ff4)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6bfc)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7f00)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a136)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c332)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089ca76)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d58a)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3643d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38c59)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39535)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a235)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819f305d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f5879)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f6155)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6e55)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa22ed)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4b09)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa53e5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa60e5)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae65d)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0e79)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1785)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2485)
Location: net/netlabel/netlabel_user.h:34
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
</ul>

## Differences
