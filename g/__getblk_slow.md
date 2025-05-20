# Function: <code>__getblk_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243c00)
Location: fs/buffer.c:1091
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff81243c00-ffffffff81243e9e: __getblk_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c9b0)
Location: fs/buffer.c:1082
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff8126c9b0-ffffffff8126cca9: __getblk_slow (STB_GLOBAL)
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
In fs/buffer.c (ffffffff8127fca6)
Location: fs/buffer.c:1083
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8128d256)
Location: fs/buffer.c:1080
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812afd96)
Location: fs/buffer.c:1042
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812d7fe5)
Location: fs/buffer.c:1013
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812ed055)
Location: fs/buffer.c:1021
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8130e806)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff81321826)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1048
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
```
**Symbols:**

```
ffffffff8135be20-ffffffff8135bed6: __getblk_slow (STB_LOCAL)
ffffffff8135e867-ffffffff8135e8b9: __getblk_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1047
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
```
**Symbols:**

```
ffffffff8136a3c0-ffffffff8136a473: __getblk_slow (STB_LOCAL)
ffffffff81beab0b-ffffffff81beab5a: __getblk_slow.cold (STB_LOCAL)
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
In fs/buffer.c (ffffffff81371026)
Location: fs/buffer.c:1043
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff813c09f6)
Location: fs/buffer.c:1018
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff814459d8)
Location: fs/buffer.c:1015
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff814d4a58)
Location: fs/buffer.c:1015
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1127
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
**Symbols:**

```
ffffffff8150c500-ffffffff8150c737: __getblk_slow (STB_LOCAL)
ffffffff820e8c31-ffffffff820e8c97: __getblk_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81541140)
Location: fs/buffer.c:1112
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
**Symbols:**

```
ffffffff81541140-ffffffff81541377: __getblk_slow (STB_LOCAL)
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
In fs/buffer.c (ffff8000103da1b8)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *__getblk_slow(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b36c4)
Location: fs/buffer.c:1022
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
c05b36c4-c05b3a08: __getblk_slow (STB_LOCAL)
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
In fs/buffer.c (c0000000004df1a0)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffe000292fcc)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff81319e06)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8130a9a6)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff813178d6)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff813294d1)
Location: fs/buffer.c:1022
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
