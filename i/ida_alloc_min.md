# Function: <code>ida_alloc_min</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2c56)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff818a80b0)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff812efdf0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff818f30b0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff813018c0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff81925010)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff8133ad30)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff819f97cb)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff81346980)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff819f900b)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff8134cc10)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff819de000)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff8139ab10)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff81a8e8d2)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff8141dad8)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff81c047f2)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff814aa3c8)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In drivers/char/virtio_console.c (ffffffff81a97185)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_port_console
```
```
In net/core/net_namespace.c (ffffffff81db3d12)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff814df0e8)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In drivers/char/virtio_console.c (ffffffff81ae2995)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_port_console
```
```
In net/core/net_namespace.c (ffffffff81e243c2)
Location: include/linux/idr.h:289
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff81511ed8)
Location: include/linux/idr.h:291
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In drivers/char/virtio_console.c (ffffffff81b35d85)
Location: include/linux/idr.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_port_console
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87cb4)
Location: include/linux/idr.h:291
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
```
```
In net/core/net_namespace.c (ffffffff81ee25d2)
Location: include/linux/idr.h:291
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffff8000103b3f78)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffff800010bc0b0c)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (c0592e6c)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (c0cdce00)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (c0000000004afdd0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (c000000000c9ae48)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffe000277766)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffe00074e9ea)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff812f9ea0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff818c5010)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff812eaac0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff8187ef50)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff812f7c90)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff81916010)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In fs/namespace.c (ffffffff81308fd0)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
```
In net/core/net_namespace.c (ffffffff81937210)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
```
</details>
</li>
</ul>

## Differences
