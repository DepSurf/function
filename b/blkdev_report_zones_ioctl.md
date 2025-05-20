# Function: <code>blkdev_report_zones_ioctl</code>

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
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81449050)
Location: block/blk-zoned.c:261
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81449050-ffffffff814491e5: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81457590)
Location: block/blk-zoned.c:261
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81457590-ffffffff8145771f: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814832c0)
Location: block/blk-zoned.c:261
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814832c0-ffffffff8148344f: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b8040)
Location: block/blk-zoned.c:303
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814b8040-ffffffff814b81ea: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cbf90)
Location: block/blk-zoned.c:272
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814cbf90-ffffffff814cc12d: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa830)
Location: block/blk-zoned.c:275
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814fa830-ffffffff814fa9cd: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518790)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81518790-ffffffff8151894a: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578c60)
Location: block/blk-zoned.c:280
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81578c60-ffffffff81578d72: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815956c0)
Location: block/blk-zoned.c:280
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff815956c0-ffffffff815957d6: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c460)
Location: block/blk-zoned.c:272
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8159c460-ffffffff8159c576: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604af0)
Location: block/blk-zoned.c:344
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81604af0-ffffffff81604bee: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b82c0)
Location: block/blk-zoned.c:337
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff816b82c0-ffffffff816b83db: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81778780)
Location: block/blk-zoned.c:332
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81778780-ffffffff8177889b: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b8360)
Location: block/blk-zoned.c:326
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff817b8360-ffffffff817b8465: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:326
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff821d4db6-ffffffff821d4dcb: blkdev_report_zones_ioctl.cold (STB_LOCAL)
ffffffff817fce40-ffffffff817fcf4f: blkdev_report_zones_ioctl (STB_GLOBAL)
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
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff800010620230)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffff800010620230-ffff8000106203cc: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7bcc)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c07c7bcc-c07c7e78: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf8c0)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c0000000007bf8c0-c0000000007bfb1c: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe00045299e)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffe00045299e-ffffffe000452ad2: blkdev_report_zones_ioctl (STB_GLOBAL)
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
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510d70)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81510d70-ffffffff81510f2a: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81501090)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81501090-ffffffff8150124a: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150ce00)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8150ce00-ffffffff8150cfba: blkdev_report_zones_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_report_zones_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815264e0)
Location: block/blk-zoned.c:314
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff815264e0-ffffffff8152669a: blkdev_report_zones_ioctl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, mode, cmd, arg</code> ➡️ <code>bdev, cmd, arg</code>
</li>
</ul>
</details>
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
