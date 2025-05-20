# Function: <code>early_memremap_pgprot_adjust</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c35e1)
Location: arch/x86/mm/ioremap.c:671
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff826c35e1-ffffffff826c369c: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed848)
Location: arch/x86/mm/ioremap.c:671
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff826ed848-ffffffff826ed903: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a43da)
Location: arch/x86/mm/ioremap.c:679
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828a43da-ffffffff828a4495: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc8a2)
Location: arch/x86/mm/ioremap.c:704
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828bc8a2-ffffffff828bc964: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2d49)
Location: arch/x86/mm/ioremap.c:726
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828c2d49-ffffffff828c2e0b: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce6141)
Location: arch/x86/mm/ioremap.c:737
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff82ce6141-ffffffff82ce6203: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd3ac7)
Location: arch/x86/mm/ioremap.c:737
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff82fd3ac7-ffffffff82fd3b89: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de683)
Location: arch/x86/mm/ioremap.c:720
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff831de683-ffffffff831de742: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c195f)
Location: arch/x86/mm/ioremap.c:765
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff832c195f-ffffffff832c1ab8: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83474044)
Location: arch/x86/mm/ioremap.c:771
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff83474044-ffffffff834741b7: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9bd30)
Location: arch/x86/mm/ioremap.c:780
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
  - mm/early_ioremap.c:early_memremap_ro
```
**Symbols:**

```
ffffffff83e9bd30-ffffffff83e9bed4: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bf7d0)
Location: arch/x86/mm/ioremap.c:785
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
  - mm/early_ioremap.c:early_memremap_ro
```
**Symbols:**

```
ffffffff836bf7d0-ffffffff836bf974: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f0270)
Location: arch/x86/mm/ioremap.c:785
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
  - mm/early_ioremap.c:early_memremap_ro
```
**Symbols:**

```
ffffffff838f0270-ffffffff838f0414: early_memremap_pgprot_adjust (STB_GLOBAL)
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
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c4c0)
Location: mm/early_ioremap.c:34
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffff80001145c4c0-ffff80001145c4e8: early_memremap_pgprot_adjust (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (c15347fc)
Location: mm/early_ioremap.c:34
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
c15347fc-c1534818: early_memremap_pgprot_adjust (STB_WEAK)
```
</details>
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
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828add1f)
Location: arch/x86/mm/ioremap.c:726
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828add1f-ffffffff828adde1: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5f92)
Location: arch/x86/mm/ioremap.c:726
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828a5f92-ffffffff828a6054: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0c1e)
Location: arch/x86/mm/ioremap.c:726
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828c0c1e-ffffffff828c0ce0: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pgprot_t early_memremap_pgprot_adjust(resource_size_t phys_addr, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3d69)
Location: arch/x86/mm/ioremap.c:726
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
```
**Symbols:**

```
ffffffff828c3d69-ffffffff828c3e2b: early_memremap_pgprot_adjust (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
