# Function: <code>sg_free_append_table</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sg_free_append_table(struct sg_append_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613781)
Location: lib/scatterlist.c:241
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff81613450-ffffffff816134b7: sg_free_append_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sg_free_append_table(struct sg_append_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816e0005)
Location: lib/scatterlist.c:241
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff816dfb10-ffffffff816dfb97: sg_free_append_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sg_free_append_table(struct sg_append_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf830)
Location: lib/scatterlist.c:241
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff817cf830-ffffffff817cf8b7: sg_free_append_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sg_free_append_table(struct sg_append_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e850)
Location: lib/scatterlist.c:243
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff8180e850-ffffffff8180e8d7: sg_free_append_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sg_free_append_table(struct sg_append_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff818544d0)
Location: lib/scatterlist.c:243
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff818544d0-ffffffff81854557: sg_free_append_table (STB_GLOBAL)
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
