# Function: <code>vmap_pages_pud_range</code>

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
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7bc0)
Location: mm/vmalloc.c:477
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff812b7bc0-ffffffff812b7ebd: vmap_pages_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fa2f0)
Location: mm/vmalloc.c:505
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff812fa2f0-ffffffff812fa5ee: vmap_pages_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813615e0)
Location: mm/vmalloc.c:506
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff813615e0-ffffffff81361a3e: vmap_pages_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dcf70)
Location: mm/vmalloc.c:518
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff813dcf70-ffffffff813dd3d1: vmap_pages_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814117e0)
Location: mm/vmalloc.c:507
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff814117e0-ffffffff81411c3f: vmap_pages_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, int *nr, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143dfd0)
Location: mm/vmalloc.c:507
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
**Symbols:**

```
ffffffff8143dfd0-ffffffff8143e497: vmap_pages_pud_range (STB_LOCAL)
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
