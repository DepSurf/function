# Function: <code>bitmap_end_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169caf0)
Location: drivers/md/bitmap.c:1525
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_close_sync
```
**Symbols:**

```
ffffffff8169caf0-ffffffff8169cba9: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fdcc0)
Location: drivers/md/bitmap.c:1532
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
  - drivers/md/bitmap.c:bitmap_close_sync
```
**Symbols:**

```
ffffffff816fdcc0-ffffffff816fdd79: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f920)
Location: drivers/md/bitmap.c:1560
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
  - drivers/md/bitmap.c:bitmap_close_sync
```
**Symbols:**

```
ffffffff8172f920-ffffffff8172f9d9: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81748fbb)
Location: drivers/md/bitmap.c:1562
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
Direct callers:
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81748e00-ffffffff81748ea8: bitmap_end_sync.part.18 (STB_LOCAL)
ffffffff81748eb0-ffffffff81748ecd: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bb41b)
Location: drivers/md/md-bitmap.c:1566
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff817bb0e0-ffffffff817bb188: bitmap_end_sync.part.19 (STB_LOCAL)
ffffffff817bb190-ffffffff817bb1ad: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_end_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int aborted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818035e8)
Location: drivers/md/md-bitmap.c:1566
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81803280-ffffffff81803328: bitmap_end_sync.part.21 (STB_LOCAL)
ffffffff81803330-ffffffff8180334d: bitmap_end_sync (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
