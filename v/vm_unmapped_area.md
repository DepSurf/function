# Function: <code>vm_unmapped_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81034141)
Location: include/linux/mm.h:1991
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81072cd9)
Location: include/linux/mm.h:1991
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033531)
Location: include/linux/mm.h:2112
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81073549)
Location: include/linux/mm.h:2112
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033170)
Location: include/linux/mm.h:2098
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810770ec)
Location: include/linux/mm.h:2098
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81031415)
Location: include/linux/mm.h:2176
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81075918)
Location: include/linux/mm.h:2176
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033604)
Location: include/linux/mm.h:2285
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107bb6b)
Location: include/linux/mm.h:2285
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81034978)
Location: include/linux/mm.h:2374
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e9cd)
Location: include/linux/mm.h:2374
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81035b58)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108554d)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81037cc3)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108914c)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038493)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089dbc)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129a770)
Location: mm/mmap.c:2064
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff8129a770-ffffffff8129a7ee: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5950)
Location: mm/mmap.c:2130
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff812a5950-ffffffff812a59bc: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab0e0)
Location: mm/mmap.c:2134
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff812ab0e0-ffffffff812ab14c: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec7b0)
Location: mm/mmap.c:2103
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff812ec7b0-ffffffff812ec819: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134f640)
Location: mm/mmap.c:2122
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff8134f640-ffffffff8134f6bf: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c8c80)
Location: mm/mmap.c:1624
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff813c8c80-ffffffff813c8e1f: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fcf10)
Location: mm/mmap.c:1652
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff813fcf10-ffffffff813fd1b4: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int vm_unmapped_area(struct vm_unmapped_area_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff814298e0)
Location: mm/mmap.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff814298e0-ffffffff81429be0: vm_unmapped_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff80001030181c)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmap.c (c031f6a8)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown
  - arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown
  - arch/arm/mm/mmap.c:arch_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mmap.c (c000000000088600)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area_topdown
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009eee4)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area
```
```
In arch/powerpc/mm/slice.c (c0000000000a42f0)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_find_area
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020eaf8)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
```
```
In fs/hugetlbfs/inode.c (ffffffe0003557b2)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff810385f3)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088d7c)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81027fd3)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810779dc)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038453)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088d2c)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81039453)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108afcc)
Location: include/linux/mm.h:2416
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
