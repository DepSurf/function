# Function: <code>bitmap_start_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169ca00)
Location: drivers/md/bitmap.c:1501
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff8169ca00-ffffffff8169caf0: bitmap_start_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fdbd0)
Location: drivers/md/bitmap.c:1508
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff816fdbd0-ffffffff816fdcc0: bitmap_start_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f830)
Location: drivers/md/bitmap.c:1536
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff8172f830-ffffffff8172f920: bitmap_start_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81748d00)
Location: drivers/md/bitmap.c:1538
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81748d00-ffffffff81748dfc: bitmap_start_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bafe0)
Location: drivers/md/md-bitmap.c:1542
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff817bafe0-ffffffff817bb0dc: bitmap_start_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bitmap_start_sync(struct bitmap *bitmap, sector_t offset, sector_t *blocks, int degraded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81803180)
Location: drivers/md/md-bitmap.c:1542
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_load
  - drivers/md/md-bitmap.c:bitmap_sync_with_cluster
```
**Symbols:**

```
ffffffff81803180-ffffffff8180327c: bitmap_start_sync (STB_GLOBAL)
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
