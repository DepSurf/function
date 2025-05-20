# Function: <code>blk_unregister_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9cd0)
Location: block/genhd.c:485
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/brd.c:brd_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff813c9cd0-ffffffff813c9cec: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140fbd0)
Location: block/genhd.c:486
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/brd.c:brd_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff8140df40-ffffffff8140df5c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142af60)
Location: block/genhd.c:486
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814292d0-ffffffff814292ec: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8143919a)
Location: block/genhd.c:487
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81437600-ffffffff8143761c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81465263)
Location: block/genhd.c:532
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814633e0-ffffffff814633fc: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81498bb4)
Location: block/genhd.c:547
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81496d00-ffffffff81496d1c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b2d04)
Location: block/genhd.c:560
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814b0c20-ffffffff814b0c3c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e11bd)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814df050-ffffffff814df06c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814fa618)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814f8480-ffffffff814f849c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155b5b6)
Location: block/genhd.c:659
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81559030-ffffffff8155904c: blk_unregister_region (STB_GLOBAL)
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
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fc1c0)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffff8000105f97a8-ffff8000105f97e4: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a7230)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
c07a491c-c07a494c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c0000000007956b4)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
c0000000007920b0-c0000000007920f8: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe00043818e)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffe000435ed4-ffffffe000435f0e: blk_unregister_region (STB_GLOBAL)
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
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f2bf8)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814f0a60-ffffffff814f0a7c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e3128)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814e0fa0-ffffffff814e0fbc: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814eec88)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff814ecaf0-ffffffff814ecb0c: blk_unregister_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_unregister_region(dev_t devt, long unsigned int range);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81507d32)
Location: block/genhd.c:573
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff81505b50-ffffffff81505b6c: blk_unregister_region (STB_GLOBAL)
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
