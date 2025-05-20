# Function: <code>restore_exclusive_pte</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void restore_exclusive_pte(struct vm_area_struct *vma, struct page *page, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812de900)
Location: mm/memory.c:702
Inline: False
Direct callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_nonpresent_pte
```
**Symbols:**

```
ffffffff812de900-ffffffff812dea2c: restore_exclusive_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void restore_exclusive_pte(struct vm_area_struct *vma, struct page *page, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133eb90)
Location: mm/memory.c:709
Inline: False
Direct callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_nonpresent_pte
```
**Symbols:**

```
ffffffff8133eb90-ffffffff8133ecea: restore_exclusive_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void restore_exclusive_pte(struct vm_area_struct *vma, struct page *page, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b5e70)
Location: mm/memory.c:670
Inline: False
Direct callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_nonpresent_pte
```
**Symbols:**

```
ffffffff813b5e70-ffffffff813b5fb3: restore_exclusive_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void restore_exclusive_pte(struct vm_area_struct *vma, struct page *page, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ea6e0)
Location: mm/memory.c:699
Inline: False
Direct callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_nonpresent_pte
```
**Symbols:**

```
ffffffff813ea6e0-ffffffff813ea85b: restore_exclusive_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void restore_exclusive_pte(struct vm_area_struct *vma, struct page *page, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff814168d0)
Location: mm/memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_nonpresent_pte
```
**Symbols:**

```
ffffffff814168d0-ffffffff81416ad6: restore_exclusive_pte (STB_LOCAL)
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
