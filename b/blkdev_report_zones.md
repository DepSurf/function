# Function: <code>blkdev_report_zones</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81448b60)
Location: block/blk-zoned.c:65
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff81448b60-ffffffff81448f45: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814570e0)
Location: block/blk-zoned.c:65
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff814570e0-ffffffff81457485: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81482dc0)
Location: block/blk-zoned.c:65
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff81482dc0-ffffffff81483184: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7a40)
Location: block/blk-zoned.c:107
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff814b7a40-ffffffff814b7ddf: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cb6f0)
Location: block/blk-zoned.c:159
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff814cb6f0-ffffffff814cb853: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa050)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff814fa050-ffffffff814fa18b: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81517f20)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81517f20-ffffffff8151805b: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578710)
Location: block/blk-zoned.c:155
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81578710-ffffffff8157876b: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595100)
Location: block/blk-zoned.c:155
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81595100-ffffffff81595164: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159bec0)
Location: block/blk-zoned.c:147
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff8159bec0-ffffffff8159bf22: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816042a0)
Location: block/blk-zoned.c:147
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-zone.c:dm_report_zones
```
**Symbols:**

```
ffffffff816042a0-ffffffff81604302: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b79a0)
Location: block/blk-zoned.c:146
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-zone.c:dm_report_zones
```
**Symbols:**

```
ffffffff816b79a0-ffffffff816b7a4f: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81777ac0)
Location: block/blk-zoned.c:144
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-zone.c:dm_report_zones
```
**Symbols:**

```
ffffffff81777ac0-ffffffff81777b74: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b7660)
Location: block/blk-zoned.c:138
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-zone.c:dm_report_zones
```
**Symbols:**

```
ffffffff817b7660-ffffffff817b7709: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:138
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-zone.c:dm_report_zones
```
**Symbols:**

```
ffffffff821d4a87-ffffffff821d4ab2: blkdev_report_zones.cold (STB_LOCAL)
ffffffff817fc230-ffffffff817fc2da: blkdev_report_zones (STB_GLOBAL)
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
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f558)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffff80001061f558-ffff80001061f6d4: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c6fb8)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
c07c6fb8-c07c71f4: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bed30)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
c0000000007bed30-c0000000007bef2c: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000452096)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffe000452096-ffffffe0004521e2: blkdev_report_zones (STB_GLOBAL)
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
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510500)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81510500-ffffffff8151063b: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500820)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81500820-ffffffff8150095b: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c590)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff8150c590-ffffffff8150c6cb: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device *bdev, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81525c70)
Location: block/blk-zoned.c:163
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81525c70-ffffffff81525dab: blkdev_report_zones (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>report_zones_cb cb</code>
</li>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone *zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, zones, nr_zones</code> ➡️ <code>bdev, sector, nr_zones, cb, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int *nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
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
