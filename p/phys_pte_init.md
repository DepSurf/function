# Function: <code>phys_pte_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int addr, long unsigned int end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181ba1a)
Location: arch/x86/mm/init_64.c:402
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff8181ba1a-ffffffff8181bb2c: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81895c1a)
Location: arch/x86/mm/init_64.c:335
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81895c1a-ffffffff81895d26: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818ca33a)
Location: arch/x86/mm/init_64.c:325
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff818ca33a-ffffffff818ca446: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819018b8)
Location: arch/x86/mm/init_64.c:406
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff819018b8-ffffffff819019c5: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198b8e8)
Location: arch/x86/mm/init_64.c:406
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff8198b8e8-ffffffff8198b9f5: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e81fa)
Location: arch/x86/mm/init_64.c:417
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff819e81fa-ffffffff819e8307: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a237aa)
Location: arch/x86/mm/init_64.c:416
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81a237aa-ffffffff81a238f7: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a93b12)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81a93b12-ffffffff81a93c25: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acb3f2)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81acb3f2-ffffffff81acb505: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc38fa)
Location: arch/x86/mm/init_64.c:453
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81bc38fa-ffffffff81bc3a0b: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3c82a)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81c3c82a-ffffffff81c3c93b: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2eccc)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81c2eccc-ffffffff81c2eddd: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d3cd)
Location: arch/x86/mm/init_64.c:449
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81d4d3cd-ffffffff81d4d4de: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d0aa)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81f1d0aa-ffffffff81f1d1d2: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5480)
Location: arch/x86/mm/init_64.c:454
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff820c5480-ffffffff820c563a: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff821494e0)
Location: arch/x86/mm/init_64.c:454
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff821494e0-ffffffff821496a3: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222bfa0)
Location: arch/x86/mm/init_64.c:454
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff8222bfa0-ffffffff8222c163: phys_pte_init (STB_LOCAL)
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
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6a262)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81a6a262-ffffffff81a6a375: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a26732)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81a26732-ffffffff81a26837: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad6672)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81ad6672-ffffffff81ad6785: phys_pte_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int phys_pte_init(pte_t *pte_page, long unsigned int paddr, long unsigned int paddr_end, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae2b32)
Location: arch/x86/mm/init_64.c:448
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
**Symbols:**

```
ffffffff81ae2b32-ffffffff81ae2c45: phys_pte_init (STB_LOCAL)
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
