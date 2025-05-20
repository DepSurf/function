# Function: <code>vmemmap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81818ce0)
Location: arch/x86/mm/init_64.c:1002
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_remove_one_section
```
**Symbols:**

```
ffffffff81818ce0-ffffffff81818cf2: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818927c0)
Location: arch/x86/mm/init_64.c:944
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff818927c0-ffffffff818927d2: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818c7110)
Location: arch/x86/mm/init_64.c:934
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff818c7110-ffffffff818c7122: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818fe880)
Location: arch/x86/mm/init_64.c:1112
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff818fe880-ffffffff818fe892: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819889b0)
Location: arch/x86/mm/init_64.c:1120
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff819889b0-ffffffff819889c2: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e52ff)
Location: arch/x86/mm/init_64.c:1135
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff819e52ff-ffffffff819e5314: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a20522)
Location: arch/x86/mm/init_64.c:1128
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_add_one_section
```
**Symbols:**

```
ffffffff81a20522-ffffffff81a20537: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a90ada)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81a90ada-ffffffff81a90aef: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ac7e5a)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81ac7e5a-ffffffff81ac7e6f: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc094e)
Location: arch/x86/mm/init_64.c:1203
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81bc094e-ffffffff81bc0963: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c399e0)
Location: arch/x86/mm/init_64.c:1197
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81c399e0-ffffffff81c399f5: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2be70)
Location: arch/x86/mm/init_64.c:1239
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81c2be70-ffffffff81c2be85: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4a5fd)
Location: arch/x86/mm/init_64.c:1240
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81d4a5fd-ffffffff81d4a612: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f19c69)
Location: arch/x86/mm/init_64.c:1240
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81f19c69-ffffffff81f19c8a: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c18b0)
Location: arch/x86/mm/init_64.c:1241
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff820c18b0-ffffffff820c18d1: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82145580)
Location: arch/x86/mm/init_64.c:1241
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff82145580-ffffffff821455a1: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82227ca0)
Location: arch/x86/mm/init_64.c:1241
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff82227ca0-ffffffff82227cc1: vmemmap_free (STB_GLOBAL)
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
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae598)
Location: arch/arm64/mm/mmu.c:772
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffff8000100ae598-ffff8000100ae5b0: vmemmap_free (STB_GLOBAL)
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
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/init_64.c (c000000000088bb0)
Location: arch/powerpc/mm/init_64.c:271
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
c000000000088bb0-c000000000088ec8: vmemmap_free (STB_GLOBAL)
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
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a66cca)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81a66cca-ffffffff81a66cdf: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a2378a)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81a2378a-ffffffff81a2379f: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad30da)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81ad30da-ffffffff81ad30ef: vmemmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmemmap_free(long unsigned int start, long unsigned int end, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81adf5da)
Location: arch/x86/mm/init_64.c:1195
Inline: False
Direct callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
**Symbols:**

```
ffffffff81adf5da-ffffffff81adf5ef: vmemmap_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
