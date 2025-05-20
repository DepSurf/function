# Function: <code>md_bitmap_dirty_bits</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818310e0)
Location: drivers/md/md-bitmap.c:1690
Inline: False
```
**Symbols:**

```
ffffffff818310e0-ffffffff8183114a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81873c70)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff81873c70-ffffffff81873cda: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a5a80)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff818a5a80-ffffffff818a5aea: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff819759a0)
Location: drivers/md/md-bitmap.c:1686
Inline: False
```
**Symbols:**

```
ffffffff819759a0-ffffffff81975a0a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8197a990)
Location: drivers/md/md-bitmap.c:1687
Inline: False
```
**Symbols:**

```
ffffffff8197a990-ffffffff8197a9fa: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195ebb0)
Location: drivers/md/md-bitmap.c:1687
Inline: False
```
**Symbols:**

```
ffffffff8195ebb0-ffffffff8195ec1a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1687
Inline: False
```
**Symbols:**

```
ffffffff81d29b5f-ffffffff81d29b7e: md_bitmap_dirty_bits.cold (STB_LOCAL)
ffffffff81a044e0-ffffffff81a0455c: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1688
Inline: False
Direct callers:
  - drivers/md/md.c:bitmap_store
```
**Symbols:**

```
ffffffff81ef5ec6-ffffffff81ef5ee5: md_bitmap_dirty_bits.cold (STB_LOCAL)
ffffffff81b6c140-ffffffff81b6c1d8: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1688
Inline: False
Direct callers:
  - drivers/md/md.c:bitmap_store
```
**Symbols:**

```
ffffffff820a84e7-ffffffff820a8506: md_bitmap_dirty_bits.cold (STB_LOCAL)
ffffffff81d08190-ffffffff81d08228: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1755
Inline: False
Direct callers:
  - drivers/md/md.c:bitmap_store
```
**Symbols:**

```
ffffffff821296fc-ffffffff8212971b: md_bitmap_dirty_bits.cold (STB_LOCAL)
ffffffff81d71320-ffffffff81d713b8: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1759
Inline: False
Direct callers:
  - drivers/md/md.c:bitmap_store
```
**Symbols:**

```
ffffffff8220b09b-ffffffff8220b0ba: md_bitmap_dirty_bits.cold (STB_LOCAL)
ffffffff81e283d0-ffffffff81e28468: md_bitmap_dirty_bits (STB_GLOBAL)
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
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010afa8c8)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffff800010afa8c8-ffff800010afa94c: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bdb3e8)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
c0bdb3e8-c0bdb480: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be8840)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
c000000000be8840-c000000000be88e4: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ec242)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffe0006ec242-ffffffe0006ec2ae: md_bitmap_dirty_bits (STB_GLOBAL)
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
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8184b900)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff8184b900-ffffffff8184b96a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81812f20)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff81812f20-ffffffff81812f8a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8189af30)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff8189af30-ffffffff8189af9a: md_bitmap_dirty_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_bitmap_dirty_bits(struct bitmap *bitmap, long unsigned int s, long unsigned int e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b70b0)
Location: drivers/md/md-bitmap.c:1691
Inline: False
```
**Symbols:**

```
ffffffff818b70b0-ffffffff818b711a: md_bitmap_dirty_bits (STB_GLOBAL)
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
