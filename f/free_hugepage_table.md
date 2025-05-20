# Function: <code>free_hugepage_table</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e8af1)
Location: arch/x86/mm/init_64.c:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81a2437a)
Location: arch/x86/mm/init_64.c:827
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81a944d8)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81acbdb8)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_hugepage_table(struct page *page, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3aad)
Location: arch/x86/mm/init_64.c:902
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81bc3aad-ffffffff81bc3ae2: free_hugepage_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_hugepage_table(struct page *page, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3c9d8)
Location: arch/x86/mm/init_64.c:896
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81c3c9d8-ffffffff81c3c9fc: free_hugepage_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_hugepage_table(struct page *page, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2eeb4)
Location: arch/x86/mm/init_64.c:994
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81c2eeb4-ffffffff81c2eed8: free_hugepage_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_hugepage_table(struct page *page, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d5b5)
Location: arch/x86/mm/init_64.c:995
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81d4d5b5-ffffffff81d4d5d9: free_hugepage_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_hugepage_table(struct page *page, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d2cb)
Location: arch/x86/mm/init_64.c:995
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff81f1d2cb-ffffffff81f1d2f9: free_hugepage_table (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff820c59f8)
Location: arch/x86/mm/init_64.c:996
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff82149a68)
Location: arch/x86/mm/init_64.c:996
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff8222c528)
Location: arch/x86/mm/init_64.c:996
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6ac28)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81a27045)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81ad7038)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
In arch/x86/mm/init_64.c (ffffffff81ae34f8)
Location: arch/x86/mm/init_64.c:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
