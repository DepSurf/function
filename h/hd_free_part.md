# Function: <code>hd_free_part</code>

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
Location: include/linux/genhd.h:684
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813ccf25)
Location: include/linux/genhd.h:684
Inline: True
Inline callers:
  - block/partition-generic.c:part_release
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
Location: include/linux/genhd.h:673
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814112b5)
Location: include/linux/genhd.h:673
Inline: True
Inline callers:
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
Location: include/linux/genhd.h:664
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8142c655)
Location: include/linux/genhd.h:664
Inline: True
Inline callers:
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
Location: include/linux/genhd.h:658
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814399a5)
Location: include/linux/genhd.h:658
Inline: True
Inline callers:
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
Location: include/linux/genhd.h:667
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814659a5)
Location: include/linux/genhd.h:667
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff8149880c)
Location: include/linux/genhd.h:676
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814993ee)
Location: include/linux/genhd.h:676
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814b295c)
Location: include/linux/genhd.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814b362e)
Location: include/linux/genhd.h:699
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814e0dfe)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e1bbe)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814fa22e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814faf6e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/partition-generic.c:part_release
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
In block/genhd.c (ffffffff8155b0c3)
Location: block/blk.h:377
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partitions/core.c (ffffffff8155cd8e)
Location: block/blk.h:377
Inline: True
Inline callers:
  - block/partitions/core.c:part_release
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
In block/genhd.c (ffff8000105fbd90)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffff8000105fcec4)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (c07a6e3c)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c07a77a4)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (c00000000079515c)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (c000000000796508)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffe000437df0)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffe000438b64)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814f280e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814f354e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814e2d3e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814e3a5e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff814ee89e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff814ef5de)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
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
In block/genhd.c (ffffffff8150793e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
```
```
In block/partition-generic.c (ffffffff8150866e)
Location: include/linux/genhd.h:707
Inline: True
Inline callers:
  - block/partition-generic.c:part_release
```
</details>
</li>
</ul>

## Differences
