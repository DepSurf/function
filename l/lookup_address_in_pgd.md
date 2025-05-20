# Function: <code>lookup_address_in_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106d190)
Location: arch/x86/mm/pageattr.c:327
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8106d190-ffffffff8106d305: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106cfc0)
Location: arch/x86/mm/pageattr.c:333
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
**Symbols:**

```
ffffffff8106cfc0-ffffffff8106d116: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070c00)
Location: arch/x86/mm/pageattr.c:333
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
**Symbols:**

```
ffffffff81070c00-ffffffff81070d56: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070340)
Location: arch/x86/mm/pageattr.c:353
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
**Symbols:**

```
ffffffff81070340-ffffffff810704ae: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81075830)
Location: arch/x86/mm/pageattr.c:353
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
```
**Symbols:**

```
ffffffff81075830-ffffffff81075a17: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81078310)
Location: arch/x86/mm/pageattr.c:373
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
```
**Symbols:**

```
ffffffff81078310-ffffffff810784b1: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107eac0)
Location: arch/x86/mm/pageattr.c:557
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff8107eac0-ffffffff8107ec61: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810823a0)
Location: arch/x86/mm/pageattr.c:566
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff810823a0-ffffffff81082540: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083460)
Location: arch/x86/mm/pageattr.c:566
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81083460-ffffffff81083600: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d070)
Location: arch/x86/mm/pat/set_memory.c:575
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108d070-ffffffff8108d267: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cf40)
Location: arch/x86/mm/pat/set_memory.c:575
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108cf40-ffffffff8108d137: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108db30)
Location: arch/x86/mm/pat/set_memory.c:583
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108db30-ffffffff8108dce9: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d3e0)
Location: arch/x86/mm/pat/set_memory.c:583
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8109d3e0-ffffffff8109d599: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0cb0)
Location: arch/x86/mm/pat/set_memory.c:586
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810b0cb0-ffffffff810b0e74: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb3c0)
Location: arch/x86/mm/pat/set_memory.c:661
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810cb3c0-ffffffff810cb58e: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce9d0)
Location: arch/x86/mm/pat/set_memory.c:662
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810ce9d0-ffffffff810ceba8: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d70b0)
Location: arch/x86/mm/pat/set_memory.c:662
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810d70b0-ffffffff810d7288: lookup_address_in_pgd (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082460)
Location: arch/x86/mm/pageattr.c:566
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81082460-ffffffff81082600: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071250)
Location: arch/x86/mm/pageattr.c:566
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81071250-ffffffff810713a6: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082410)
Location: arch/x86/mm/pageattr.c:566
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81082410-ffffffff810825b0: lookup_address_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address_in_pgd(pgd_t *pgd, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084530)
Location: arch/x86/mm/pageattr.c:566
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81084530-ffffffff810846d0: lookup_address_in_pgd (STB_GLOBAL)
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
