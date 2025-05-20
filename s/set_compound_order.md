# Function: <code>set_compound_order</code>

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
In mm/page_alloc.c (ffffffff81192956)
Location: include/linux/mm.h:560
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811daa6d)
Location: include/linux/mm.h:560
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811a995a)
Location: include/linux/mm.h:607
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811f914d)
Location: include/linux/mm.h:607
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff811b9eb0)
Location: include/linux/mm.h:594
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81209d3c)
Location: include/linux/mm.h:594
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff811c240d)
Location: include/linux/mm.h:650
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812152df)
Location: include/linux/mm.h:650
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff811d6dbe)
Location: include/linux/mm.h:667
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8122fe1f)
Location: include/linux/mm.h:667
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff811f86e6)
Location: include/linux/mm.h:709
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8125227f)
Location: include/linux/mm.h:709
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff8120ad19)
Location: include/linux/mm.h:737
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812664ef)
Location: include/linux/mm.h:737
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff8126d430)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81281793)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff8127bf70)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81290af3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff812af6a3)
Location: include/linux/mm.h:911
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c3c33)
Location: include/linux/mm.h:911
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812bb32b)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812cf878)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff812c048b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812d60cd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff81303203)
Location: include/linux/mm.h:976
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8131c9d1)
Location: include/linux/mm.h:976
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81f1a59f)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff81388367)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c2404)
Location: include/linux/mm.h:1020
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103134f8)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffff80001032e170)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (c052e39c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
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
In mm/page_alloc.c (c0000000003e5158)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (c000000000406ba4)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffe00021a8a2)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffe00022c408)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff812745c0)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812890d3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff81266530)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff8127af73)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff81272360)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81286ee3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff81282190)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812975b3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
</ul>

## Differences
