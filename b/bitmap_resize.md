# Function: <code>bitmap_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169dea0)
Location: drivers/md/bitmap.c:1940
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff8169dea0-ffffffff8169e5d3: bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816ff120)
Location: drivers/md/bitmap.c:1974
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff816ff120-ffffffff816ff972: bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81730d60)
Location: drivers/md/bitmap.c:2000
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81730d60-ffffffff81731594: bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81749cc0)
Location: drivers/md/bitmap.c:2038
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81749cc0-ffffffff8174a4ee: bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bbfa0)
Location: drivers/md/md-bitmap.c:2048
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff817bbfa0-ffffffff817bc82c: bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81804080)
Location: drivers/md/md-bitmap.c:2048
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81804080-ffffffff81804919: bitmap_resize (STB_GLOBAL)
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
