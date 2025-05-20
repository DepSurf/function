# Function: <code>blkdev_issue_secure_erase</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkdev_issue_secure_erase(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:305
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81e8b704-ffffffff81e8b734: blkdev_issue_secure_erase.cold (STB_LOCAL)
ffffffff81682380-ffffffff81682559: blkdev_issue_secure_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blkdev_issue_secure_erase(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:303
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff82075e9d-ffffffff82075ecd: blkdev_issue_secure_erase.cold (STB_LOCAL)
ffffffff8173fa10-ffffffff8173fbf5: blkdev_issue_secure_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blkdev_issue_secure_erase(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:303
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff820f5d89-ffffffff820f5db9: blkdev_issue_secure_erase.cold (STB_LOCAL)
ffffffff8177bf40-ffffffff8177c11f: blkdev_issue_secure_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_issue_secure_erase(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:303
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff821d3293-ffffffff821d32c3: blkdev_issue_secure_erase.cold (STB_LOCAL)
ffffffff817be330-ffffffff817be50f: blkdev_issue_secure_erase (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
