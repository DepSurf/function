# Function: <code>iommu_phys_to_virt</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162aff0)
Location: drivers/iommu/amd_iommu_proto.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665bee)
Location: drivers/iommu/amd_iommu_proto.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168465e)
Location: drivers/iommu/amd_iommu_proto.h:101
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bbbb3)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dea43)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817951c3)
Location: drivers/iommu/amd/amd_iommu.h:91
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3583)
Location: drivers/iommu/amd/amd_iommu.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
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
In drivers/iommu/amd/iommu.c (ffffffff81786333)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c972)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
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
In drivers/iommu/amd/iommu.c (ffffffff8180d195)
Location: drivers/iommu/amd/amd_iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81814032)
Location: drivers/iommu/amd/amd_iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
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
In drivers/iommu/amd/iommu.c (ffffffff8194d8e1)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954e04)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
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
In drivers/iommu/amd/iommu.c (ffffffff81ab1e01)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81abacc0)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb2c2)
Location: drivers/iommu/amd/amd_iommu.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
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
In drivers/iommu/amd/iommu.c (ffffffff81afdeb2)
Location: drivers/iommu/amd/amd_iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b073b7)
Location: drivers/iommu/amd/amd_iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b0786a)
Location: drivers/iommu/amd/amd_iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:fetch_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
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
In drivers/iommu/amd/iommu.c (ffffffff81b51622)
Location: drivers/iommu/amd/amd_iommu.h:119
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5b39c)
Location: drivers/iommu/amd/amd_iommu.h:119
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5b89a)
Location: drivers/iommu/amd/amd_iommu.h:119
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:fetch_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4493)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681e83)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2703)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ecd43)
Location: drivers/iommu/amd_iommu_proto.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
</ul>

## Differences
