# Function: <code>blkdev_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff813c8f20)
Location: block/ioctl.c:496
Inline: False
Direct callers:
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:ioctl_by_bdev
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff813c8f20-ffffffff813c9809: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8140d180)
Location: block/ioctl.c:496
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff8140d180-ffffffff8140da8d: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814284a0)
Location: block/ioctl.c:505
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814284a0-ffffffff81428e12: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814367f0)
Location: block/ioctl.c:505
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814367f0-ffffffff8143712b: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81462580)
Location: block/ioctl.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff81462580-ffffffff81462ee8: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81495eb0)
Location: block/ioctl.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff81495eb0-ffffffff81496821: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814afd60)
Location: block/ioctl.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814afd60-ffffffff814b0744: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814de130)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814de130-ffffffff814deb68: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814f7580)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814f7580-ffffffff814f7fa7: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815585c0)
Location: block/ioctl.c:577
Inline: False
Direct callers:
  - fs/block_dev.c:block_ioctl
```
**Symbols:**

```
ffffffff815585c0-ffffffff8155880b: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81574bb0)
Location: block/ioctl.c:536
Inline: False
Direct callers:
  - fs/block_dev.c:block_ioctl
```
**Symbols:**

```
ffffffff81574bb0-ffffffff81574e07: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8157cc40)
Location: block/ioctl.c:538
Inline: False
Direct callers:
  - fs/block_dev.c:block_ioctl
```
**Symbols:**

```
ffffffff8157cc40-ffffffff8157ce97: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:553
Inline: False
Direct callers:
  - block/fops.c:block_ioctl
```
**Symbols:**

```
ffffffff81cd8858-ffffffff81cd8878: blkdev_ioctl.cold (STB_LOCAL)
ffffffff815e2230-ffffffff815e2493: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int blkdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:558
Inline: False
```
**Symbols:**

```
ffffffff81e8c2f0-ffffffff81e8c310: blkdev_ioctl.cold (STB_LOCAL)
ffffffff81690e50-ffffffff816910df: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int blkdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:560
Inline: False
```
**Symbols:**

```
ffffffff820768b0-ffffffff820768d0: blkdev_ioctl.cold (STB_LOCAL)
ffffffff8174fa40-ffffffff8174fce1: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int blkdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:576
Inline: False
```
**Symbols:**

```
ffffffff820f6733-ffffffff820f6753: blkdev_ioctl.cold (STB_LOCAL)
ffffffff8178bce0-ffffffff8178bf62: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int blkdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:587
Inline: False
```
**Symbols:**

```
ffffffff821d3c6c-ffffffff821d3c8c: blkdev_ioctl.cold (STB_LOCAL)
ffffffff817ce480-ffffffff817ce702: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffff8000105f83c0)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
```
**Symbols:**

```
ffff8000105f83c0-ffff8000105f90bc: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c07a36c0)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
```
**Symbols:**

```
c07a36c0-c07a4438: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c0000000007907f0)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
```
**Symbols:**

```
c0000000007907f0-c0000000007916c0: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffe0004351fa)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
```
**Symbols:**

```
ffffffe0004351fa-ffffffe00043590a: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814efb60)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814efb60-ffffffff814f0587: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814e00a0)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814e00a0-ffffffff814e0ac7: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814ebbf0)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff814ebbf0-ffffffff814ec617: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81504c00)
Location: block/ioctl.c:513
Inline: False
Direct callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:block_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff81504c00-ffffffff81505627: blkdev_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, mode, cmd, arg</code> ➡️ <code>file, cmd, arg</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
