# Function: <code>hugetlb_vma_lock_alloc</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d164)
Location: mm/hugetlb.c:372
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_open
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_open
```
**Symbols:**

```
ffffffff814064d0-ffffffff81406561: hugetlb_vma_lock_alloc.part.0 (STB_LOCAL)
ffffffff82066108-ffffffff8206611c: hugetlb_vma_lock_alloc.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_vma_lock_alloc(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81439be9)
Location: mm/hugetlb.c:366
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:hugetlb_vm_op_open
```
**Symbols:**

```
ffffffff81439bb0-ffffffff81439c7f: hugetlb_vma_lock_alloc (STB_LOCAL)
ffffffff820e5852-ffffffff820e5866: hugetlb_vma_lock_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8147a634)
Location: mm/hugetlb.c:399
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_open
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_open
```
**Symbols:**

```
ffffffff81473600-ffffffff814736c0: hugetlb_vma_lock_alloc.part.0 (STB_LOCAL)
ffffffff821c2a3b-ffffffff821c2a4f: hugetlb_vma_lock_alloc.part.0.cold (STB_LOCAL)
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
</ul>
