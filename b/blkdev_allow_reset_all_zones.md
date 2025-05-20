# Function: <code>blkdev_allow_reset_all_zones</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8151818e)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815788a8)
Location: block/blk-zoned.c:172
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815953c0)
Location: block/blk-zoned.c:172
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c15f)
Location: block/blk-zoned.c:164
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f848)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7388)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007beff4)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe00045225a)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8151076e)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500a8e)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c7fe)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81525ede)
Location: block/blk-zoned.c:224
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
</details>
</li>
</ul>

## Differences
