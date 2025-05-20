# Function: <code>bitmap_unplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169dd30)
Location: drivers/md/bitmap.c:975
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8169dd30-ffffffff8169de96: bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fefb0)
Location: drivers/md/bitmap.c:982
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff816fefb0-ffffffff816ff112: bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81730c50)
Location: drivers/md/bitmap.c:1002
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81730c50-ffffffff81730d5e: bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81748690)
Location: drivers/md/bitmap.c:1004
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81748690-ffffffff817487a2: bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817ba920)
Location: drivers/md/md-bitmap.c:1008
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff817ba920-ffffffff817baa2f: bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818028c0)
Location: drivers/md/md-bitmap.c:1008
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818028c0-ffffffff818029cf: bitmap_unplug (STB_GLOBAL)
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
