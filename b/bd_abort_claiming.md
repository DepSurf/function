# Function: <code>bd_abort_claiming</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313920)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81313920-ffffffff8131396f: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326830)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81326830-ffffffff8132687f: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813615b3)
Location: fs/block_dev.c:1218
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81360520-ffffffff8136056c: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136da80)
Location: fs/block_dev.c:1084
Inline: False
Direct callers:
  - fs/block_dev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8136da80-ffffffff8136dad8: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374460)
Location: fs/block_dev.c:1090
Inline: False
Direct callers:
  - fs/block_dev.c:truncate_bdev_range
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81374460-ffffffff813744b8: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c455b)
Location: block/bdev.c:646
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff815c41f0-ffffffff815c4248: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ef32)
Location: block/bdev.c:651
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8166e870-ffffffff8166e8d0: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a222)
Location: block/bdev.c:650
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817299d0-ffffffff81729a30: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766571)
Location: block/bdev.c:600
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
Direct callers:
  - block/genhd.c:disk_scan_partitions
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81765e90-ffffffff81765eed: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bd_abort_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a89d4)
Location: block/bdev.c:591
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:truncate_bdev_range
Direct callers:
  - block/genhd.c:disk_scan_partitions
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817a7a90-ffffffff817a7aed: bd_abort_claiming (STB_GLOBAL)
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
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1288)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff8000103e1288-ffff8000103e133c: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9388)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c05b9388-c05b93f0: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e52b0)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000004e52b0-c0000000004e537c: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297ad0)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe000297ad0-ffffffe000297b6a: bd_abort_claiming (STB_GLOBAL)
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
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ee10)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131ee10-ffffffff8131ee5f: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f9b0)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8130f9b0-ffffffff8130f9ff: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c8e0)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131c8e0-ffffffff8131c92f: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132e390)
Location: fs/block_dev.c:1237
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8132e390-ffffffff8132e3dd: bd_abort_claiming (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device *whole</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, whole, holder</code> ➡️ <code>bdev, holder</code>
</li>
</ul>
</details>
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
