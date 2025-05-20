# Function: <code>hstate_index</code>

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
In mm/hugetlb.c (ffffffff811da364)
Location: include/linux/hugetlb.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81f8d8c1)
Location: include/linux/hugetlb.h:441
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff811fd97b)
Location: include/linux/hugetlb.h:437
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81fb7df6)
Location: include/linux/hugetlb.h:437
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8120e456)
Location: include/linux/hugetlb.h:437
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81ff47b4)
Location: include/linux/hugetlb.h:437
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff81219d79)
Location: include/linux/hugetlb.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff820d6fa4)
Location: include/linux/hugetlb.h:459
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff81234e51)
Location: include/linux/hugetlb.h:453
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff826dfc10)
Location: include/linux/hugetlb.h:453
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff81257df1)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8270a10d)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8126c4ab)
Location: include/linux/hugetlb.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828c12f1)
Location: include/linux/hugetlb.h:477
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8128786b)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828da686)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8129747b)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828e2b15)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c7cce)
Location: include/linux/hugetlb.h:628
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff82d00062)
Location: include/linux/hugetlb.h:628
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d382d)
Location: include/linux/hugetlb.h:626
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff82feca27)
Location: include/linux/hugetlb.h:626
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812da780)
Location: include/linux/hugetlb.h:739
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff831f7243)
Location: include/linux/hugetlb.h:739
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81473aab)
Location: include/linux/hugetlb.h:739
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8132172d)
Location: include/linux/hugetlb.h:762
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff832dde69)
Location: include/linux/hugetlb.h:762
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca6d2)
Location: include/linux/hugetlb.h:762
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138e72e)
Location: include/linux/hugetlb.h:792
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff83493740)
Location: include/linux/hugetlb.h:792
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff8155668e)
Location: include/linux/hugetlb.h:792
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d1c3)
Location: include/linux/hugetlb.h:836
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d495)
Location: include/linux/hugetlb.h:836
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff815f8194)
Location: include/linux/hugetlb.h:836
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814405e5)
Location: include/linux/hugetlb.h:864
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff81492c16)
Location: include/linux/hugetlb.h:864
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81630114)
Location: include/linux/hugetlb.h:864
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147a693)
Location: include/linux/hugetlb.h:886
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2337)
Location: include/linux/hugetlb.h:886
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/hugetlbfs/inode.c (ffffffff816695c4)
Location: include/linux/hugetlb.h:886
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
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
In mm/hugetlb.c (ffff800010335138)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffff80001145be1c)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040eba0)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (c0000000013868e0)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffe000017f1e)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffe00001963e)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8128fa5b)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828cb9c9)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff81281710)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828c40ee)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8128d86b)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828de749)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
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
In mm/hugetlb.c (ffffffff8129d5f8)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff828e3b60)
Location: include/linux/hugetlb.h:465
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
</details>
</li>
</ul>

## Differences
