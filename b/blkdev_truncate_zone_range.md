# Function: <code>blkdev_truncate_zone_range</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (ffffffff81595220)
Location: block/blk-zoned.c:321
Inline: True
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81595220-ffffffff81595266: blkdev_truncate_zone_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (ffffffff8159bfd0)
Location: block/blk-zoned.c:313
Inline: True
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff8159bfd0-ffffffff8159c016: blkdev_truncate_zone_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604d1b)
Location: block/blk-zoned.c:382
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b8503)
Location: block/blk-zoned.c:375
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817789d3)
Location: block/blk-zoned.c:370
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b8597)
Location: block/blk-zoned.c:359
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817fd07e)
Location: block/blk-zoned.c:359
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
