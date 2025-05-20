# Function: <code>blk_register_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9ca0)
Location: block/genhd.c:476
Inline: True
Inline callers:
  - block/genhd.c:add_disk
Direct callers:
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813c9ca0-ffffffff813c9ccd: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140f3ec)
Location: block/genhd.c:477
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - drivers/block/brd.c:brd_init
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8140df10-ffffffff8140df3d: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142a789)
Location: block/genhd.c:477
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814292a0-ffffffff814292cd: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81438a50)
Location: block/genhd.c:478
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814375d0-ffffffff814375f8: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81464ab5)
Location: block/genhd.c:523
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814633b0-ffffffff814633d8: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8149852f)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81496cd0-ffffffff81496cf8: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b266a)
Location: block/genhd.c:551
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814b0bf0-ffffffff814b0c18: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0982)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814df020-ffffffff814df04e: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f9f16)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814f8450-ffffffff814f847e: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155ac49)
Location: block/genhd.c:650
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81559000-ffffffff8155902e: blk_register_region (STB_GLOBAL)
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
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fb9bc)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffff8000105f9738-ffff8000105f97a4: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a69e4)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c07a48c4-c07a491c: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000794d04)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c000000000792040-c0000000007920b0: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000437aa4)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffe000435e7a-ffffffe000435ed4: blk_register_region (STB_GLOBAL)
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
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f24f6)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814f0a30-ffffffff814f0a5e: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e2a26)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814e0f70-ffffffff814e0f9e: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ee586)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814ecac0-ffffffff814ecaee: blk_register_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module *module, struct kobject * (*probe)(dev_t, int *, void *), int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81507620)
Location: block/genhd.c:564
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
Direct callers:
  - drivers/block/loop.c:loop_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:sd_remove
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81505b20-ffffffff81505b4e: blk_register_region (STB_GLOBAL)
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
