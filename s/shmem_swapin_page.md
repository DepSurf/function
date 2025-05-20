# Function: <code>shmem_swapin_page</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81233060)
Location: mm/shmem.c:1619
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81233060-ffffffff812336da: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81241280)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81241280-ffffffff812418d5: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126dad0)
Location: mm/shmem.c:1638
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff8126dad0-ffffffff8126de6b: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81279810)
Location: mm/shmem.c:1693
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81279810-ffffffff81279b67: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127e970)
Location: mm/shmem.c:1691
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff8127e970-ffffffff8127eca9: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bc4f0)
Location: mm/shmem.c:1714
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff812bc4f0-ffffffff812bc82d: shmem_swapin_page (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d3660)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffff8000102d3660-ffff8000102d3db8: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fb8fc)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
c04fb8fc-c04fbf3c: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003926c0)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
c0000000003926c0-c000000000392fc0: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef746)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffe0001ef746-ffffffe0001efcf0: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812398d0)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff812398d0-ffffffff81239f25: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c900)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff8122c900-ffffffff8122cf35: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237670)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81237670-ffffffff81237cc5: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81246bb0)
Location: mm/shmem.c:1634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
```
**Symbols:**

```
ffffffff81246bb0-ffffffff81247307: shmem_swapin_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
