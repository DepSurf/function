# Function: <code>check_disk_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81248280)
Location: fs/block_dev.c:1124
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81248280-ffffffff812482e9: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270a00)
Location: fs/block_dev.c:1196
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81270a00-ffffffff81270a69: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81284370)
Location: fs/block_dev.c:1448
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81284370-ffffffff812843d9: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291a10)
Location: fs/block_dev.c:1372
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81291a10-ffffffff81291a77: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4770)
Location: fs/block_dev.c:1362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff812b4770-ffffffff812b47da: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbc90)
Location: fs/block_dev.c:1388
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff812dbc90-ffffffff812dbcfc: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f1380)
Location: fs/block_dev.c:1427
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff812f1380-ffffffff812f13ec: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313230)
Location: fs/block_dev.c:1486
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81313230-ffffffff8131329c: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326150)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81326150-ffffffff813261bc: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1463
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81361b76-ffffffff81361ba0: check_disk_change.cold (STB_LOCAL)
ffffffff8135ff20-ffffffff8135ffd7: check_disk_change (STB_GLOBAL)
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
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e03e8)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
  - drivers/mmc/core/block.c:mmc_blk_open
```
**Symbols:**

```
ffff8000103e03e8-ffff8000103e0464: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b923c)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
  - drivers/mmc/core/block.c:mmc_blk_open
```
**Symbols:**

```
c05b923c-c05b929c: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e6120)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
c0000000004e6120-c0000000004e61e0: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297154)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
  - drivers/mmc/core/block.c:mmc_blk_open
```
**Symbols:**

```
ffffffe000297154-ffffffe0002971b6: check_disk_change (STB_GLOBAL)
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
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131e730)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff8131e730-ffffffff8131e79c: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f2d0)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff8130f2d0-ffffffff8130f33c: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c200)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff8131c200-ffffffff8131c26c: check_disk_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_disk_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132e310)
Location: fs/block_dev.c:1482
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff8132e310-ffffffff8132e37c: check_disk_change (STB_GLOBAL)
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
