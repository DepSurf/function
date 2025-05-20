# Function: <code>bdev_io_min</code>

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
In block/ioctl.c (ffffffff813c96c3)
Location: include/linux/blkdev.h:1220
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1220
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
In block/ioctl.c (ffffffff8140d8b2)
Location: include/linux/blkdev.h:1249
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1249
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
In block/ioctl.c (ffffffff81428771)
Location: include/linux/blkdev.h:1414
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1414
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
In block/ioctl.c (ffffffff81436ab9)
Location: include/linux/blkdev.h:1452
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1452
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
In block/ioctl.c (ffffffff8146284c)
Location: include/linux/blkdev.h:1467
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81480514)
Location: include/linux/blkdev.h:1467
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
In block/ioctl.c (ffffffff814961e4)
Location: include/linux/blkdev.h:1507
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814b5081)
Location: include/linux/blkdev.h:1507
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
In block/ioctl.c (ffffffff814b03af)
Location: include/linux/blkdev.h:1286
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814c8941)
Location: include/linux/blkdev.h:1286
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
In block/ioctl.c (ffffffff814deaf2)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814f77cc)
Location: include/linux/blkdev.h:1300
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
In block/ioctl.c (ffffffff814f7f31)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81515493)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffff81557e4d)
Location: include/linux/blkdev.h:1361
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
In block/ioctl.c (ffffffff815746d6)
Location: include/linux/blkdev.h:1462
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
In block/ioctl.c (ffffffff8157c756)
Location: include/linux/blkdev.h:1447
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
In block/ioctl.c (ffffffff815e1f16)
Location: include/linux/blkdev.h:1422
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
In block/ioctl.c (ffffffff81690d0b)
Location: include/linux/blkdev.h:1244
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
In block/ioctl.c (ffffffff8174f8f3)
Location: include/linux/blkdev.h:1192
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
In block/ioctl.c (ffffffff8178bbb0)
Location: include/linux/blkdev.h:1173
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
In block/ioctl.c (ffffffff817ce334)
Location: include/linux/blkdev.h:1158
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
In block/ioctl.c (ffff8000105f8d90)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffff80001061c3e8)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (c07a4088)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (c000000000791080)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (c0000000007bad50)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffe0004357be)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffff814f0511)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8150da73)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffff814e0a51)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814fdea3)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffff814ec5a1)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81509b03)
Location: include/linux/blkdev.h:1327
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
In block/ioctl.c (ffffffff815055b1)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81523173)
Location: include/linux/blkdev.h:1327
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
