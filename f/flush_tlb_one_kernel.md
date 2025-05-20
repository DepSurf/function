# Function: <code>flush_tlb_one_kernel</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b830)
Location: arch/x86/mm/tlb.c:1051
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff8108b830-ffffffff8108b84f: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b880)
Location: arch/x86/mm/tlb.c:987
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff8108b880-ffffffff8108b89f: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c490)
Location: arch/x86/mm/tlb.c:1031
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff8108c490-ffffffff8108c4af: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bcd0)
Location: arch/x86/mm/tlb.c:1090
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
```
**Symbols:**

```
ffffffff8109bcd0-ffffffff8109bcef: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af1d0)
Location: arch/x86/mm/tlb.c:1064
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
  - mm/kfence/core.c:kfence_protect_page
```
**Symbols:**

```
ffffffff810af1d0-ffffffff810af208: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c95c0)
Location: arch/x86/mm/tlb.c:1088
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
  - mm/kfence/core.c:kfence_protect_page
```
**Symbols:**

```
ffffffff810c95c0-ffffffff810c95f8: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccc40)
Location: arch/x86/mm/tlb.c:1109
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
  - mm/kfence/core.c:kfence_init_pool
```
**Symbols:**

```
ffffffff810ccc40-ffffffff810ccc78: flush_tlb_one_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d5300)
Location: arch/x86/mm/tlb.c:1111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff810d5300-ffffffff810d5338: flush_tlb_one_kernel (STB_GLOBAL)
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
