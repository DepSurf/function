# Function: <code>vmem_altmap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e5e0)
Location: kernel/memremap.c:396
Inline: False
```
**Symbols:**

```
ffffffff8119e5e0-ffffffff8119e5ef: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811ae010)
Location: kernel/memremap.c:406
Inline: False
```
**Symbols:**

```
ffffffff811ae010-ffffffff811ae01f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b5490)
Location: kernel/memremap.c:402
Inline: False
```
**Symbols:**

```
ffffffff811b5490-ffffffff811b549f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c9580)
Location: kernel/memremap.c:474
Inline: False
```
**Symbols:**

```
ffffffff811c9580-ffffffff811c958f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9b90)
Location: kernel/memremap.c:284
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff811e9b90-ffffffff811e9b9f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa700)
Location: kernel/memremap.c:275
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff811fa700-ffffffff811fa70f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2d90)
Location: mm/memremap.c:352
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812c2d90-ffffffff812c2d9f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4c40)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812d4c40-ffffffff812d4c4f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130aa10)
Location: mm/memremap.c:407
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff8130aa10-ffffffff8130aa1f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813168f0)
Location: mm/memremap.c:456
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff813168f0-ffffffff813168ff: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131cb40)
Location: mm/memremap.c:462
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff8131cb40-ffffffff8131cb4f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369e90)
Location: mm/memremap.c:459
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff81369e90-ffffffff81369e9f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e7bc0)
Location: mm/memremap.c:417
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff813e7bc0-ffffffff813e7bd7: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146f9e0)
Location: mm/memremap.c:433
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff8146f9e0-ffffffff8146f9f7: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a41c0)
Location: mm/memremap.c:433
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff814a41c0-ffffffff814a41d7: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222c531)
Location: include/linux/mm.h:3883
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046e5e0)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
c00000000046e5e0-c00000000046e5f8: vmem_altmap_free (STB_GLOBAL)
```
</details>
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
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cd220)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812cd220-ffffffff812cd22f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812be090)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812be090-ffffffff812be09f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cb030)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812cb030-ffffffff812cb03f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmem_altmap_free(struct vmem_altmap *altmap, long unsigned int nr_pfns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812dbd90)
Location: mm/memremap.c:374
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff812dbd90-ffffffff812dbd9f: vmem_altmap_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
