# Function: <code>register_blkdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9aa0)
Location: block/genhd.c:286
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_init
  - drivers/block/virtio_blk.c:init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff813c9aa0-ffffffff813c9bd3: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140dd10)
Location: block/genhd.c:287
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_init
  - drivers/block/virtio_blk.c:init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff8140dd10-ffffffff8140de45: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814290a0)
Location: block/genhd.c:287
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814290a0-ffffffff814291d5: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814373e0)
Location: block/genhd.c:288
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814373e0-ffffffff8143751a: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814631a0)
Location: block/genhd.c:325
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814631a0-ffffffff814632f9: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:340
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff81498e1b-ffffffff81498e3c: register_blkdev.cold.33 (STB_LOCAL)
ffffffff81496ae0-ffffffff81496c1f: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:353
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814b2f5b-ffffffff814b2f7c: register_blkdev.cold.32 (STB_LOCAL)
ffffffff814b0a00-ffffffff814b0b3f: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814e1443-ffffffff814e1491: register_blkdev.cold (STB_LOCAL)
ffffffff814dee20-ffffffff814def51: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814fa893-ffffffff814fa8e1: register_blkdev.cold (STB_LOCAL)
ffffffff814f8260-ffffffff814f8391: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:440
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff8155b860-ffffffff8155b8ae: register_blkdev.cold (STB_LOCAL)
ffffffff81558e10-ffffffff81558f41: register_blkdev (STB_GLOBAL)
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
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f94d8)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffff8000105f94d8-ffff8000105f966c: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a467c)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/mtd/mtd_blkdevs.c:register_mtd_blktrans
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
c07a467c-c07a47fc: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000791b90)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
c000000000791b90-c000000000791db0: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435c84)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffffffe000435c84-ffffffe000435dd0: register_blkdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814f2e73-ffffffff814f2ec1: register_blkdev.cold (STB_LOCAL)
ffffffff814f0840-ffffffff814f0971: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814e3387-ffffffff814e33d5: register_blkdev.cold (STB_LOCAL)
ffffffff814e0d80-ffffffff814e0eb1: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff814eef03-ffffffff814eef51: register_blkdev.cold (STB_LOCAL)
ffffffff814ec8d0-ffffffff814eca01: register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:354
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff81507f95-ffffffff81507fe3: register_blkdev.cold (STB_LOCAL)
ffffffff81505930-ffffffff81505a61: register_blkdev (STB_GLOBAL)
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
