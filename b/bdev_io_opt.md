# Function: <code>bdev_io_opt</code>

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
In block/ioctl.c (ffffffff813c918d)
Location: include/linux/blkdev.h:1230
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1230
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
In block/ioctl.c (ffffffff8140d3ed)
Location: include/linux/blkdev.h:1259
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1259
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
In block/ioctl.c (ffffffff81428b2d)
Location: include/linux/blkdev.h:1424
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1424
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
In block/ioctl.c (ffffffff81437077)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1462
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
In block/ioctl.c (ffffffff81462e34)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81480805)
Location: include/linux/blkdev.h:1477
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
In block/ioctl.c (ffffffff8149646a)
Location: include/linux/blkdev.h:1517
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814b5248)
Location: include/linux/blkdev.h:1517
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
In block/ioctl.c (ffffffff814b06cc)
Location: include/linux/blkdev.h:1296
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814c8b05)
Location: include/linux/blkdev.h:1296
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
In block/ioctl.c (ffffffff814de1f1)
Location: include/linux/blkdev.h:1310
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814f7796)
Location: include/linux/blkdev.h:1310
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
In block/ioctl.c (ffffffff814f7641)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff815154e6)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffff815583f8)
Location: include/linux/blkdev.h:1371
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
In block/ioctl.c (ffffffff81574983)
Location: include/linux/blkdev.h:1472
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
In block/ioctl.c (ffffffff8157ca00)
Location: include/linux/blkdev.h:1457
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
In block/ioctl.c (ffffffff815e1d5f)
Location: include/linux/blkdev.h:1432
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
In block/ioctl.c (ffffffff816906ea)
Location: include/linux/blkdev.h:1254
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
In block/ioctl.c (ffffffff8174f2c3)
Location: include/linux/blkdev.h:1202
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff8178b76c)
Location: include/linux/blkdev.h:1183
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d36e)
Location: include/linux/blkdev.h:1183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
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
In block/ioctl.c (ffffffff817cdec9)
Location: include/linux/blkdev.h:1168
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81e24592)
Location: include/linux/blkdev.h:1168
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
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
In block/ioctl.c (ffff8000105f8d28)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffff80001061c400)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (c07a406c)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (c0000000007910d0)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (c0000000007bad2c)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffe000435766)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffff814efc21)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8150dac6)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffff814e0161)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814fdef6)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffff814ebcb1)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81509b56)
Location: include/linux/blkdev.h:1337
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
In block/ioctl.c (ffffffff81504cc1)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff815231c6)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
