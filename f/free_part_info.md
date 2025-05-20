# Function: <code>free_part_info</code>

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
In block/genhd.c (ffffffff813cac95)
Location: include/linux/genhd.h:423
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813ccf3a)
Location: include/linux/genhd.h:423
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
In block/genhd.c (ffffffff8140f8e1)
Location: include/linux/genhd.h:407
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81411b61)
Location: include/linux/genhd.h:407
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
In block/genhd.c (ffffffff8142ac71)
Location: include/linux/genhd.h:398
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8142cef0)
Location: include/linux/genhd.h:398
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
In block/genhd.c (ffffffff81438ec5)
Location: include/linux/genhd.h:392
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8143a1cd)
Location: include/linux/genhd.h:392
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
In block/genhd.c (ffffffff81464ea2)
Location: include/linux/genhd.h:384
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814661e5)
Location: include/linux/genhd.h:384
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
In block/genhd.c (ffffffff81498818)
Location: include/linux/genhd.h:387
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81499bad)
Location: include/linux/genhd.h:387
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
In block/genhd.c (ffffffff814b2968)
Location: include/linux/genhd.h:410
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814b3e9b)
Location: include/linux/genhd.h:410
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
In block/genhd.c (ffffffff814e0e0b)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e23aa)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffff814fa23b)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814fb76a)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffff8000105fbd98)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffff8000105fd6c8)
Location: include/linux/genhd.h:417
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
In block/genhd.c (c07a6e44)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c07a8598)
Location: include/linux/genhd.h:417
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
In block/genhd.c (c000000000795168)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c000000000797050)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffe000437dfc)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffe0004392e2)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffff814f281b)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814f3d4a)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffff814e2d4b)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e425a)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffff814ee8ab)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814efdda)
Location: include/linux/genhd.h:417
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
In block/genhd.c (ffffffff8150794b)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff81508e6a)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
```
</details>
</li>
</ul>

## Differences
