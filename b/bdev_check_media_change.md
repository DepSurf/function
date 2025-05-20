# Function: <code>bdev_check_media_change</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bdev_check_media_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff81577916)
Location: block/genhd.c:1885
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81bf2919-ffffffff81bf2936: bdev_check_media_change.cold (STB_LOCAL)
ffffffff81577850-ffffffff81577962: bdev_check_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bdev_check_media_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff8157f659)
Location: block/genhd.c:1590
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81be48ef-ffffffff81be490c: bdev_check_media_change.cold (STB_LOCAL)
ffffffff8157f590-ffffffff8157f6a5: bdev_check_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bdev_check_media_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/disk-events.c (ffffffff815eeec9)
Location: block/disk-events.c:275
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81cd9bb2-ffffffff81cd9bcf: bdev_check_media_change.cold (STB_LOCAL)
ffffffff815eee00-ffffffff815eef15: bdev_check_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bdev_check_media_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/disk-events.c (ffffffff8169f848)
Location: block/disk-events.c:275
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff81e8d642-ffffffff81e8d65f: bdev_check_media_change.cold (STB_LOCAL)
ffffffff8169f790-ffffffff8169f8a2: bdev_check_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool bdev_check_media_change(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175e120)
Location: block/disk-events.c:275
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/md/md.c:md_open
```
**Symbols:**

```
ffffffff8175e120-ffffffff8175e24b: bdev_check_media_change (STB_GLOBAL)
```
</details>
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
</ul>
