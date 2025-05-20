# Function: <code>tomoyo_put_group</code>

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
In security/tomoyo/file.c (ffffffff8136edfd)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_write_file
```
```
In security/tomoyo/gc.c (ffffffff8136ff4f)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81370b47)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81372167)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff813a6214)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813a631f)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813a6f37)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff813a858d)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff813bcd94)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813bce9f)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813bdab7)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff813bf11d)
Location: security/tomoyo/common.h:1192
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff813d37a0)
Location: security/tomoyo/common.h:1194
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813d38b7)
Location: security/tomoyo/common.h:1194
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813d43a7)
Location: security/tomoyo/common.h:1194
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff813d5a0f)
Location: security/tomoyo/common.h:1194
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff813f9cb0)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813f9d35)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813fa8b7)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff813fbf1f)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff8142ac69)
Location: security/tomoyo/common.h:1193
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8142acd5)
Location: security/tomoyo/common.h:1193
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8142b857)
Location: security/tomoyo/common.h:1193
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff8142ce7e)
Location: security/tomoyo/common.h:1193
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81447539)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81447610)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81448177)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff814497ce)
Location: security/tomoyo/common.h:1196
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81475137)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81475226)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81475db7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81477431)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff8148eed7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8148efc6)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8148fb57)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff814911d1)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff814e6177)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff814e6462)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff814e6e77)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff814e85a1)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81503577)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81503862)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81504287)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81505921)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff8150a149)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1207
Inline: False
```
```
In security/tomoyo/group.c (ffffffff8150ae07)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff8150c461)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81567754)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1207
Inline: False
```
```
In security/tomoyo/group.c (ffffffff815685a7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81569f39)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff816032fe)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1206
Inline: False
```
```
In security/tomoyo/group.c (ffffffff81604217)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81605dc9)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff816b448e)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1206
Inline: False
```
```
In security/tomoyo/group.c (ffffffff816b5447)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff816b71d9)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff816ece4e)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1206
Inline: False
```
```
In security/tomoyo/group.c (ffffffff816ede27)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff816efbb9)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81729c1e)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (0)
Location: security/tomoyo/common.h:1204
Inline: False
```
```
In security/tomoyo/group.c (ffffffff8172abf7)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff8172c989)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffff800010582838)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffff800010582ad4)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffff800010583b64)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffff800010585714)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (c0734660)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (c0734ab8)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (c0735728)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (c07370e8)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (c0000000006f1120)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (c0000000006f143c)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (c0000000006f2804)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (c0000000006f4fa4)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffe0003d2c08)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (ffffffe0003d2e12)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffe0003d3d66)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffe0003d5362)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff814874b7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff814875a6)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81488137)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff814897b1)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81477ed7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81477fc6)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81478b57)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff8147a1d1)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff81483557)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81483646)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff814841d7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff81485851)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
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
In security/tomoyo/file.c (ffffffff8149b0e7)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8149b1d6)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8149bd17)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/network.c (ffffffff8149d391)
Location: security/tomoyo/common.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
</details>
</li>
</ul>

## Differences
