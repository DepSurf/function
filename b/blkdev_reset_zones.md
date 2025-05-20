# Function: <code>blkdev_reset_zones</code>

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
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81448f50)
Location: block/blk-zoned.c:204
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff81448f50-ffffffff8144904d: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81457490)
Location: block/blk-zoned.c:204
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff81457490-ffffffff81457589: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81483190)
Location: block/blk-zoned.c:204
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff81483190-ffffffff814832bc: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7de0)
Location: block/blk-zoned.c:246
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff814b7de0-ffffffff814b7f0e: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cb860)
Location: block/blk-zoned.c:214
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff814cb860-ffffffff814cba05: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa190)
Location: block/blk-zoned.c:217
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff814fa190-ffffffff814fa344: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815180e0)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff815180e0-ffffffff8151832f: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f798)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffff80001061f798-ffff80001061f9d8: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c72c0)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
c07c72c0-c07c7628: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bef30)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
c0000000007bef30-c0000000007bf218: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe0004521e2)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffe0004521e2-ffffffe00045239e: blkdev_reset_zones (STB_GLOBAL)
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
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815106c0)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff815106c0-ffffffff8151090f: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815009e0)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff815009e0-ffffffff81500c2f: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c750)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff8150c750-ffffffff8150c99f: blkdev_reset_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_reset_zones(struct block_device *bdev, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81525e30)
Location: block/blk-zoned.c:253
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
```
**Symbols:**

```
ffffffff81525e30-ffffffff8152607a: blkdev_reset_zones (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
