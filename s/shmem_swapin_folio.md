# Function: <code>shmem_swapin_folio</code>

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
int shmem_swapin_folio(struct inode *inode, long unsigned int index, struct folio **foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81318530)
Location: mm/shmem.c:1714
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81318530-ffffffff81318979: shmem_swapin_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_swapin_folio(struct inode *inode, long unsigned int index, struct folio **foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138c430)
Location: mm/shmem.c:1728
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff8138c430-ffffffff8138c827: shmem_swapin_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_swapin_folio(struct inode *inode, long unsigned int index, struct folio **foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bea30)
Location: mm/shmem.c:1740
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff813bea30-ffffffff813beedb: shmem_swapin_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_swapin_folio(struct inode *inode, long unsigned int index, struct folio **foliop, enum sgp_type sgp, gfp_t gfp, struct mm_struct *fault_mm, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e9a50)
Location: mm/shmem.c:1848
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff813e9a50-ffffffff813e9f26: shmem_swapin_folio (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *fault_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
</ul>
</details>
</li>
</ul>
