# Function: <code>pmd_install</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmd_install(struct mm_struct *mm, pmd_t *pmd, pgtable_t *pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133f850)
Location: mm/memory.c:440
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
**Symbols:**

```
ffffffff8133f850-ffffffff8133f940: pmd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmd_install(struct mm_struct *mm, pmd_t *pmd, pgtable_t *pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b7780)
Location: mm/memory.c:393
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
**Symbols:**

```
ffffffff813b7780-ffffffff813b7870: pmd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmd_install(struct mm_struct *mm, pmd_t *pmd, pgtable_t *pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ec520)
Location: mm/memory.c:412
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
**Symbols:**

```
ffffffff813ec520-ffffffff813ec613: pmd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pmd_install(struct mm_struct *mm, pmd_t *pmd, pgtable_t *pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417d60)
Location: mm/memory.c:412
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
**Symbols:**

```
ffffffff81417d60-ffffffff81417e53: pmd_install (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
