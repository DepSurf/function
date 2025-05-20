# Function: <code>page_cpupid_last</code>

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
In mm/mmzone.c (0)
Location: include/linux/mm.h:779
Inline: True
```
```
In mm/memory.c (ffffffff811bf6e7)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff811f64ad)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff811c522d)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff811db40f)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81217cf1)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff811d5340)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff811eaf81)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8122a2af)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff811de1c0)
Location: include/linux/mm.h:904
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff811f606a)
Location: include/linux/mm.h:904
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81235eb3)
Location: include/linux/mm.h:904
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff811f3c50)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8120dcd1)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/huge_memory.c (ffffffff81254c0d)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff81214f6a)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8122e750)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/huge_memory.c (ffffffff81278a6d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff81227e4a)
Location: include/linux/mm.h:1076
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff81242667)
Location: include/linux/mm.h:1076
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8128d102)
Location: include/linux/mm.h:1076
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff81237b7a)
Location: include/linux/mm.h:1144
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8125145a)
Location: include/linux/mm.h:1144
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812a23e4)
Location: include/linux/mm.h:1144
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff81245e2a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8125fa0a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812b38e4)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff81273bea)
Location: include/linux/mm.h:1332
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8128febf)
Location: include/linux/mm.h:1332
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812e891f)
Location: include/linux/mm.h:1332
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff8127e46a)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8129a93f)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812f6a40)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff812835ca)
Location: include/linux/mm.h:1430
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8129fe1b)
Location: include/linux/mm.h:1430
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812fcdea)
Location: include/linux/mm.h:1430
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff812c17e0)
Location: include/linux/mm.h:1434
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff812e341a)
Location: include/linux/mm.h:1434
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff81346cfb)
Location: include/linux/mm.h:1434
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813447bb)
Location: include/linux/mm.h:1369
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff813bd005)
Location: include/linux/mm.h:1369
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813bc953)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff8143f672)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813f134a)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff81474eb2)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/mmzone.c (ffff8000102d95dc)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffff8000102fa15c)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffff80001035496c)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (0)
Location: include/linux/mm.h:1176
Inline: True
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
In mm/mmzone.c (c000000000399210)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (c0000000003bf500)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (c00000000043b99c)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/mm.h:1176
Inline: True
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
In mm/mmzone.c (ffffffff8123e47a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8125805a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812abec4)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff8123147a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff8124db18)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8129da34)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff8123c21a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff81255dfa)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812a9cd4)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/mmzone.c (ffffffff8124b97a)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/memory.c (ffffffff81265888)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/huge_memory.c (ffffffff812b9f54)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
</ul>

## Differences
