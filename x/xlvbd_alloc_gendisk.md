# Function: <code>xlvbd_alloc_gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81573550)
Location: drivers/block/xen-blkfront.c:930
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81573550-ffffffff81573d3e: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815ca5b0)
Location: drivers/block/xen-blkfront.c:1083
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff815ca5b0-ffffffff815cacdc: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f7210)
Location: drivers/block/xen-blkfront.c:1082
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff815f7210-ffffffff815f7921: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160ca20)
Location: drivers/block/xen-blkfront.c:1092
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8160ca20-ffffffff8160d181: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81675300)
Location: drivers/block/xen-blkfront.c:1092
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81675300-ffffffff81675a0b: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1092
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff816b25a0-ffffffff816b2c62: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff816b3331-ffffffff816b3363: xlvbd_alloc_gendisk.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff816d1c80-ffffffff816d234b: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff816d4593-ffffffff816d45c5: xlvbd_alloc_gendisk.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff8170d490-ffffffff8170db66: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff8170fda3-ffffffff8170fe00: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81731790-ffffffff81731e66: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff8173408d-ffffffff817340ea: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1101
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff817ef8e0-ffffffff817efbcf: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff817f1674-ffffffff817f16ce: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1102
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff818041e0-ffffffff818044c7: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff81c0fd57-ffffffff81c0fdb1: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1102
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff817e8f80-ffffffff817e9269: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff81c01efb-ffffffff81c01f55: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1059
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81875320-ffffffff81875924: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff81d05c4d-ffffffff81d05caa: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1065
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff819bc5a0-ffffffff819bcb94: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff81ece4cb-ffffffff81ece515: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b31be0)
Location: drivers/block/xen-blkfront.c:1068
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81b31be0-ffffffff81b32241: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b85280)
Location: drivers/block/xen-blkfront.c:1069
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81b85280-ffffffff81b8590b: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd9190)
Location: drivers/block/xen-blkfront.c:1069
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81bd9190-ffffffff81bd981b: xlvbd_alloc_gendisk (STB_LOCAL)
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
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010928fc0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffff800010928fc0-ffff800010929718: xlvbd_alloc_gendisk (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1107
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff816f7700-ffffffff816f7dfb: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff816fa121-ffffffff816fa17e: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81724c50-ffffffff81725326: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff8172754d-ffffffff817275aa: xlvbd_alloc_gendisk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xlvbd_alloc_gendisk(blkif_sector_t capacity, struct blkfront_info *info, u16 vdisk_info, u16 sector_size, unsigned int physical_sector_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1091
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff8173fb90-ffffffff8174024f: xlvbd_alloc_gendisk (STB_LOCAL)
ffffffff8174299d-ffffffff817429f7: xlvbd_alloc_gendisk.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u16 vdisk_info</code>
</li>
<li>
<b>Param reordered. </b>
<code>capacity, info, vdisk_info, sector_size, physical_sector_size</code> ➡️ <code>capacity, info, sector_size, physical_sector_size</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
