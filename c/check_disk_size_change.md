# Function: <code>check_disk_size_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81248160)
Location: fs/block_dev.c:1067
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:invalidate_partitions
```
**Symbols:**

```
ffffffff81248160-ffffffff812481ee: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270910)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81270910-ffffffff81270964: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81284280)
Location: fs/block_dev.c:1394
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81284280-ffffffff812842d4: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291930)
Location: fs/block_dev.c:1319
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81291930-ffffffff81291984: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4690)
Location: fs/block_dev.c:1309
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff812b4690-ffffffff812b46e4: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1332
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff812ddf4b-ffffffff812ddf6b: check_disk_size_change.cold.43 (STB_LOCAL)
ffffffff812ddcf0-ffffffff812ddd3f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1371
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff812f353b-ffffffff812f355b: check_disk_size_change.cold.44 (STB_LOCAL)
ffffffff812f32e0-ffffffff812f332f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1423
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81314fc6-ffffffff81314fe6: check_disk_size_change.cold (STB_LOCAL)
ffffffff81314d40-ffffffff81314d8f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81327e50-ffffffff81327e70: check_disk_size_change.cold (STB_LOCAL)
ffffffff81327360-ffffffff813273af: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
```
**Symbols:**

```
ffffffff81360050-ffffffff813600f7: check_disk_size_change (STB_LOCAL)
ffffffff81361ba0-ffffffff81361be9: check_disk_size_change.cold (STB_LOCAL)
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
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e2270)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffff8000103e2270-ffff8000103e2314: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba408)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
c05ba408-c05ba514: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7de0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
c0000000004e7de0-c0000000004e7e94: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298880)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffe000298880-ffffffe000298908: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81320430-ffffffff81320450: check_disk_size_change.cold (STB_LOCAL)
ffffffff8131f940-ffffffff8131f98f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81310fd0-ffffffff81310ff0: check_disk_size_change.cold (STB_LOCAL)
ffffffff813104e0-ffffffff8131052f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8131df00-ffffffff8131df20: check_disk_size_change.cold (STB_LOCAL)
ffffffff8131d410-ffffffff8131d45f: check_disk_size_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void check_disk_size_change(struct gendisk *disk, struct block_device *bdev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1419
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8132fbf7-ffffffff8132fc17: check_disk_size_change.cold (STB_LOCAL)
ffffffff8132f110-ffffffff8132f15f: check_disk_size_change (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool verbose</code>
</li>
</ul>
</details>
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
