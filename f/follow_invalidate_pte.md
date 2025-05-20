# Function: <code>follow_invalidate_pte</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int follow_invalidate_pte(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f930)
Location: mm/memory.c:4721
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8129f930-ffffffff8129fd82: follow_invalidate_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int follow_invalidate_pte(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a51a0)
Location: mm/memory.c:4748
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812a51a0-ffffffff812a55e7: follow_invalidate_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int follow_invalidate_pte(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4894
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81cbc61a-ffffffff81cbc633: follow_invalidate_pte.cold (STB_LOCAL)
ffffffff812e6720-ffffffff812e6ad6: follow_invalidate_pte (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
