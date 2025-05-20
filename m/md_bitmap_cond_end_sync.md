# Function: <code>md_bitmap_cond_end_sync</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182f5f0)
Location: drivers/md/md-bitmap.c:1612
Inline: True
```
**Symbols:**

```
ffffffff8182f5f0-ffffffff8182f771: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81871d00)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff81871d00-ffffffff81871e75: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a3b00)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff818a3b00-ffffffff818a3c75: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81973350)
Location: drivers/md/md-bitmap.c:1608
Inline: True
```
**Symbols:**

```
ffffffff81973350-ffffffff81973480: md_bitmap_cond_end_sync.part.0 (STB_LOCAL)
ffffffff81973480-ffffffff819734c9: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81978250)
Location: drivers/md/md-bitmap.c:1609
Inline: True
```
**Symbols:**

```
ffffffff81978250-ffffffff8197837f: md_bitmap_cond_end_sync.part.0 (STB_LOCAL)
ffffffff81978380-ffffffff819783c9: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195ca90)
Location: drivers/md/md-bitmap.c:1609
Inline: True
```
**Symbols:**

```
ffffffff8195ca90-ffffffff8195cc07: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a0232e)
Location: drivers/md/md-bitmap.c:1609
Inline: True
```
**Symbols:**

```
ffffffff81d295cd-ffffffff81d295ee: md_bitmap_cond_end_sync.cold (STB_LOCAL)
ffffffff81a022d0-ffffffff81a0245c: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1610
Inline: False
```
**Symbols:**

```
ffffffff81ef5932-ffffffff81ef5953: md_bitmap_cond_end_sync.cold (STB_LOCAL)
ffffffff81b6a5a0-ffffffff81b6a776: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1610
Inline: False
```
**Symbols:**

```
ffffffff820a8118-ffffffff820a8139: md_bitmap_cond_end_sync.cold (STB_LOCAL)
ffffffff81d063e0-ffffffff81d065b6: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1677
Inline: False
```
**Symbols:**

```
ffffffff821294ef-ffffffff82129510: md_bitmap_cond_end_sync.cold (STB_LOCAL)
ffffffff81d6f460-ffffffff81d6f636: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1681
Inline: False
```
**Symbols:**

```
ffffffff8220aec5-ffffffff8220aee6: md_bitmap_cond_end_sync.cold (STB_LOCAL)
ffffffff81e26740-ffffffff81e26916: md_bitmap_cond_end_sync (STB_GLOBAL)
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
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af78f0)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffff800010af78f0-ffff800010af7a84: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd9018)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
c0bd9018-c0bd9200: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be5a80)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
c000000000be5a80-c000000000be5cf8: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ea472)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffe0006ea472-ffffffe0006ea5dc: md_bitmap_cond_end_sync (STB_GLOBAL)
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
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81849980)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff81849980-ffffffff81849af5: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81810fd0)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff81810fd0-ffffffff81811145: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81898fb0)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff81898fb0-ffffffff81899125: md_bitmap_cond_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_cond_end_sync(struct bitmap *bitmap, sector_t sector, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b4ab0)
Location: drivers/md/md-bitmap.c:1613
Inline: True
```
**Symbols:**

```
ffffffff818b4ab0-ffffffff818b4c3a: md_bitmap_cond_end_sync (STB_GLOBAL)
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
