# Function: <code>phys_pmd_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int address, long unsigned int end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181bbe0)
Location: arch/x86/mm/init_64.c:447
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff8181bbe0-ffffffff8181be24: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81895df5)
Location: arch/x86/mm/init_64.c:389
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81895df5-ffffffff81896031: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818ca512)
Location: arch/x86/mm/init_64.c:379
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff818ca512-ffffffff818ca74e: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81901a8c)
Location: arch/x86/mm/init_64.c:460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81901a8c-ffffffff81901cc7: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198babc)
Location: arch/x86/mm/init_64.c:460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff8198babc-ffffffff8198bcf0: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e83ab)
Location: arch/x86/mm/init_64.c:471
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff819e83ab-ffffffff819e85f2: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a2399b)
Location: arch/x86/mm/init_64.c:470
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81a2399b-ffffffff81a23d2d: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a93cc9)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81a93cc9-ffffffff81a9406d: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acb5a9)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81acb5a9-ffffffff81acb94d: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc4454)
Location: arch/x86/mm/init_64.c:507
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81bc4454-ffffffff81bc4804: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3d34d)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81c3d34d-ffffffff81c3d6fd: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f75b)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81c2f75b-ffffffff81c2faa2: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4deaa)
Location: arch/x86/mm/init_64.c:503
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81d4deaa-ffffffff81d4e1f1: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1dc4a)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81f1dc4a-ffffffff81f1dfae: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c60f0)
Location: arch/x86/mm/init_64.c:508
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff820c60f0-ffffffff820c65dd: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214a150)
Location: arch/x86/mm/init_64.c:508
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff8214a150-ffffffff8214a63d: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222cc00)
Location: arch/x86/mm/init_64.c:508
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff8222cc00-ffffffff8222d0ed: phys_pmd_init (STB_LOCAL)
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
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6a419)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81a6a419-ffffffff81a6a7bd: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a268db)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81a268db-ffffffff81a26c1c: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad6829)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81ad6829-ffffffff81ad6bcd: phys_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int phys_pmd_init(pmd_t *pmd_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae2ce9)
Location: arch/x86/mm/init_64.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
**Symbols:**

```
ffffffff81ae2ce9-ffffffff81ae308d: phys_pmd_init (STB_LOCAL)
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
<code>long unsigned int address</code>
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
