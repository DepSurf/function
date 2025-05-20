# Function: <code>bdev_physical_block_size</code>

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
In block/ioctl.c (ffffffff813c938f)
Location: include/linux/blkdev.h:1210
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1210
Inline: True
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
In block/ioctl.c (ffffffff8140d57d)
Location: include/linux/blkdev.h:1239
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1239
Inline: True
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
In block/ioctl.c (ffffffff81428bcd)
Location: include/linux/blkdev.h:1404
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1404
Inline: True
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
In block/ioctl.c (ffffffff81436d90)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1442
Inline: True
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
In block/ioctl.c (ffffffff81462b35)
Location: include/linux/blkdev.h:1457
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814806f4)
Location: include/linux/blkdev.h:1457
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff8149648a)
Location: include/linux/blkdev.h:1497
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814b5264)
Location: include/linux/blkdev.h:1497
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff814b03e6)
Location: include/linux/blkdev.h:1276
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814c8b21)
Location: include/linux/blkdev.h:1276
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff814de1a4)
Location: include/linux/blkdev.h:1290
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814f77b1)
Location: include/linux/blkdev.h:1290
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff814f75f4)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff815154af)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff81557df1)
Location: include/linux/blkdev.h:1351
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff815743f1)
Location: include/linux/blkdev.h:1452
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff8157c481)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff815e1dd1)
Location: include/linux/blkdev.h:1412
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff81690b7b)
Location: include/linux/blkdev.h:1234
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff8174f75d)
Location: include/linux/blkdev.h:1182
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff8178b713)
Location: include/linux/blkdev.h:1163
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff817cde73)
Location: include/linux/blkdev.h:1148
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffff8000105f8d58)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffff80001061c360)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (c07a4024)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (c000000000791030)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (c0000000007bacd8)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffe000435790)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff814efbd4)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8150da8f)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff814e0114)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814fdebf)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff814ebc64)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81509b1f)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/ioctl.c (ffffffff81504c74)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8152318f)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
