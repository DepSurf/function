# Function: <code>bd_prepare_to_claim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812490ba)
Location: fs/block_dev.c:791
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271bda)
Location: fs/block_dev.c:869
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8128523a)
Location: fs/block_dev.c:1121
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812928c1)
Location: fs/block_dev.c:1046
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b56d4)
Location: fs/block_dev.c:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd531)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2b11)
Location: fs/block_dev.c:1076
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314560)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326ed0)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361359)
Location: fs/block_dev.c:1054
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e170)
Location: fs/block_dev.c:1007
Inline: False
Direct callers:
  - fs/block_dev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8136e170-ffffffff8136e2b5: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374a80)
Location: fs/block_dev.c:1013
Inline: False
Direct callers:
  - fs/block_dev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81374a80-ffffffff81374bc5: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c43c0)
Location: block/bdev.c:569
Inline: False
Direct callers:
  - block/bdev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff815c43c0-ffffffff815c4505: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166e8d0)
Location: block/bdev.c:574
Inline: False
Direct callers:
  - block/bdev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8166e8d0-ffffffff8166ea1d: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729b90)
Location: block/bdev.c:573
Inline: False
Direct callers:
  - block/bdev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81729b90-ffffffff81729cdd: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81765d50)
Location: block/bdev.c:517
Inline: False
Direct callers:
  - block/bdev.c:truncate_bdev_range
  - block/genhd.c:disk_scan_partitions
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81765d50-ffffffff81765e7d: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bd_prepare_to_claim(struct block_device *bdev, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a7950)
Location: block/bdev.c:508
Inline: False
Direct callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:truncate_bdev_range
  - block/genhd.c:disk_scan_partitions
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817a7950-ffffffff817a7a7d: bd_prepare_to_claim (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9b04)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7608)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002982ca)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f4b0)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310050)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cf80)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ec64)
Location: fs/block_dev.c:1073
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
```
</details>
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
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct blk_holder_ops *hops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
