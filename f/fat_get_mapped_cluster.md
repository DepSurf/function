# Function: <code>fat_get_mapped_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813292e0)
Location: fs/fat/cache.c:304
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813292e0-ffffffff813293fd: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8133f020)
Location: fs/fat/cache.c:304
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff8133f020-ffffffff8133f13d: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81353bb0)
Location: fs/fat/cache.c:304
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81353bb0-ffffffff81353ccd: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813787d0)
Location: fs/fat/cache.c:305
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813787d0-ffffffff813788ed: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813a749e-ffffffff813a74c8: fat_get_mapped_cluster.cold.13 (STB_LOCAL)
ffffffff813a72e0-ffffffff813a73da: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813c028e-ffffffff813c02b8: fat_get_mapped_cluster.cold.14 (STB_LOCAL)
ffffffff813c00d0-ffffffff813c01ca: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813eaa9b-ffffffff813eaac4: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff813ea8e0-ffffffff813ea9de: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81404b3b-ffffffff81404b64: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff81404980-ffffffff81404a7e: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff814529ce-ffffffff814529f7: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff81452810-ffffffff8145290c: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81bed75f-ffffffff81bed788: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff8146ecf0-ffffffff8146edec: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81bdf862-ffffffff81bdf88b: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff814742e0-ffffffff814743f8: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81ccf82b-ffffffff81ccf884: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff814caf90-ffffffff814cb0ae: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff81e82a03-ffffffff81e82a5a: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff81557010-ffffffff81557142: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff82071cde-ffffffff82071d0c: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff815f8ba0-ffffffff815f8cf7: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff820f1973-ffffffff820f19a1: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff81630b20-ffffffff81630c77: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff821cec55-ffffffff821cec83: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff81669fd0-ffffffff8166a127: fat_get_mapped_cluster (STB_GLOBAL)
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
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffff8000104e3560)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffff8000104e3560-ffff8000104e36c4: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c06a26b8)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
c06a26b8-c06a2868: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c000000000620770)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
c000000000620770-c000000000620960: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffe000356cfe)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffe000356cfe-ffffffe000356df2: fat_get_mapped_cluster (STB_GLOBAL)
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
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813fd11b-ffffffff813fd144: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff813fcf60-ffffffff813fd05e: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813edb9b-ffffffff813edbc4: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff813ed9e0-ffffffff813edade: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff813fa49b-ffffffff813fa4c4: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff813fa2e0-ffffffff813fa3de: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_get_mapped_cluster(struct inode *inode, sector_t sector, sector_t last_block, long unsigned int *mapped_blocks, sector_t *bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:310
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
```
**Symbols:**

```
ffffffff814100fb-ffffffff81410124: fat_get_mapped_cluster.cold (STB_LOCAL)
ffffffff8140ff40-ffffffff8141003e: fat_get_mapped_cluster (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
