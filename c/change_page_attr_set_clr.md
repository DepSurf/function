# Function: <code>change_page_attr_set_clr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e1d0)
Location: arch/x86/mm/pageattr.c:1365
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_rw
```
**Symbols:**

```
ffffffff8106e1d0-ffffffff8106e6bd: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106df90)
Location: arch/x86/mm/pageattr.c:1373
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff8106df90-ffffffff8106e4a0: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071c00)
Location: arch/x86/mm/pageattr.c:1373
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81071c00-ffffffff81072146: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810712e0)
Location: arch/x86/mm/pageattr.c:1419
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff810712e0-ffffffff8107179f: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81076a60)
Location: arch/x86/mm/pageattr.c:1419
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81076a60-ffffffff81076e37: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079560)
Location: arch/x86/mm/pageattr.c:1446
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81079560-ffffffff810798b0: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107fed0)
Location: arch/x86/mm/pageattr.c:1653
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff8107fed0-ffffffff810800b7: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083960)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81083960-ffffffff81083b54: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084a30)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81084a30-ffffffff81084c24: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e640)
Location: arch/x86/mm/pat/set_memory.c:1687
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_np
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff8108e640-ffffffff8108e7f1: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e410)
Location: arch/x86/mm/pat/set_memory.c:1687
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_np
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff8108e410-ffffffff8108e5c1: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108efd0)
Location: arch/x86/mm/pat/set_memory.c:1695
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_np
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff8108efd0-ffffffff8108f17e: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ea80)
Location: arch/x86/mm/pat/set_memory.c:1695
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_np
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff8109ea80-ffffffff8109ec2e: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2480)
Location: arch/x86/mm/pat/set_memory.c:1687
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:clear_mce_nospec
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff810b2480-ffffffff810b2651: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ccde0)
Location: arch/x86/mm/pat/set_memory.c:1792
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_rox
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:clear_mce_nospec
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff810ccde0-ffffffff810ccf8a: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0410)
Location: arch/x86/mm/pat/set_memory.c:1793
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_rox
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:clear_mce_nospec
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff810d0410-ffffffff810d05ba: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8af0)
Location: arch/x86/mm/pat/set_memory.c:1797
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:set_memory_global
  - arch/x86/mm/pat/set_memory.c:set_memory_nonglobal
  - arch/x86/mm/pat/set_memory.c:set_memory_4k
  - arch/x86/mm/pat/set_memory.c:set_memory_np_noalias
  - arch/x86/mm/pat/set_memory.c:set_memory_rox
  - arch/x86/mm/pat/set_memory.c:set_memory_nx
  - arch/x86/mm/pat/set_memory.c:set_memory_x
  - arch/x86/mm/pat/set_memory.c:clear_mce_nospec
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:__set_memory_prot
```
**Symbols:**

```
ffffffff810d8af0-ffffffff810d8c9a: change_page_attr_set_clr (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083a30)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81083a30-ffffffff81083c24: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072680)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81072680-ffffffff81072874: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810839e0)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff810839e0-ffffffff81083bd4: change_page_attr_set_clr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int *addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085b20)
Location: arch/x86/mm/pageattr.c:1664
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:set_memory_global
  - arch/x86/mm/pageattr.c:set_memory_nonglobal
  - arch/x86/mm/pageattr.c:set_memory_4k
  - arch/x86/mm/pageattr.c:set_memory_np_noalias
  - arch/x86/mm/pageattr.c:set_memory_np
  - arch/x86/mm/pageattr.c:set_memory_nx
  - arch/x86/mm/pageattr.c:set_memory_x
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
**Symbols:**

```
ffffffff81085b20-ffffffff81085d14: change_page_attr_set_clr (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
