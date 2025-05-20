# Function: <code>bitmap_close_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169cbb0)
Location: drivers/md/bitmap.c:1556
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff8169cbb0-ffffffff8169cc27: bitmap_close_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fdd80)
Location: drivers/md/bitmap.c:1563
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff816fdd80-ffffffff816fddf7: bitmap_close_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f9e0)
Location: drivers/md/bitmap.c:1591
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff8172f9e0-ffffffff8172fa57: bitmap_close_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817497f1)
Location: drivers/md/bitmap.c:1593
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_load
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff81748ed0-ffffffff81748f42: bitmap_close_sync.part.19 (STB_LOCAL)
ffffffff81748f50-ffffffff81748f67: bitmap_close_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bbad7)
Location: drivers/md/md-bitmap.c:1597
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_load
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff817bb1b0-ffffffff817bb222: bitmap_close_sync.part.20 (STB_LOCAL)
ffffffff817bb230-ffffffff817bb247: bitmap_close_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_close_sync(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81803fa7)
Location: drivers/md/md-bitmap.c:1597
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_load
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff81803350-ffffffff818033c2: bitmap_close_sync.part.22 (STB_LOCAL)
ffffffff818033d0-ffffffff818033e6: bitmap_close_sync (STB_GLOBAL)
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
