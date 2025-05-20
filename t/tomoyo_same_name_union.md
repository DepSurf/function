# Function: <code>tomoyo_same_name_union</code>

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
In security/tomoyo/file.c (ffffffff8136ea65)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_path_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
```
```
In security/tomoyo/network.c (ffffffff81371876)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff813a4f85)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff813a7c96)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff813bbb05)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff813be826)
Location: security/tomoyo/common.h:1229
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff813d2405)
Location: security/tomoyo/common.h:1255
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff813d5126)
Location: security/tomoyo/common.h:1255
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff813f8915)
Location: security/tomoyo/common.h:1257
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff813fb636)
Location: security/tomoyo/common.h:1257
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81429905)
Location: security/tomoyo/common.h:1230
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff8142c5a6)
Location: security/tomoyo/common.h:1230
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff814461c5)
Location: security/tomoyo/common.h:1248
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81448ef6)
Location: security/tomoyo/common.h:1248
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81473de5)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81476b46)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff8148db85)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff814908e6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff814e4e05)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff814e7c66)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81502205)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81504fe6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81508dd5)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff8150bb66)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff815660c5)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff815693d6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff816017d5)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81605172)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff816b2805)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff816b64b2)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff816eb1f5)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff816eeeb2)
Location: security/tomoyo/common.h:1232
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81727fc5)
Location: security/tomoyo/common.h:1230
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff8172bc82)
Location: security/tomoyo/common.h:1230
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffff80001058126c)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffff800010584b5c)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (c0733560)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (c07365d4)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (c0000000006ef6d8)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (c0000000006f3fa0)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffe0003d1b12)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffe0003d4a3c)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81486165)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81488ec6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81476b85)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff814798e6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81482205)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff81484f66)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
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
In security/tomoyo/file.c (ffffffff81499d95)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_mount_acl
  - security/tomoyo/file.c:tomoyo_same_path_number_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_path2_acl
  - security/tomoyo/file.c:tomoyo_same_mkdev_acl
  - security/tomoyo/file.c:tomoyo_same_path_acl
```
```
In security/tomoyo/network.c (ffffffff8149caa6)
Location: security/tomoyo/common.h:1233
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_same_unix_acl
```
</details>
</li>
</ul>

## Differences
