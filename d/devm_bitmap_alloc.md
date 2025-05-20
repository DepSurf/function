# Function: <code>devm_bitmap_alloc</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8c70)
Location: lib/bitmap.c:1283
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff815a8c70-ffffffff815a8cc2: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611f10)
Location: lib/bitmap.c:1414
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff81611f10-ffffffff81611f62: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de230)
Location: lib/bitmap.c:1444
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff816de230-ffffffff816de291: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce3d0)
Location: lib/bitmap.c:1425
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff817ce3d0-ffffffff817ce431: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c880)
Location: lib/bitmap.c:1425
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff8180c880-ffffffff8180c8ea: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int *devm_bitmap_alloc(struct device *dev, unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852990)
Location: lib/bitmap.c:749
Inline: False
Direct callers:
  - lib/bitmap.c:devm_bitmap_zalloc
```
**Symbols:**

```
ffffffff81852990-ffffffff818529fa: devm_bitmap_alloc (STB_GLOBAL)
```
</details>
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
