# Function: <code>phys_pud_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int addr, long unsigned int end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181be24)
Location: arch/x86/mm/init_64.c:522
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8181be24-ffffffff8181c05b: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81896031)
Location: arch/x86/mm/init_64.c:472
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81896031-ffffffff8189626a: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818ca74e)
Location: arch/x86/mm/init_64.c:462
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff818ca74e-ffffffff818ca987: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81901cc7)
Location: arch/x86/mm/init_64.c:543
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81901cc7-ffffffff81901f0a: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198bcf0)
Location: arch/x86/mm/init_64.c:543
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8198bcf0-ffffffff8198bf38: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e85f2)
Location: arch/x86/mm/init_64.c:554
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff819e85f2-ffffffff819e884d: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a23d2d)
Location: arch/x86/mm/init_64.c:553
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a23d2d-ffffffff81a240d6: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a9406d)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a9406d-ffffffff81a9440b: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acb94d)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81acb94d-ffffffff81acbceb: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc4804)
Location: arch/x86/mm/init_64.c:592
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81bc4804-ffffffff81bc4bbb: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3d6fd)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81c3d6fd-ffffffff81c3dab4: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2faa2)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81c2faa2-ffffffff81c2fdf8: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4e1f1)
Location: arch/x86/mm/init_64.c:588
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81d4e1f1-ffffffff81d4e547: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1dfae)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81f1dfae-ffffffff81f1e31f: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c65f0)
Location: arch/x86/mm/init_64.c:592
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff820c65f0-ffffffff820c6ad2: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214a650)
Location: arch/x86/mm/init_64.c:592
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff8214a650-ffffffff8214ab2c: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t _prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222d100)
Location: arch/x86/mm/init_64.c:592
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff8222d100-ffffffff8222d5dc: phys_pud_init (STB_LOCAL)
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
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6a7bd)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a6a7bd-ffffffff81a6ab5b: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a26c1c)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a26c1c-ffffffff81a26f56: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad6bcd)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81ad6bcd-ffffffff81ad6f6b: phys_pud_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int phys_pud_init(pud_t *pud_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae308d)
Location: arch/x86/mm/init_64.c:587
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81ae308d-ffffffff81ae342b: phys_pud_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int paddr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int paddr_end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool init</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t _prot</code>
</li>
<li>
<b>Param reordered. </b>
<code>pud_page, paddr, paddr_end, page_size_mask, init</code> ➡️ <code>pud_page, paddr, paddr_end, page_size_mask, _prot, init</code>
</li>
</ul>
</details>
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
