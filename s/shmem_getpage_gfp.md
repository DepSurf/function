# Function: <code>shmem_getpage_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a9030)
Location: mm/shmem.c:1064
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_follow_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_symlink
```
**Symbols:**

```
ffffffff811a9030-ffffffff811a9858: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct mm_struct *fault_mm, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c0710)
Location: mm/shmem.c:1544
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811c0710-ffffffff811c12ed: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct mm_struct *fault_mm, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d0cf0)
Location: mm/shmem.c:1571
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811d0cf0-ffffffff811d18fb: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d9790)
Location: mm/shmem.c:1596
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811d9790-ffffffff811da2cc: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ef460)
Location: mm/shmem.c:1611
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811ef460-ffffffff811f0029: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, int *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81210ac0)
Location: mm/shmem.c:1630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81210ac0-ffffffff812117b1: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81222af0)
Location: mm/shmem.c:1596
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81222af0-ffffffff81223787: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812336e0)
Location: mm/shmem.c:1733
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812336e0-ffffffff81234017: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812418e0)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812418e0-ffffffff81242217: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126ea10)
Location: mm/shmem.c:1732
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8126ea10-ffffffff8126f2de: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81279b70)
Location: mm/shmem.c:1793
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81279b70-ffffffff8127a424: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ecb0)
Location: mm/shmem.c:1791
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8127ecb0-ffffffff8127f567: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:1814
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812bd060-ffffffff812bd8b4: shmem_getpage_gfp (STB_LOCAL)
ffffffff81cbaa59-ffffffff81cbaa7a: shmem_getpage_gfp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:1823
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
```
**Symbols:**

```
ffffffff81318d10-ffffffff81319639: shmem_getpage_gfp (STB_LOCAL)
ffffffff81e6c344-ffffffff81e6c364: shmem_getpage_gfp.cold (STB_LOCAL)
```
</details>
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
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d3db8)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffff8000102d3db8-ffff8000102d4704: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fbf3c)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c04fbf3c-c04fc7e8: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000392fc0)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c000000000392fc0-c000000000393c80: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001efcf0)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffe0001efcf0-ffffffe0001f0412: shmem_getpage_gfp (STB_LOCAL)
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
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239f30)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81239f30-ffffffff8123a867: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122cf40)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8122cf40-ffffffff8122d865: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237cd0)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81237cd0-ffffffff81238607: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode *inode, long unsigned int index, struct page **pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct *vma, struct vm_fault *vmf, vm_fault_t *fault_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81247310)
Location: mm/shmem.c:1748
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81247310-ffffffff81247c48: shmem_getpage_gfp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *fault_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, index, pagep, sgp, gfp, fault_type</code> ➡️ <code>inode, index, pagep, sgp, gfp, fault_mm, fault_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *fault_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, index, pagep, sgp, gfp, fault_mm, fault_type</code> ➡️ <code>inode, index, pagep, sgp, gfp, vma, vmf, fault_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int *fault_type</code> ➡️ <code>vm_fault_t *fault_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
