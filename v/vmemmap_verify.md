# Function: <code>vmemmap_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8181f1b4)
Location: mm/sparse-vmemmap.c:90
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8181f1b4-ffffffff8181f209: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81899858)
Location: mm/sparse-vmemmap.c:162
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81899858-ffffffff818998ad: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818cdf0a)
Location: mm/sparse-vmemmap.c:162
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff818cdf0a-ffffffff818cdf5f: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8190539f)
Location: mm/sparse-vmemmap.c:162
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8190539f-ffffffff819053f4: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f3b6)
Location: mm/sparse-vmemmap.c:165
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8198f3b6-ffffffff8198f415: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819ebc1a)
Location: mm/sparse-vmemmap.c:143
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff819ebc1a-ffffffff819ebc8c: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a26e88)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a26e88-ffffffff81a26efa: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a9772e)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a9772e-ffffffff81a977a0: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81aceff5)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81aceff5-ffffffff81acf067: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc79b6)
Location: mm/sparse-vmemmap.c:131
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81bc79b6-ffffffff81bc7a2b: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c406ec)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c406ec-ffffffff81c40761: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c3275b)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c3275b-ffffffff81c327ca: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d511d8)
Location: mm/sparse-vmemmap.c:486
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81d511d8-ffffffff81d51223: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f21420)
Location: mm/sparse-vmemmap.c:532
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff81f21420-ffffffff81f21479: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cb350)
Location: mm/sparse-vmemmap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff820cb350-ffffffff820cb3f1: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214f5e0)
Location: mm/sparse-vmemmap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff8214f5e0-ffffffff8214f681: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff822324b0)
Location: mm/sparse-vmemmap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff822324b0-ffffffff82232551: vmemmap_verify (STB_GLOBAL)
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
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da0c74)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffff800010da0c74-ffff800010da0cd0: vmemmap_verify (STB_GLOBAL)
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
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eedad0)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
c000000000eedad0-c000000000eedb4c: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe000048f56)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffe000048f56-ffffffe000048f9e: vmemmap_verify (STB_GLOBAL)
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
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6de65)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a6de65-ffffffff81a6ded7: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a3ac)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a2a3ac-ffffffff81a2a417: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada275)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ada275-ffffffff81ada2e7: vmemmap_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmemmap_verify(pte_t *pte, int node, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae672b)
Location: mm/sparse-vmemmap.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ae672b-ffffffff81ae679d: vmemmap_verify (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
