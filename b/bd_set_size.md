# Function: <code>bd_set_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812474d0)
Location: fs/block_dev.c:1143
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:figure_loop_size
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812474d0-ffffffff812475b2: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270620)
Location: fs/block_dev.c:1215
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff81270620-ffffffff812706ff: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81283df0)
Location: fs/block_dev.c:1467
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff81283df0-ffffffff81283ecf: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812914b0)
Location: fs/block_dev.c:1391
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff812914b0-ffffffff81291584: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4200)
Location: fs/block_dev.c:1381
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff812b4200-ffffffff812b42d4: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db820)
Location: fs/block_dev.c:1407
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff812db820-ffffffff812db8f4: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f269b)
Location: fs/block_dev.c:1446
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff812f0fb0-ffffffff812f0fef: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314048)
Location: fs/block_dev.c:1505
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff81312eb0-ffffffff81312eef: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327812)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff81325df0-ffffffff81325e2f: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360af8)
Location: fs/block_dev.c:1482
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8135f050-ffffffff8135f08f: bd_set_size (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e271c)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffff8000103dffc8-ffff8000103e0010: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8a08)
Location: fs/block_dev.c:1501
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
c05b8a08-c05b8a70: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e8494)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
c0000000004e5500-c0000000004e556c: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298d0a)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffe000296dd0-ffffffe000296e18: bd_set_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131fdf2)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff8131e3d0-ffffffff8131e40f: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310992)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff8130ef70-ffffffff8130efaf: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d8c2)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff8131bea0-ffffffff8131bedf: bd_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bd_set_size(struct block_device *bdev, loff_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132f5c2)
Location: fs/block_dev.c:1501
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
**Symbols:**

```
ffffffff8132dc80-ffffffff8132dcbf: bd_set_size (STB_GLOBAL)
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
