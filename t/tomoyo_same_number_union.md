# Function: <code>tomoyo_same_number_union</code>

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
In security/tomoyo/file.c (ffffffff8136eae1)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff81371946)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff813a4fc9)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff813a7d66)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff813bbb49)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff813be8f6)
Location: security/tomoyo/common.h:1243
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff813d2449)
Location: security/tomoyo/common.h:1269
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff813d51f5)
Location: security/tomoyo/common.h:1269
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff813f8959)
Location: security/tomoyo/common.h:1271
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff813fb705)
Location: security/tomoyo/common.h:1271
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81429949)
Location: security/tomoyo/common.h:1244
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff8142c675)
Location: security/tomoyo/common.h:1244
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81446209)
Location: security/tomoyo/common.h:1262
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff81448fc5)
Location: security/tomoyo/common.h:1262
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81473e29)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff81476c15)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff8148dbc9)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff814909b5)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff814e4e49)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff814e7d35)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81502249)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff815050b5)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81508e19)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff8150bc35)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81566109)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff8156957b)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool tomoyo_same_number_union(const struct tomoyo_number_union *a, const struct tomoyo_number_union *b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816019bd)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
Direct callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff81605382)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
**Symbols:**

```
ffffffff816015f0-ffffffff81601633: tomoyo_same_number_union (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool tomoyo_same_number_union(const struct tomoyo_number_union *a, const struct tomoyo_number_union *b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b2a1d)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
Direct callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff816b6712)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
**Symbols:**

```
ffffffff816b25b0-ffffffff816b25f3: tomoyo_same_number_union (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool tomoyo_same_number_union(const struct tomoyo_number_union *a, const struct tomoyo_number_union *b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816eb42d)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
Direct callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff816ef0f2)
Location: security/tomoyo/common.h:1246
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
**Symbols:**

```
ffffffff816eafa0-ffffffff816eafe3: tomoyo_same_number_union (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool tomoyo_same_number_union(const struct tomoyo_number_union *a, const struct tomoyo_number_union *b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff817281fd)
Location: security/tomoyo/common.h:1244
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
Direct callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff8172bec2)
Location: security/tomoyo/common.h:1244
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
**Symbols:**

```
ffffffff81727d70-ffffffff81727db3: tomoyo_same_number_union (STB_LOCAL)
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
In security/tomoyo/file.c (ffff8000105812dc)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffff800010584ce8)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (c07335c8)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (c07366e0)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (c0000000006ef750)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (c0000000006f40e0)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffe0003d1b5c)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffe0003d4b58)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff814861a9)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff81488f95)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81476bc9)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff814799b5)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81482249)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff81485035)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
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
In security/tomoyo/file.c (ffffffff81499dd9)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
```
```
In security/tomoyo/network.c (ffffffff8149cb75)
Location: security/tomoyo/common.h:1247
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_inet_acl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
