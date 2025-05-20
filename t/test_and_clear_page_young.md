# Function: <code>test_and_clear_page_young</code>

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
In mm/rmap.c (ffffffff811cabc7)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff81278e25)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff811e7bad)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff812a57ee)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff811f8f2d)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff812bb138)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff81203043)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff812c66e1)
Location: include/linux/page_idle.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8121c4d3)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff812ecc52)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8123e30c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff81319292)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8125289c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff813308aa)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff81264bfe)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In fs/proc/task_mmu.c (ffffffff813586d4)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8127348e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812853ae)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81370924)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812a42be)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812b7843)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813b8de7)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812afd7e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c2784)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813ca82f)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812b535e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c960a)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813d189d)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812f6f9e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8130e630)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81422d9d)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/madvise.c (ffffffff81377975)
Location: include/linux/page_idle.h:119
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8149ab56)
Location: include/linux/page_idle.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/madvise.c (ffffffff813f51ed)
Location: include/linux/page_idle.h:133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8152f093)
Location: include/linux/page_idle.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81567347)
Location: include/linux/page_idle.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159d8c7)
Location: include/linux/page_idle.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffff800010308fa4)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffff80001031f3c4)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffff80001043aa3c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0525dc0)
Location: include/linux/page_idle.h:68
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (c0537b38)
Location: include/linux/page_idle.h:68
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (c0600434)
Location: include/linux/page_idle.h:68
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (c0000000003d837c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (c0000000003f473c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (c00000000054e524)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffe000213594)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffe000220c3a)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffe0002d22aa)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8126bade)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8127d9fe)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81368f04)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8125db7e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8126f896)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8135a04c)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8126987e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8127b79e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813669d4)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff81278b0e)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8128b60f)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8137a030)
Location: include/linux/page_idle.h:22
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
