# Function: <code>get_next_vma</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool get_next_vma(long unsigned int mask, long unsigned int size, struct mm_walk *args, long unsigned int *vm_start, long unsigned int *vm_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81377550)
Location: mm/vmscan.c:3820
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pte_range
```
**Symbols:**

```
ffffffff81377550-ffffffff81377660: get_next_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool get_next_vma(long unsigned int mask, long unsigned int size, struct mm_walk *args, long unsigned int *vm_start, long unsigned int *vm_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a9440)
Location: mm/vmscan.c:3908
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pte_range
```
**Symbols:**

```
ffffffff813a9440-ffffffff813a9554: get_next_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool get_next_vma(long unsigned int mask, long unsigned int size, struct mm_walk *args, long unsigned int *vm_start, long unsigned int *vm_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d2e40)
Location: mm/vmscan.c:3229
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pte_range
```
**Symbols:**

```
ffffffff813d2e40-ffffffff813d2f53: get_next_vma (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
