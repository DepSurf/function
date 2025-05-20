# Function: <code>vmemmap_pud_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8181f3b0)
Location: mm/sparse-vmemmap.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8181f3b0-ffffffff8181f47c: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81899a7b)
Location: mm/sparse-vmemmap.c:199
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81899a7b-ffffffff81899b5c: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818ce12d)
Location: mm/sparse-vmemmap.c:199
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff818ce12d-ffffffff818ce20e: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819055c2)
Location: mm/sparse-vmemmap.c:199
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff819055c2-ffffffff819056a3: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f619)
Location: mm/sparse-vmemmap.c:213
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8198f619-ffffffff8198f70d: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819ebea9)
Location: mm/sparse-vmemmap.c:191
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff819ebea9-ffffffff819ebf85: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a27117)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a27117-ffffffff81a271f3: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a979bb)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a979bb-ffffffff81a97a9e: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81acf289)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81acf289-ffffffff81acf36c: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc7c46)
Location: mm/sparse-vmemmap.c:179
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81bc7c46-ffffffff81bc7d27: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c40971)
Location: mm/sparse-vmemmap.c:183
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c40971-ffffffff81c40a52: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c3294f)
Location: mm/sparse-vmemmap.c:183
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c3294f-ffffffff81c329b1: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d5135d)
Location: mm/sparse-vmemmap.c:537
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81d5135d-ffffffff81d513bf: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f215f0)
Location: mm/sparse-vmemmap.c:598
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff81f215f0-ffffffff81f21649: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cb6f0)
Location: mm/sparse-vmemmap.c:203
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff820cb6f0-ffffffff820cb790: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214f980)
Location: mm/sparse-vmemmap.c:203
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff8214f980-ffffffff8214fa20: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82232840)
Location: mm/sparse-vmemmap.c:203
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff82232840-ffffffff822328e0: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(pgd_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da0eb8)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffff800010da0eb8-ffff800010da0f50: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(pgd_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eedd4c)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
c000000000eedd4c-c000000000eede28: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe000049076)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffe000049076-ffffffe0000490cc: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6e0f9)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a6e0f9-ffffffff81a6e1dc: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a5a5)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a2a5a5-ffffffff81a2a623: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada509)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ada509-ffffffff81ada5ec: vmemmap_pud_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pud_t *vmemmap_pud_populate(p4d_t *p4d, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae69bf)
Location: mm/sparse-vmemmap.c:180
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ae69bf-ffffffff81ae6aa2: vmemmap_pud_populate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>p4d_t *p4d</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t *pgd</code>
</li>
</ul>
</details>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
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
