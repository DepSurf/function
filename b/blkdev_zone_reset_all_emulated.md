# Function: <code>blkdev_zone_reset_all_emulated</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_reset_all_emulated(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:190
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff81604490-ffffffff81604649: blkdev_zone_reset_all_emulated (STB_LOCAL)
ffffffff81cda36b-ffffffff81cda388: blkdev_zone_reset_all_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_reset_all_emulated(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:189
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff816b7c10-ffffffff816b7da3: blkdev_zone_reset_all_emulated (STB_LOCAL)
ffffffff81e8dede-ffffffff81e8df03: blkdev_zone_reset_all_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_reset_all_emulated(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:186
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff81778220-ffffffff817783a7: blkdev_zone_reset_all_emulated (STB_LOCAL)
ffffffff8207726b-ffffffff82077290: blkdev_zone_reset_all_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_reset_all_emulated(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:180
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff817b7ad0-ffffffff817b7c51: blkdev_zone_reset_all_emulated (STB_LOCAL)
ffffffff820f72a3-ffffffff820f72c8: blkdev_zone_reset_all_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_reset_all_emulated(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:180
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff817fc850-ffffffff817fc9ec: blkdev_zone_reset_all_emulated (STB_LOCAL)
ffffffff821d4b6b-ffffffff821d4bc1: blkdev_zone_reset_all_emulated.cold (STB_LOCAL)
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
