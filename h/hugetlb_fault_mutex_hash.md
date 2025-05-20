# Function: <code>hugetlb_fault_mutex_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dd180)
Location: mm/hugetlb.c:3650
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811dd180-ffffffff811dd276: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fb460)
Location: mm/hugetlb.c:3665
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811fb460-ffffffff811fb563: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120bf60)
Location: mm/hugetlb.c:3779
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8120bf60-ffffffff8120c063: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217610)
Location: mm/hugetlb.c:3797
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81217610-ffffffff81217719: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812322c0)
Location: mm/hugetlb.c:3818
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812322c0-ffffffff812323c9: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255310)
Location: mm/hugetlb.c:3848
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81255310-ffffffff8125541d: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812696f0)
Location: mm/hugetlb.c:3888
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812696f0-ffffffff812697fd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812873ce)
Location: mm/hugetlb.c:3977
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81284880-ffffffff8128493d: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81296fde)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81294420-ffffffff812944dd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c7810)
Location: mm/hugetlb.c:4515
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812c7810-ffffffff812c78d0: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3380)
Location: mm/hugetlb.c:4505
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812d3380-ffffffff812d3440: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812da0c0)
Location: mm/hugetlb.c:4746
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812da0c0-ffffffff812da179: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81320e80)
Location: mm/hugetlb.c:5051
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81320e80-ffffffff81320f39: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138dc20)
Location: mm/hugetlb.c:5678
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8138dc20-ffffffff8138dce8: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140c980)
Location: mm/hugetlb.c:5959
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8140c980-ffffffff8140ca48: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143fda0)
Location: mm/hugetlb.c:6058
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8143fda0-ffffffff8143fe68: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct address_space *mapping, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81479c50)
Location: mm/hugetlb.c:6326
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81479c50-ffffffff81479d18: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010334e00)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffff800010332ce8-ffff800010332dd8: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040e4e4)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
c00000000040e2e0-c00000000040e3d8: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002315e4)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffe00022f3aa-ffffffe00022f4cc: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128f5be)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8128ca00-ffffffff8128cabd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128128e)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8127e820-ffffffff8127e8dd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d3ce)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8128a810-ffffffff8128a8cd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate *h, struct address_space *mapping, long unsigned int idx, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129d196)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8129a600-ffffffff8129a6bd: hugetlb_fault_mutex_hash (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, mm, vma, mapping, idx, address</code> ➡️ <code>h, mapping, idx, address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hstate *h</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, mapping, idx, address</code> ➡️ <code>mapping, idx</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
