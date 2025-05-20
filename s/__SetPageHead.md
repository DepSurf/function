# Function: <code>__SetPageHead</code>

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
In mm/page_alloc.c (ffffffff8119295c)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811daff7)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
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
In mm/page_alloc.c (ffffffff811a995e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811f9157)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811b9ec2)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81209d45)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811c241c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812152e9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811d6dcd)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8122fe2c)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811f86ea)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8125228e)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8120ad1d)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812664fc)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8126d434)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff8128179b)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8127bf74)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81290afb)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812af6a7)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c3c3c)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812bb2cf)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812cf88b)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812c0422)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812d60db)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff813031c3)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8131c9e8)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
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
In mm/page_alloc.c (ffffffff81f1a51d)
Location: include/linux/page-flags.h:792
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8138837e)
Location: include/linux/page-flags.h:792
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff820c2340)
Location: include/linux/page-flags.h:789
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
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
In mm/mm_init.c (ffffffff82145e63)
Location: include/linux/page-flags.h:778
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c043)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
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
In mm/mm_init.c (ffffffff82228583)
Location: include/linux/page-flags.h:794
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448bb3)
Location: include/linux/page-flags.h:794
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
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
In mm/page_alloc.c (ffff8000103134fc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffff80001032e170)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
Location: include/linux/page-flags.h:550
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
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (c000000000406ba4)
Location: include/linux/page-flags.h:550
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
In mm/page_alloc.c (ffffffe00021a89e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffe00022c3f8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812745c4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812890db)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81266534)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff8127af7b)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81272364)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81286eeb)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81282194)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812975bb)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
</details>
</li>
</ul>

## Differences
