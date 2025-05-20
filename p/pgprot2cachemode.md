# Function: <code>pgprot2cachemode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bd89)
Location: arch/x86/include/asm/pgtable_types.h:355
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e344)
Location: arch/x86/include/asm/pgtable_types.h:355
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff810706a1)
Location: arch/x86/include/asm/pgtable_types.h:355
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bc36)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e10a)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81070431)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f856)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81071d7a)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff810740c1)
Location: arch/x86/include/asm/pgtable_types.h:393
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106ef89)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81071446)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81073641)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81074079)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81076bc3)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81079001)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076a90)
Location: arch/x86/include/asm/pgtable_types.h:454
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff810796c8)
Location: arch/x86/include/asm/pgtable_types.h:454
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff8107b9d1)
Location: arch/x86/include/asm/pgtable_types.h:454
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d120)
Location: arch/x86/include/asm/pgtable_types.h:478
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff8108001d)
Location: arch/x86/include/asm/pgtable_types.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81082341)
Location: arch/x86/include/asm/pgtable_types.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8108086d)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81083ab6)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81085fc1)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081a6d)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81084b86)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81086cb1)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810842c0)
Location: arch/x86/mm/init.c:86
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff810842c0-ffffffff810842ef: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81085810)
Location: arch/x86/mm/init.c:87
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81085810-ffffffff8108583f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81086510)
Location: arch/x86/mm/init.c:87
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81086510-ffffffff8108653f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81095720)
Location: arch/x86/mm/init.c:87
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81095720-ffffffff8109574f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810a78e0)
Location: arch/x86/mm/init.c:96
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff810a78e0-ffffffff810a791f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c0d00)
Location: arch/x86/mm/init.c:97
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff810c0d00-ffffffff810c0d3f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c43e0)
Location: arch/x86/mm/init.c:98
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff810c43e0-ffffffff810c441f: pgprot2cachemode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum page_cache_mode pgprot2cachemode(pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810cc830)
Location: arch/x86/mm/init.c:97
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff810cc830-ffffffff810cc86f: pgprot2cachemode (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a6d)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81083b86)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81085cb1)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f9bd)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff810727d6)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81074a31)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a1d)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81083b36)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81085c61)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082b3d)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
```
```
In arch/x86/mm/pageattr.c (ffffffff81085c76)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pat.c (ffffffff81087db1)
Location: arch/x86/include/asm/pgtable_types.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
