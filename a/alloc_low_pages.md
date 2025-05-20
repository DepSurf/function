# Function: <code>alloc_low_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81818720)
Location: arch/x86/mm/init.c:83
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81818720-ffffffff8181885e: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81892260)
Location: arch/x86/mm/init.c:84
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81892260-ffffffff81892390: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff818c6b80)
Location: arch/x86/mm/init.c:84
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff818c6b80-ffffffff818c6cb0: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff818fe2e0)
Location: arch/x86/mm/init.c:85
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff818fe2e0-ffffffff818fe410: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81988410)
Location: arch/x86/mm/init.c:87
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81988410-ffffffff81988540: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff819e4dd0)
Location: arch/x86/mm/init.c:89
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff819e4dd0-ffffffff819e4f0a: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81a1ff90)
Location: arch/x86/mm/init.c:88
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81a1ff90-ffffffff81a20128: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81a90720)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81a90720-ffffffff81a908b5: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81ac7aa0)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81ac7aa0-ffffffff81ac7c35: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81bc05a0)
Location: arch/x86/mm/init.c:113
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff81bc05a0-ffffffff81bc071d: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81c39620)
Location: arch/x86/mm/init.c:114
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff81c39620-ffffffff81c397a7: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81c2bac0)
Location: arch/x86/mm/init.c:114
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff81c2bac0-ffffffff81c2bc41: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81d4a1b0)
Location: arch/x86/mm/init.c:114
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff81d4a1b0-ffffffff81d4a358: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81f197c0)
Location: arch/x86/mm/init.c:123
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff81f197c0-ffffffff81f19980: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff820c1390)
Location: arch/x86/mm/init.c:124
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff820c1390-ffffffff820c1550: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff82145060)
Location: arch/x86/mm/init.c:125
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff82145060-ffffffff82145220: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff82227780)
Location: arch/x86/mm/init.c:124
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
**Symbols:**

```
ffffffff82227780-ffffffff82227940: alloc_low_pages (STB_GLOBAL)
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
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81a66910)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81a66910-ffffffff81a66aa5: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81a233d0)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81a233d0-ffffffff81a23565: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81ad2d20)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81ad2d20-ffffffff81ad2eb5: alloc_low_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *alloc_low_pages(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81adf220)
Location: arch/x86/mm/init.c:91
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/kaslr.c:init_trampoline
```
**Symbols:**

```
ffffffff81adf220-ffffffff81adf3b5: alloc_low_pages (STB_GLOBAL)
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
