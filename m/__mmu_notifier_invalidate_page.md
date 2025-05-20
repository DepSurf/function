# Function: <code>__mmu_notifier_invalidate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_page(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e4110)
Location: mm/mmu_notifier.c:176
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff811e4110-ffffffff811e417d: __mmu_notifier_invalidate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_page(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202ba0)
Location: mm/mmu_notifier.c:176
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
**Symbols:**

```
ffffffff81202ba0-ffffffff81202c0d: __mmu_notifier_invalidate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_page(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812149e0)
Location: mm/mmu_notifier.c:176
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
**Symbols:**

```
ffffffff812149e0-ffffffff81214a4d: __mmu_notifier_invalidate_page (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
