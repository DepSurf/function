# Function: <code>compat_blkdev_driver_ioctl</code>

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
In block/compat_ioctl.c (ffffffff813e6096)
Location: block/compat_ioctl.c:524
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
In block/compat_ioctl.c (ffffffff8142c340)
Location: block/compat_ioctl.c:524
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
In block/compat_ioctl.c (ffffffff81446140)
Location: block/compat_ioctl.c:524
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
In block/compat_ioctl.c (ffffffff8145478c)
Location: block/compat_ioctl.c:208
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
In block/compat_ioctl.c (ffffffff8148041f)
Location: block/compat_ioctl.c:209
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
In block/compat_ioctl.c (ffffffff814b4f7c)
Location: block/compat_ioctl.c:209
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
In block/compat_ioctl.c (ffffffff814c883c)
Location: block/compat_ioctl.c:209
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_blkdev_driver_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffffffff814f6fc0)
Location: block/compat_ioctl.c:209
Inline: False
Direct callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814f6fc0-ffffffff814f7345: compat_blkdev_driver_ioctl (STB_LOCAL)
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
In block/compat_ioctl.c (ffffffff815150ad)
Location: block/compat_ioctl.c:210
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
int compat_blkdev_driver_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (ffff80001061b840)
Location: block/compat_ioctl.c:210
Inline: False
Direct callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffff80001061b840-ffff80001061c034: compat_blkdev_driver_ioctl (STB_LOCAL)
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
int compat_blkdev_driver_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/compat_ioctl.c (c0000000007ba240)
Location: block/compat_ioctl.c:210
Inline: False
Direct callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
c0000000007ba240-c0000000007ba84c: compat_blkdev_driver_ioctl (STB_LOCAL)
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
In block/compat_ioctl.c (ffffffff8150d68d)
Location: block/compat_ioctl.c:210
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
In block/compat_ioctl.c (ffffffff814fdabd)
Location: block/compat_ioctl.c:210
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
In block/compat_ioctl.c (ffffffff8150971d)
Location: block/compat_ioctl.c:210
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
In block/compat_ioctl.c (ffffffff81522d8d)
Location: block/compat_ioctl.c:210
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
