# Function: <code>remove_pmd_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181c2d3)
Location: arch/x86/mm/init_64.c:863
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8189649e)
Location: arch/x86/mm/init_64.c:811
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818cabaf)
Location: arch/x86/mm/init_64.c:801
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819020c3)
Location: arch/x86/mm/init_64.c:947
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198c0bb)
Location: arch/x86/mm/init_64.c:955
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e8a47)
Location: arch/x86/mm/init_64.c:969
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a242d0)
Location: arch/x86/mm/init_64.c:962
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a9440b)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81a9440b-ffffffff81a9479b: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acbceb)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81acbceb-ffffffff81acc07b: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3cdc)
Location: arch/x86/mm/init_64.c:1037
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff81bc3cdc-ffffffff81bc3ec0: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3cbf0)
Location: arch/x86/mm/init_64.c:1031
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff81c3cbf0-ffffffff81c3cdd8: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2eed8)
Location: arch/x86/mm/init_64.c:1101
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff81c2eed8-ffffffff81c2f185: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d5d9)
Location: arch/x86/mm/init_64.c:1102
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff81d4d5d9-ffffffff81d4d886: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d2f9)
Location: arch/x86/mm/init_64.c:1102
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff81f1d2f9-ffffffff81f1d5b9: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5650)
Location: arch/x86/mm/init_64.c:1103
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff820c5650-ffffffff820c5b23: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff821496c0)
Location: arch/x86/mm/init_64.c:1103
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff821496c0-ffffffff82149b93: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222c180)
Location: arch/x86/mm/init_64.c:1103
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
**Symbols:**

```
ffffffff8222c180-ffffffff8222c649: remove_pmd_table (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebdb8)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:790
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
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
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6ab5b)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81a6ab5b-ffffffff81a6aeeb: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a26f56)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81a26f56-ffffffff81a273f3: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad6f6b)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81ad6f6b-ffffffff81ad72fb: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t *pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae342b)
Location: arch/x86/mm/init_64.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81ae342b-ffffffff81ae37bb: remove_pmd_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
