# Function: <code>unregister_blkdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9be0)
Location: block/genhd.c:342
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_exit
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_exit
  - drivers/block/virtio_blk.c:fini
  - drivers/block/virtio_blk.c:init
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff813c9be0-ffffffff813c9c9b: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140de50)
Location: block/genhd.c:343
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_exit
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_exit
  - drivers/block/virtio_blk.c:fini
  - drivers/block/virtio_blk.c:init
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff8140de50-ffffffff8140df0d: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814291e0)
Location: block/genhd.c:343
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814291e0-ffffffff8142929d: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81437520)
Location: block/genhd.c:344
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81437520-ffffffff814375ce: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463300)
Location: block/genhd.c:389
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81463300-ffffffff814633ae: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81496c20)
Location: block/genhd.c:404
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81496c20-ffffffff81496cce: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b0b40)
Location: block/genhd.c:417
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814b0b40-ffffffff814b0bee: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814def60)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814def60-ffffffff814df01a: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f83a0)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814f83a0-ffffffff814f844e: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81558f50)
Location: block/genhd.c:504
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81558f50-ffffffff81558ffe: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575630)
Location: block/genhd.c:494
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81575630-ffffffff815756de: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157d3b0)
Location: block/genhd.c:282
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff8157d3b0-ffffffff8157d45e: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e4010)
Location: block/genhd.c:299
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff815e4010-ffffffff815e40f9: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81691810)
Location: block/genhd.c:310
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81691810-ffffffff816918f6: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817503b0)
Location: block/genhd.c:287
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff817503b0-ffffffff81750496: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178c670)
Location: block/genhd.c:283
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/virtio_blk.c:virtio_blk_fini
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff8178c670-ffffffff8178c756: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cee40)
Location: block/genhd.c:283
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/virtio_blk.c:virtio_blk_fini
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff817cee40-ffffffff817cef26: unregister_blkdev (STB_GLOBAL)
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
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f9670)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffff8000105f9670-ffff8000105f9738: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a47fc)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
c07a47fc-c07a48c4: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000791db0)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
c000000000791db0-c000000000792038: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435dd0)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffffffe000435dd0-ffffffe000435e7a: unregister_blkdev (STB_GLOBAL)
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
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f0980)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814f0980-ffffffff814f0a2e: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0ec0)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814e0ec0-ffffffff814e0f6e: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814eca10)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff814eca10-ffffffff814ecabe: unregister_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81505a70)
Location: block/genhd.c:418
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/xen-blkfront.c:xlblk_exit
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff81505a70-ffffffff81505b1e: unregister_blkdev (STB_GLOBAL)
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
