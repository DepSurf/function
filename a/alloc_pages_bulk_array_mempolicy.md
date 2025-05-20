# Function: <code>alloc_pages_bulk_array_mempolicy</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int alloc_pages_bulk_array_mempolicy(gfp_t gfp, long unsigned int nr_pages, struct page **page_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81399340)
Location: mm/mempolicy.c:2351
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
**Symbols:**

```
ffffffff81399340-ffffffff813995a6: alloc_pages_bulk_array_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int alloc_pages_bulk_array_mempolicy(gfp_t gfp, long unsigned int nr_pages, struct page **page_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814191c0)
Location: mm/mempolicy.c:2366
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff814191c0-ffffffff814193fb: alloc_pages_bulk_array_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int alloc_pages_bulk_array_mempolicy(gfp_t gfp, long unsigned int nr_pages, struct page **page_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144c6a0)
Location: mm/mempolicy.c:2377
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff8144c6a0-ffffffff8144c8db: alloc_pages_bulk_array_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int alloc_pages_bulk_array_mempolicy(gfp_t gfp, long unsigned int nr_pages, struct page **page_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81485fe0)
Location: mm/mempolicy.c:2276
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff81485fe0-ffffffff81486256: alloc_pages_bulk_array_mempolicy (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
