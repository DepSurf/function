# Function: <code>bd_finish_claiming</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313a60)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81313a60-ffffffff81313af4: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326970)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81326970-ffffffff81326a04: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360d10)
Location: fs/block_dev.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff81360d10-ffffffff81360da1: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bd_finish_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e0c0)
Location: fs/block_dev.c:1057
Inline: False
```
**Symbols:**

```
ffffffff8136e0c0-ffffffff8136e16b: bd_finish_claiming (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8137533c)
Location: fs/block_dev.c:1063
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4e39)
Location: block/bdev.c:619
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f882)
Location: block/bdev.c:624
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172ac68)
Location: block/bdev.c:623
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766d33)
Location: block/bdev.c:569
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8b9a)
Location: block/bdev.c:560
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
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
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e14b0)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffff8000103e14b0-ffff8000103e15c8: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b92b4)
Location: fs/block_dev.c:1209
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
c05b92b4-c05b9388: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e61e0)
Location: fs/block_dev.c:1209
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
c0000000004e61e0-c0000000004e6344: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297c9c)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffe000297c9c-ffffffe000297d7c: bd_finish_claiming (STB_GLOBAL)
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
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ef50)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff8131ef50-ffffffff8131efe4: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130faf0)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff8130faf0-ffffffff8130fb84: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ca20)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff8131ca20-ffffffff8131cab4: bd_finish_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bd_finish_claiming(struct block_device *bdev, struct block_device *whole, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132e3e0)
Location: fs/block_dev.c:1209
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff8132e3e0-ffffffff8132e472: bd_finish_claiming (STB_GLOBAL)
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
