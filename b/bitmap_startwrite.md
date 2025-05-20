# Function: <code>bitmap_startwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169cea0)
Location: drivers/md/bitmap.c:1356
Inline: False
```
**Symbols:**

```
ffffffff8169cea0-ffffffff8169d089: bitmap_startwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fe180)
Location: drivers/md/bitmap.c:1363
Inline: False
```
**Symbols:**

```
ffffffff816fe180-ffffffff816fe363: bitmap_startwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172fde0)
Location: drivers/md/bitmap.c:1391
Inline: False
```
**Symbols:**

```
ffffffff8172fde0-ffffffff8172ffc3: bitmap_startwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817498d0)
Location: drivers/md/bitmap.c:1393
Inline: False
```
**Symbols:**

```
ffffffff817498d0-ffffffff81749ab5: bitmap_startwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bbbb0)
Location: drivers/md/md-bitmap.c:1397
Inline: False
```
**Symbols:**

```
ffffffff817bbbb0-ffffffff817bbd98: bitmap_startwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bitmap_startwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818038a0)
Location: drivers/md/md-bitmap.c:1397
Inline: False
```
**Symbols:**

```
ffffffff818038a0-ffffffff81803a84: bitmap_startwrite (STB_GLOBAL)
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
