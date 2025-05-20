# Function: <code>blkdev_reset_zones_ioctl</code>

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
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814491f0)
Location: block/blk-zoned.c:320
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814491f0-ffffffff814492cd: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81457720)
Location: block/blk-zoned.c:320
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81457720-ffffffff81457800: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81483450)
Location: block/blk-zoned.c:320
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81483450-ffffffff81483530: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b81f0)
Location: block/blk-zoned.c:366
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814b81f0-ffffffff814b82d3: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cc130)
Location: block/blk-zoned.c:334
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814cc130-ffffffff814cc213: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa9d0)
Location: block/blk-zoned.c:335
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814fa9d0-ffffffff814faab1: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518950)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81518950-ffffffff81518a31: blkdev_reset_zones_ioctl (STB_GLOBAL)
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
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff8000106203d0)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffff8000106203d0-ffff8000106204b0: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7e78)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c07c7e78-c07c7fb4: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bfb20)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c0000000007bfb20-c0000000007bfc84: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000452ad2)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffe000452ad2-ffffffe000452b76: blkdev_reset_zones_ioctl (STB_GLOBAL)
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
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510f30)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81510f30-ffffffff81511011: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81501250)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81501250-ffffffff81501331: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150cfc0)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8150cfc0-ffffffff8150d0a1: blkdev_reset_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_reset_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815266a0)
Location: block/blk-zoned.c:374
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff815266a0-ffffffff81526781: blkdev_reset_zones_ioctl (STB_GLOBAL)
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
