# Function: <code>sg_alloc_append_table_from_pages</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table *sgt_append, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613000)
Location: lib/scatterlist.c:442
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff81613000-ffffffff8161344e: sg_alloc_append_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table *sgt_append, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df5e0)
Location: lib/scatterlist.c:442
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff816df5e0-ffffffff816dfa7c: sg_alloc_append_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table *sgt_append, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cfb60)
Location: lib/scatterlist.c:451
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff817cfb60-ffffffff817d002b: sg_alloc_append_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table *sgt_append, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e9e0)
Location: lib/scatterlist.c:453
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff8180e9e0-ffffffff8180eea5: sg_alloc_append_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table *sgt_append, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854660)
Location: lib/scatterlist.c:454
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
```
**Symbols:**

```
ffffffff81854660-ffffffff81854b28: sg_alloc_append_table_from_pages (STB_GLOBAL)
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
