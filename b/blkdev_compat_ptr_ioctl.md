# Function: <code>blkdev_compat_ptr_ioctl</code>

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
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81557990)
Location: block/ioctl.c:241
Inline: False
```
**Symbols:**

```
ffffffff81557990-ffffffff815579bf: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81573f90)
Location: block/ioctl.c:226
Inline: False
```
**Symbols:**

```
ffffffff81573f90-ffffffff81573fbc: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8157c020)
Location: block/ioctl.c:228
Inline: False
```
**Symbols:**

```
ffffffff8157c020-ffffffff8157c04c: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815e1570)
Location: block/ioctl.c:241
Inline: False
```
**Symbols:**

```
ffffffff815e1570-ffffffff815e159c: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81690150)
Location: block/ioctl.c:243
Inline: False
```
**Symbols:**

```
ffffffff81690150-ffffffff81690194: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8174ecd0)
Location: block/ioctl.c:243
Inline: False
```
**Symbols:**

```
ffffffff8174ecd0-ffffffff8174ed14: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8178af60)
Location: block/ioctl.c:245
Inline: False
```
**Symbols:**

```
ffffffff8178af60-ffffffff8178afa1: blkdev_compat_ptr_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_compat_ptr_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff817cd6b0)
Location: block/ioctl.c:246
Inline: False
```
**Symbols:**

```
ffffffff817cd6b0-ffffffff817cd6f1: blkdev_compat_ptr_ioctl (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
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
