# Function: <code>bd_may_claim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812490d8)
Location: fs/block_dev.c:755
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81249510-ffffffff81249553: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271d5b)
Location: fs/block_dev.c:833
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81271410-ffffffff81271453: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812853b4)
Location: fs/block_dev.c:1085
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81285680-ffffffff812856c2: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292a5a)
Location: fs/block_dev.c:1010
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81292b60-ffffffff81292ba5: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b587c)
Location: fs/block_dev.c:1000
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff812b5990-ffffffff812b59d5: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd6c2)
Location: fs/block_dev.c:1001
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff812dc820-ffffffff812dc862: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2ca2)
Location: fs/block_dev.c:1040
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff812f1650-ffffffff812f1692: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131456d)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff813138d0-ffffffff81313915: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326edd)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff813267e0-ffffffff81326825: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360d33)
Location: fs/block_dev.c:1018
Inline: True
Inline callers:
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff8135f9b0-ffffffff8135f9f5: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e0eb)
Location: fs/block_dev.c:977
Inline: True
Inline callers:
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/block_dev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff8136d1c0-ffffffff8136d20b: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374ad2)
Location: fs/block_dev.c:983
Inline: True
Inline callers:
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/block_dev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff81373a30-ffffffff81373a7b: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4412)
Location: block/bdev.c:539
Inline: True
Inline callers:
  - block/bdev.c:bd_prepare_to_claim
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff815c3d90-ffffffff815c3ddb: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166e922)
Location: block/bdev.c:544
Inline: True
Inline callers:
  - block/bdev.c:bd_prepare_to_claim
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff8166e6f0-ffffffff8166e759: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729be2)
Location: block/bdev.c:543
Inline: True
Inline callers:
  - block/bdev.c:bd_prepare_to_claim
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff81729950-ffffffff817299b9: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81765cc0)
Location: block/bdev.c:475
Inline: True
Direct callers:
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff81765cc0-ffffffff81765d3d: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a78c0)
Location: block/bdev.c:466
Inline: True
Direct callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff817a78c0-ffffffff817a793d: bd_may_claim (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1680)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffff8000103e09c0-ffff8000103e0a4c: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b92e0)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
c05b9a0c-c05b9a70: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e6224)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
c0000000004e74b0-c0000000004e7518: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002982ca)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffe000297a64-ffffffe000297ad0: bd_may_claim (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f4bd)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff8131edc0-ffffffff8131ee05: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131005d)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff8130f960-ffffffff8130f9a5: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cf8d)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff8131c890-ffffffff8131c8d5: bd_may_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bd_may_claim(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ec6d)
Location: fs/block_dev.c:1037
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff8132eb90-ffffffff8132ebd5: bd_may_claim (STB_LOCAL)
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
<li>
<b>Param removed. </b>
<code>struct block_device *whole</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, whole, holder</code> ➡️ <code>bdev, holder, hops</code>
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
