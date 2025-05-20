# Function: <code>remove_pud_table</code>

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
In arch/x86/mm/init_64.c (ffffffff8181c106)
Location: arch/x86/mm/init_64.c:919
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
In arch/x86/mm/init_64.c (ffffffff818962fa)
Location: arch/x86/mm/init_64.c:867
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
In arch/x86/mm/init_64.c (ffffffff818caa17)
Location: arch/x86/mm/init_64.c:857
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81901f0a)
Location: arch/x86/mm/init_64.c:1003
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81901f0a-ffffffff8190253c: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198bf38)
Location: arch/x86/mm/init_64.c:1011
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff8198bf38-ffffffff8198c4b0: remove_pud_table (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff819e88e3)
Location: arch/x86/mm/init_64.c:1025
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
In arch/x86/mm/init_64.c (ffffffff81a2416c)
Location: arch/x86/mm/init_64.c:1018
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94847)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc127)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc40e0)
Location: arch/x86/mm/init_64.c:1093
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81bc40e0-ffffffff81bc42e1: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3cfeb)
Location: arch/x86/mm/init_64.c:1087
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81c3cfeb-ffffffff81c3d1da: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f419)
Location: arch/x86/mm/init_64.c:1150
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81c2f419-ffffffff81c2f580: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4db18)
Location: arch/x86/mm/init_64.c:1151
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81d4db18-ffffffff81d4dc7e: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d872)
Location: arch/x86/mm/init_64.c:1151
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81f1d872-ffffffff81f1d9f1: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5b40)
Location: arch/x86/mm/init_64.c:1152
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff820c5b40-ffffffff820c5da5: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82149bb0)
Location: arch/x86/mm/init_64.c:1152
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff82149bb0-ffffffff82149e0f: remove_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_pud_table(pud_t *pud_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222c660)
Location: arch/x86/mm/init_64.c:1152
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff8222c660-ffffffff8222c8bf: remove_pud_table (STB_LOCAL)
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebce8)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:815
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6af97)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a27494)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad73a7)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3867)
Location: arch/x86/mm/init_64.c:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
