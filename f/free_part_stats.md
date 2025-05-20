# Function: <code>free_part_stats</code>

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
In block/genhd.c (ffffffff813cac89)
Location: include/linux/genhd.h:352
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813ccf2e)
Location: include/linux/genhd.h:352
Inline: True
Inline callers:
  - block/partition-generic.c:part_release
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff8140f8d5)
Location: include/linux/genhd.h:336
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81411b75)
Location: include/linux/genhd.h:336
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff8142ac65)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8142cf04)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff81438eb9)
Location: include/linux/genhd.h:321
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8143a1e1)
Location: include/linux/genhd.h:321
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff81464e96)
Location: include/linux/genhd.h:325
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814661f9)
Location: include/linux/genhd.h:325
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814987ec)
Location: include/linux/genhd.h:326
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81499bb9)
Location: include/linux/genhd.h:326
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814b293c)
Location: include/linux/genhd.h:331
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814b3ea7)
Location: include/linux/genhd.h:331
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814e0dda)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e23b6)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814fa20a)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814fb776)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/genhd.c (ffff8000105fbd68)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffff8000105fd6d0)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (c07a6e20)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c07a85a4)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (c000000000795120)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c00000000079705c)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffe000437dd6)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffe000439288)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814f27ea)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814f3d56)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814e2d1a)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e4266)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff814ee87a)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814efde6)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff8150791a)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81508e76)
Location: include/linux/genhd.h:338
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
```
</details>
</li>
</ul>

## Differences
