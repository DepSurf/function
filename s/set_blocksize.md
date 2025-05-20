# Function: <code>set_blocksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247400)
Location: fs/block_dev.c:104
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/super.c:ext4_load_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81247400-ffffffff812474c9: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126fcc0)
Location: fs/block_dev.c:117
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/super.c:ext4_fill_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8126fcc0-ffffffff8126fd72: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81282ec0)
Location: fs/block_dev.c:119
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/super.c:ext4_fill_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81282ec0-ffffffff81282f72: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291bd0)
Location: fs/block_dev.c:119
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/super.c:ext4_fill_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81291bd0-ffffffff81291c74: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4950)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - fs/ext4/super.c:ext4_load_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812b4950-ffffffff812b49f4: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db1f0)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_load_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812db1f0-ffffffff812db2b3: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0740)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_load_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812f0740-ffffffff812f0803: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813120c0)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff813120c0-ffffffff81312187: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81325020)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81325020-ffffffff813250d6: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360280)
Location: fs/block_dev.c:120
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:get_swap_writer
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81360280-ffffffff8136035f: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136d800)
Location: fs/block_dev.c:153
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_swap_check
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff8136d800-ffffffff8136d8e7: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813741f0)
Location: fs/block_dev.c:152
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/block_dev.c:sb_min_blocksize
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff813741f0-ffffffff813742cf: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c3f80)
Location: block/bdev.c:143
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:sb_min_blocksize
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff815c3f80-ffffffff815c405f: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166efd0)
Location: block/bdev.c:139
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:sb_min_blocksize
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff8166efd0-ffffffff8166f0bc: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a2d0)
Location: block/bdev.c:138
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:sb_min_blocksize
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff8172a2d0-ffffffff8172a3c1: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766620)
Location: block/bdev.c:138
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:sb_min_blocksize
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff81766620-ffffffff8176670e: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8150)
Location: block/bdev.c:141
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - block/bdev.c:sb_min_blocksize
  - block/ioctl.c:blkdev_bszset
  - block/ioctl.c:blkdev_bszset
```
**Symbols:**

```
ffffffff817a8150-ffffffff817a823e: set_blocksize (STB_GLOBAL)
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
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df5e0)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff8000103df5e0-ffff8000103df6ac: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b78e8)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c05b78e8-c05b79a4: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4400)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000004e4400-c0000000004e4500: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe00029642e)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe00029642e-ffffffe0002964de: set_blocksize (STB_GLOBAL)
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
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d600)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131d600-ffffffff8131d6b6: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e1a0)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8130e1a0-ffffffff8130e256: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b0d0)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131b0d0-ffffffff8131b186: set_blocksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_blocksize(struct block_device *bdev, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132cd70)
Location: fs/block_dev.c:121
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8132cd70-ffffffff8132ce26: set_blocksize (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
