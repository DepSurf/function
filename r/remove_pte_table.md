# Function: <code>remove_pte_table</code>

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
In arch/x86/mm/init_64.c (ffffffff8181c47d)
Location: arch/x86/mm/init_64.c:791
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
In arch/x86/mm/init_64.c (ffffffff81896633)
Location: arch/x86/mm/init_64.c:740
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
In arch/x86/mm/init_64.c (ffffffff818cad38)
Location: arch/x86/mm/init_64.c:730
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
In arch/x86/mm/init_64.c (ffffffff81902242)
Location: arch/x86/mm/init_64.c:876
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
In arch/x86/mm/init_64.c (ffffffff8198c216)
Location: arch/x86/mm/init_64.c:884
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
In arch/x86/mm/init_64.c (ffffffff819e8be7)
Location: arch/x86/mm/init_64.c:898
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
In arch/x86/mm/init_64.c (ffffffff81a24470)
Location: arch/x86/mm/init_64.c:891
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
In arch/x86/mm/init_64.c (ffffffff81a945c3)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81acbea3)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_pte_table(pte_t *pte_start, long unsigned int addr, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3ae2)
Location: arch/x86/mm/init_64.c:966
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81bc3ae2-ffffffff81bc3c63: remove_pte_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_pte_table(pte_t *pte_start, long unsigned int addr, long unsigned int end, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3c9fc)
Location: arch/x86/mm/init_64.c:960
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81c3c9fc-ffffffff81c3cb7f: remove_pte_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f03b)
Location: arch/x86/mm/init_64.c:1058
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d73c)
Location: arch/x86/mm/init_64.c:1059
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d458)
Location: arch/x86/mm/init_64.c:1059
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5790)
Location: arch/x86/mm/init_64.c:1060
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82149800)
Location: arch/x86/mm/init_64.c:1060
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff8222c2c0)
Location: arch/x86/mm/init_64.c:1060
Inline: True
Inline callers:
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebe70)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:716
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
In arch/x86/mm/init_64.c (ffffffff81a6ad13)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81a2718d)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81ad7123)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81ae35e3)
Location: arch/x86/mm/init_64.c:958
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
