# Function: <code>blkdev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81249000)
Location: fs/block_dev.c:1340
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:add_disk
```
**Symbols:**

```
ffffffff81249000-ffffffff8124933d: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271b20)
Location: fs/block_dev.c:1412
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81271b20-ffffffff81271e5d: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81285180)
Location: fs/block_dev.c:1658
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81285180-ffffffff812854ae: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292810)
Location: fs/block_dev.c:1585
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81292810-ffffffff81292b0d: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5620)
Location: fs/block_dev.c:1576
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SYSC_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff812b5620-ffffffff812b5937: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd480)
Location: fs/block_dev.c:1600
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff812dd480-ffffffff812dd7a6: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2a60)
Location: fs/block_dev.c:1633
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff812f2a60-ffffffff812f2d86: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813146b0)
Location: fs/block_dev.c:1692
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff813146b0-ffffffff813147eb: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327a10)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81327a10-ffffffff81327b4b: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813614b0)
Location: fs/block_dev.c:1713
Inline: False
Direct callers:
  - kernel/power/swap.c:get_swap_writer
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
```
**Symbols:**

```
ffffffff813614b0-ffffffff81361610: blkdev_get (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e28f8)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffff8000103e28f8-ffff8000103e2a5c: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05bab3c)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c05bab3c-c05baca4: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e86b0)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c0000000004e86b0-c0000000004e884c: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298e18)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffe000298e18-ffffffe000298f2e: blkdev_get (STB_GLOBAL)
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
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131fff0)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8131fff0-ffffffff8132012b: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310b90)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81310b90-ffffffff81310ccb: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131dac0)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8131dac0-ffffffff8131dbfb: blkdev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_get(struct block_device *bdev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132f7c0)
Location: fs/block_dev.c:1695
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:blkdev_get_by_path
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8132f7c0-ffffffff8132f8fb: blkdev_get (STB_GLOBAL)
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
