# Function: <code>free_the_page</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812094b7)
Location: mm/page_alloc.c:4604
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812707c6)
Location: mm/page_alloc.c:4771
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f606)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1721)
Location: mm/page_alloc.c:4892
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd636)
Location: mm/page_alloc.c:5043
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c25c6)
Location: mm/page_alloc.c:5244
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305f96)
Location: mm/page_alloc.c:702
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136e046)
Location: mm/page_alloc.c:690
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:free_compound_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ea3c8)
Location: mm/page_alloc.c:747
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:free_compound_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141f36b)
Location: mm/page_alloc.c:581
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:free_compound_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144c028)
Location: mm/page_alloc.c:560
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:destroy_large_folio
  - mm/page_alloc.c:destroy_large_folio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103172b0)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05319a0)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e961c)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021fd7a)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:init_cma_reserved_pageblock
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277c56)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269b66)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812759f6)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812855b6)
Location: mm/page_alloc.c:4789
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
</details>
</li>
</ul>

## Differences
