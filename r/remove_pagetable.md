# Function: <code>remove_pagetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181c05b)
Location: arch/x86/mm/init_64.c:975
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_free
  - arch/x86/mm/init_64.c:arch_remove_memory
```
**Symbols:**

```
ffffffff8181c05b-ffffffff8181c83e: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8189626a)
Location: arch/x86/mm/init_64.c:923
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff8189626a-ffffffff81896955: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818ca987)
Location: arch/x86/mm/init_64.c:913
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff818ca987-ffffffff818cb042: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8190253c)
Location: arch/x86/mm/init_64.c:1091
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff8190253c-ffffffff81902610: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198c4b0)
Location: arch/x86/mm/init_64.c:1099
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff8198c4b0-ffffffff8198c58d: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e884d)
Location: arch/x86/mm/init_64.c:1113
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff819e884d-ffffffff819e8e7b: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a240d6)
Location: arch/x86/mm/init_64.c:1106
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81a240d6-ffffffff81a24704: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a9479b)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81a9479b-ffffffff81a94a4d: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc07b)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81acc07b-ffffffff81acc32d: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc43ae)
Location: arch/x86/mm/init_64.c:1181
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81bc43ae-ffffffff81bc4454: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3d2a7)
Location: arch/x86/mm/init_64.c:1175
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81c3d2a7-ffffffff81c3d34d: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f6b5)
Location: arch/x86/mm/init_64.c:1217
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81c2f6b5-ffffffff81c2f75b: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4ddb6)
Location: arch/x86/mm/init_64.c:1218
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81d4ddb6-ffffffff81d4deaa: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1db48)
Location: arch/x86/mm/init_64.c:1218
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81f1db48-ffffffff81f1dc4a: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5f80)
Location: arch/x86/mm/init_64.c:1219
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff820c5f80-ffffffff820c60dc: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82149fe0)
Location: arch/x86/mm/init_64.c:1219
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff82149fe0-ffffffff8214a13c: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222ca90)
Location: arch/x86/mm/init_64.c:1219
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff8222ca90-ffffffff8222cbec: remove_pagetable (STB_LOCAL)
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
void remove_pagetable(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebb60)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:840
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__vmemmap_remove_mapping
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__remove_section_mapping
```
**Symbols:**

```
c000000000eebb60-c000000000eec0b0: remove_pagetable (STB_LOCAL)
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
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6aeeb)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81a6aeeb-ffffffff81a6b19d: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a273f3)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81a273f3-ffffffff81a27760: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad72fb)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81ad72fb-ffffffff81ad75ad: remove_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_pagetable(long unsigned int start, long unsigned int end, bool direct, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae37bb)
Location: arch/x86/mm/init_64.c:1173
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - arch/x86/mm/init_64.c:vmemmap_free
```
**Symbols:**

```
ffffffff81ae37bb-ffffffff81ae3a6d: remove_pagetable (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool direct</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
