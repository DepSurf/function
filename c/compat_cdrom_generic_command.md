# Function: <code>compat_cdrom_generic_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff813e60e3)
Location: block/compat_ioctl.c:147
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff8142c38d)
Location: block/compat_ioctl.c:147
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff8144618d)
Location: block/compat_ioctl.c:147
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff81454cc4)
Location: block/compat_ioctl.c:143
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff8148095a)
Location: block/compat_ioctl.c:144
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff814b547d)
Location: block/compat_ioctl.c:144
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff814c8d3a)
Location: block/compat_ioctl.c:144
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff814f7160)
Location: block/compat_ioctl.c:144
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff81515560)
Location: block/compat_ioctl.c:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_cdrom_generic_command(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffff80001061ad58)
Location: block/compat_ioctl.c:145
Inline: False
Direct callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
**Symbols:**

```
ffff80001061ad58-ffff80001061b840: compat_cdrom_generic_command (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_cdrom_generic_command(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (c0000000007b9c40)
Location: block/compat_ioctl.c:145
Inline: False
Direct callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
**Symbols:**

```
c0000000007b9c40-c0000000007ba238: compat_cdrom_generic_command (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In block/compat_ioctl.c (ffffffff8150db40)
Location: block/compat_ioctl.c:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/compat_ioctl.c (ffffffff814fdf70)
Location: block/compat_ioctl.c:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/compat_ioctl.c (ffffffff81509bd0)
Location: block/compat_ioctl.c:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/compat_ioctl.c (ffffffff81523240)
Location: block/compat_ioctl.c:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
