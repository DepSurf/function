# Function: <code>pages_are_mergeable</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pages_are_mergeable(struct page *a, struct page *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817ced60)
Location: lib/scatterlist.c:413
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff817ced60-ffffffff817ceded: pages_are_mergeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pages_are_mergeable(struct page *a, struct page *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d210)
Location: lib/scatterlist.c:415
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff8180d210-ffffffff8180d29d: pages_are_mergeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pages_are_mergeable(struct page *a, struct page *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81852ec0)
Location: lib/scatterlist.c:416
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff81852ec0-ffffffff81852f4d: pages_are_mergeable (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
