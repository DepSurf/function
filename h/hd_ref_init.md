# Function: <code>hd_ref_init</code>

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
In block/genhd.c (ffffffff813cb5e9)
Location: include/linux/genhd.h:656
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813cd76c)
Location: include/linux/genhd.h:656
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff8140f8a9)
Location: include/linux/genhd.h:645
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81411ace)
Location: include/linux/genhd.h:645
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff8142ac39)
Location: include/linux/genhd.h:636
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff8142ce5d)
Location: include/linux/genhd.h:636
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff81438e58)
Location: include/linux/genhd.h:630
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff8143a240)
Location: include/linux/genhd.h:630
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff81464e35)
Location: include/linux/genhd.h:639
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81466258)
Location: include/linux/genhd.h:639
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814987ae)
Location: include/linux/genhd.h:648
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81499aec)
Location: include/linux/genhd.h:648
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814b28fe)
Location: include/linux/genhd.h:671
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814b3dd9)
Location: include/linux/genhd.h:671
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814e0d96)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814e22e6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814fa1c6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814fb6a6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hd_ref_init(struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155d626)
Location: block/partitions/core.c:302
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
Direct callers:
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff8155d7f0-ffffffff8155d81d: hd_ref_init (STB_GLOBAL)
```
</details>
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
In block/genhd.c (ffff8000105fbd00)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffff8000105fd678)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (c07a6dd4)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (c07a854c)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (c0000000007950bc)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (c000000000796f44)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffe000437d72)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffe000439226)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814f27a6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814f3c86)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814e2cd6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814e4196)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff814ee836)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814efd16)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/genhd.c (ffffffff815078d6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81508da6)
Location: include/linux/genhd.h:679
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
