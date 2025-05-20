# Function: <code>bdev_disk_changed</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327450)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81327450-ffffffff813274b3: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813601a0)
Location: fs/block_dev.c:1492
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff813601a0-ffffffff81360274: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136c810)
Location: fs/block_dev.c:1236
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff8136c810-ffffffff8136c8dd: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374040)
Location: fs/block_dev.c:1242
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81374040-ffffffff81374147: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bdev_disk_changed(struct gendisk *disk, bool invalidate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (ffffffff815e6c80)
Location: block/partitions/core.c:665
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:blkdev_get_whole
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff815e6a50-ffffffff815e6c7d: bdev_disk_changed.part.0 (STB_LOCAL)
ffffffff81cd8c23-ffffffff81cd8d64: bdev_disk_changed.part.0.cold (STB_LOCAL)
ffffffff815e6c80-ffffffff815e6cac: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bdev_disk_changed(struct gendisk *disk, bool invalidate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (ffffffff81695df0)
Location: block/partitions/core.c:653
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:blkdev_get_whole
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81695be0-ffffffff81695de6: bdev_disk_changed.part.0 (STB_LOCAL)
ffffffff81e8c707-ffffffff81e8c833: bdev_disk_changed.part.0.cold (STB_LOCAL)
ffffffff81695df0-ffffffff81695e2c: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bdev_disk_changed(struct gendisk *disk, bool invalidate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (ffffffff81755190)
Location: block/partitions/core.c:655
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:blkdev_get_whole
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81754e40-ffffffff8175517a: bdev_disk_changed.part.0 (STB_LOCAL)
ffffffff82076b12-ffffffff82076b27: bdev_disk_changed.part.0.cold (STB_LOCAL)
ffffffff81755190-ffffffff817551cc: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bdev_disk_changed(struct gendisk *disk, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:652
Inline: False
Direct callers:
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:blkdev_get_whole
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff820f692d-ffffffff820f6942: bdev_disk_changed.cold (STB_LOCAL)
ffffffff81790d50-ffffffff81791187: bdev_disk_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdev_disk_changed(struct gendisk *disk, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817d48c0)
Location: block/partitions/core.c:646
Inline: False
Direct callers:
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:blkdev_get_whole
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff817d48c0-ffffffff817d4a9d: bdev_disk_changed (STB_GLOBAL)
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
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e23d8)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffff8000103e23d8-ffff8000103e2458: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba5ac)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c05ba5ac-c05ba620: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7fe0)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c0000000004e7fe0-c0000000004e80a0: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe00029899a)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffe00029899a-ffffffe000298a1c: bdev_disk_changed (STB_LOCAL)
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
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131fa30)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8131fa30-ffffffff8131fa93: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813105d0)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff813105d0-ffffffff81310633: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d500)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8131d500-ffffffff8131d563: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device *bdev, bool invalidate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132f200)
Location: fs/block_dev.c:1511
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8132f200-ffffffff8132f263: bdev_disk_changed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
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
