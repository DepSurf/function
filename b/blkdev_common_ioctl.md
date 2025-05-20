# Function: <code>blkdev_common_ioctl</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81557d80)
Location: block/ioctl.c:494
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81557d80-ffffffff815585b1: blkdev_common_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81574380)
Location: block/ioctl.c:453
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81574380-ffffffff81574bb0: blkdev_common_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8157c410)
Location: block/ioctl.c:455
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8157c410-ffffffff8157cc3f: blkdev_common_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815e19a0)
Location: block/ioctl.c:468
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff815e19a0-ffffffff815e2227: blkdev_common_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:470
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff816904b0-ffffffff81690e46: blkdev_common_ioctl (STB_LOCAL)
ffffffff81e8c2c7-ffffffff81e8c2f0: blkdev_common_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blkdev_common_ioctl(struct file *file, fmode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:470
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8174f070-ffffffff8174fa2b: blkdev_common_ioctl (STB_LOCAL)
ffffffff82076888-ffffffff820768b0: blkdev_common_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:487
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8178b330-ffffffff8178bcc6: blkdev_common_ioctl (STB_LOCAL)
ffffffff820f670a-ffffffff820f6733: blkdev_common_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_common_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/ioctl.c (0)
Location: block/ioctl.c:498
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff817cda90-ffffffff817ce463: blkdev_common_ioctl (STB_LOCAL)
ffffffff821d3c2f-ffffffff821d3c6c: blkdev_common_ioctl.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
