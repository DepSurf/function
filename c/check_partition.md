# Function: <code>check_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffff813ce290)
Location: block/partitions/check.c:142
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff813ce290-ffffffff813ce4a6: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffff81413350)
Location: block/partitions/check.c:142
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81413350-ffffffff81413556: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffff8142e880)
Location: block/partitions/check.c:142
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8142e880-ffffffff8142ea85: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffff8143bb90)
Location: block/partitions/check.c:142
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8143bb90-ffffffff8143bdb9: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffff81467ba0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81467ba0-ffffffff81467dcb: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8149bc46-ffffffff8149bc5b: check_partition.cold.2 (STB_LOCAL)
ffffffff8149ba10-ffffffff8149bc46: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814b5f58-ffffffff814b5f6d: check_partition.cold.1 (STB_LOCAL)
ffffffff814b5d20-ffffffff814b5f58: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814e44b4-ffffffff814e44c8: check_partition.cold (STB_LOCAL)
ffffffff814e4270-ffffffff814e44b4: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814fd874-ffffffff814fd888: check_partition.cold (STB_LOCAL)
ffffffff814fd630-ffffffff814fd874: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:115
Inline: False
Direct callers:
  - block/partitions/core.c:blk_add_partitions
```
**Symbols:**

```
ffffffff8155d0f0-ffffffff8155d2ed: check_partition (STB_LOCAL)
ffffffff8155deba-ffffffff8155dedf: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:125
Inline: False
Direct callers:
  - block/partitions/core.c:blk_add_partitions
```
**Symbols:**

```
ffffffff815794f0-ffffffff815796fb: check_partition (STB_LOCAL)
ffffffff81bf2a5c-ffffffff81bf2a99: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:123
Inline: False
Direct callers:
  - block/partitions/core.c:blk_add_partitions
```
**Symbols:**

```
ffffffff81580f50-ffffffff8158115b: check_partition (STB_LOCAL)
ffffffff81be4964-ffffffff81be49a1: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:124
Inline: False
```
**Symbols:**

```
ffffffff815e6260-ffffffff815e64eb: check_partition (STB_LOCAL)
ffffffff81cd8bbc-ffffffff81cd8be8: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:123
Inline: False
```
**Symbols:**

```
ffffffff81695710-ffffffff81695945: check_partition (STB_LOCAL)
ffffffff81e8c6b7-ffffffff81e8c707: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:122
Inline: False
```
**Symbols:**

```
ffffffff817548d0-ffffffff81754b48: check_partition (STB_LOCAL)
ffffffff82076afe-ffffffff82076b12: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:114
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_disk_changed
```
**Symbols:**

```
ffffffff817909d0-ffffffff81790d3b: check_partition (STB_LOCAL)
ffffffff820f6919-ffffffff820f692d: check_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:114
Inline: False
Direct callers:
  - block/partitions/core.c:blk_add_partitions
```
**Symbols:**

```
ffffffff817d4280-ffffffff817d461a: check_partition (STB_LOCAL)
ffffffff821d3d57-ffffffff821d3d6b: check_partition.cold (STB_LOCAL)
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
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffff8000105ff1c8)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffff8000105ff1c8-ffff8000105ff3e4: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (c07aa48c)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
c07aa48c-c07aa694: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (c000000000799240)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
c000000000799240-c000000000799534: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/check.c (ffffffe00043a7b8)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffe00043a7b8-ffffffe00043a99e: check_partition (STB_GLOBAL)
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
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814f5e54-ffffffff814f5e68: check_partition.cold (STB_LOCAL)
ffffffff814f5c10-ffffffff814f5e54: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814e6364-ffffffff814e6378: check_partition.cold (STB_LOCAL)
ffffffff814e6120-ffffffff814e6364: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff814f1ee4-ffffffff814f1ef8: check_partition.cold (STB_LOCAL)
ffffffff814f1ca0-ffffffff814f1ee4: check_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct parsed_partitions *check_partition(struct gendisk *hd, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/check.c (0)
Location: block/partitions/check.c:143
Inline: False
Direct callers:
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8150af44-ffffffff8150af58: check_partition.cold (STB_LOCAL)
ffffffff8150ad00-ffffffff8150af44: check_partition (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
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
