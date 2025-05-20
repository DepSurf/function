# Function: <code>md_bitmap_end_sync</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182f7e8)
Location: drivers/md/md-bitmap.c:1564
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff8182f480-ffffffff8182f528: md_bitmap_end_sync.part.21 (STB_LOCAL)
ffffffff8182f530-ffffffff8182f54d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81871ee8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81871b90-ffffffff81871c3c: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81871c40-ffffffff81871c5d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a3ce8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff818a3990-ffffffff818a3a3c: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff818a3a40-ffffffff818a3a5d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81974e38)
Location: drivers/md/md-bitmap.c:1560
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81973280-ffffffff81973328: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81973330-ffffffff8197334d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81979d38)
Location: drivers/md/md-bitmap.c:1561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81978180-ffffffff81978228: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81978230-ffffffff8197824d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195d318)
Location: drivers/md/md-bitmap.c:1561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff8195c9c0-ffffffff8195ca68: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff8195ca70-ffffffff8195ca8d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a02b78)
Location: drivers/md/md-bitmap.c:1561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81a021f0-ffffffff81a022aa: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81d295ae-ffffffff81d295cd: md_bitmap_end_sync.part.0.cold (STB_LOCAL)
ffffffff81a022b0-ffffffff81a022cd: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b6a97a)
Location: drivers/md/md-bitmap.c:1562
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
```
**Symbols:**

```
ffffffff81b6a400-ffffffff81b6a4c8: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81ef5913-ffffffff81ef5932: md_bitmap_end_sync.part.0.cold (STB_LOCAL)
ffffffff81b6a4d0-ffffffff81b6a505: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d067da)
Location: drivers/md/md-bitmap.c:1562
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
```
**Symbols:**

```
ffffffff81d06210-ffffffff81d062d8: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff820a80f9-ffffffff820a8118: md_bitmap_end_sync.part.0.cold (STB_LOCAL)
ffffffff81d062f0-ffffffff81d06325: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d6f8ba)
Location: drivers/md/md-bitmap.c:1629
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
```
**Symbols:**

```
ffffffff81d6f290-ffffffff81d6f358: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff821294d0-ffffffff821294ef: md_bitmap_end_sync.part.0.cold (STB_LOCAL)
ffffffff81d6f370-ffffffff81d6f3a5: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e26b95)
Location: drivers/md/md-bitmap.c:1633
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
```
**Symbols:**

```
ffffffff81e26570-ffffffff81e26638: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff8220aea6-ffffffff8220aec5: md_bitmap_end_sync.part.0.cold (STB_LOCAL)
ffffffff81e26650-ffffffff81e26685: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af7ae8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffff800010af76a0-ffff800010af77bc: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffff800010af77c0-ffff800010af7828: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd8cd8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
c0bd8b08-c0bd8bf4: md_bitmap_end_sync.part.0 (STB_LOCAL)
c0bd8bf4-c0bd8c48: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be5d80)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
c000000000be5830-c000000000be596c: md_bitmap_end_sync.part.0 (STB_LOCAL)
c000000000be5970-c000000000be599c: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ea60e)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffe0006ea2da-ffffffe0006ea396: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffe0006ea396-ffffffe0006ea3f2: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81849b68)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81849810-ffffffff818498bc: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff818498c0-ffffffff818498dd: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818111b8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81810e60-ffffffff81810f0c: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81810f10-ffffffff81810f2d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81899198)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81898e40-ffffffff81898eec: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff81898ef0-ffffffff81898f0d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b4ca8)
Location: drivers/md/md-bitmap.c:1565
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff818b4940-ffffffff818b49ec: md_bitmap_end_sync.part.0 (STB_LOCAL)
ffffffff818b49f0-ffffffff818b4a0d: md_bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
