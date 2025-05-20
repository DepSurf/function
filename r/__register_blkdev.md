# Function: <code>__register_blkdev</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:429
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
ffffffff81bf2821-ffffffff81bf286f: __register_blkdev.cold (STB_LOCAL)
ffffffff81575440-ffffffff81575626: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:217
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
ffffffff81be47e7-ffffffff81be4835: __register_blkdev.cold (STB_LOCAL)
ffffffff8157d1c0-ffffffff8157d3a5: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:232
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
ffffffff81cd8939-ffffffff81cd8987: __register_blkdev.cold (STB_LOCAL)
ffffffff815e41c0-ffffffff815e4434: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:241
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
ffffffff81e8c328-ffffffff81e8c380: __register_blkdev.cold (STB_LOCAL)
ffffffff816915b0-ffffffff81691810: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817500f0)
Location: block/genhd.c:218
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
ffffffff817500f0-ffffffff817503a0: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178c410)
Location: block/genhd.c:214
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff8178c410-ffffffff8178c652: __register_blkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_blkdev(unsigned int major, const char *name, void (*probe)(dev_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cebb0)
Location: block/genhd.c:214
Inline: False
Direct callers:
  - block/genhd.c:genhd_device_init
  - drivers/block/loop.c:loop_init
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/block/xen-blkfront.c:xlblk_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sr.c:init_sr
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
```
**Symbols:**

```
ffffffff817cebb0-ffffffff817cee21: __register_blkdev (STB_GLOBAL)
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
