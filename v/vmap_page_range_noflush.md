# Function: <code>vmap_page_range_noflush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cdea0)
Location: mm/vmalloc.c:185
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:map_kernel_range_noflush
```
**Symbols:**

```
ffffffff811cdea0-ffffffff811ce1e8: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811eaa30)
Location: mm/vmalloc.c:186
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811eaa30-ffffffff811ead81: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fbcb0)
Location: mm/vmalloc.c:186
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811fbcb0-ffffffff811fbfe1: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812069b0)
Location: mm/vmalloc.c:219
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812069b0-ffffffff81206cc5: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f9f0)
Location: mm/vmalloc.c:217
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8121f9f0-ffffffff8121fd4f: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81240a70)
Location: mm/vmalloc.c:217
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81240a70-ffffffff81240dd1: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255360)
Location: mm/vmalloc.c:217
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81255360-ffffffff8125569c: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812679f0)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812676b0-ffffffff812679f7: vmap_page_range_noflush (STB_LOCAL)
ffffffff8126bb00-ffffffff8126bb26: vmap_page_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81276010)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81276010-ffffffff8127634e: vmap_page_range_noflush (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030c1f0)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffff80001030c1f0-ffff80001030c494: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c05283e8)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c05283e8-c05285f0: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dc2a0)
Location: mm/vmalloc.c:220
Inline: False
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c0000000003dc2a0-c0000000003dc7dc: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215798)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffe000215798-ffffffe000215954: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e660)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8126e660-ffffffff8126e99e: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260750)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81260750-ffffffff81260a6e: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126c400)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8126c400-ffffffff8126c73e: vmap_page_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vmap_page_range_noflush(long unsigned int start, long unsigned int end, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127bf40)
Location: mm/vmalloc.c:220
Inline: True
Direct callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8127bf40-ffffffff8127c27e: vmap_page_range_noflush (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
