# Function: <code>anon_vma_unlock_read</code>

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
In mm/rmap.c (ffffffff811ca5a6)
Location: include/linux/rmap.h:126
Inline: True
Inline callers:
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:rmap_walk
```
```
In mm/ksm.c (ffffffff811e6fca)
Location: include/linux/rmap.h:126
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff811e6f09)
Location: include/linux/rmap.h:130
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8120605e)
Location: include/linux/rmap.h:130
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff811f82a9)
Location: include/linux/rmap.h:131
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8121807e)
Location: include/linux/rmap.h:131
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff81203778)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81223c0f)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8121c2d3)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8123f25a)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8123deb4)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81262a58)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff81252439)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff812772d8)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff812645cf)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81292b36)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff81272e3f)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff812a28b6)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff812a3cad)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/hugetlb.c (ffffffff812c4134)
Location: include/linux/rmap.h:133
Inline: True
```
```
In mm/ksm.c (ffffffff812d7036)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff812af78d)
Location: include/linux/rmap.h:132
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff812e2bc3)
Location: include/linux/rmap.h:132
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff812b4f3a)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff812ea353)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff812f6889)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81332273)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8135b9b0)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff813a365e)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff813d669b)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff814233be)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
```
```
In mm/memory-failure.c (ffffffff814612f0)
Location: include/linux/rmap.h:139
Inline: True
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
In mm/rmap.c (ffffffff8140b622)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8145861d)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
```
```
In mm/memory-failure.c (ffffffff81497c50)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
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
In mm/rmap.c (ffffffff81437f1b)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81492d7c)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
```
```
In mm/memory-failure.c (ffffffff814c7215)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
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
In mm/rmap.c (ffff8000103089ac)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffff8000103422d0)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (c05258a0)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (c054803c)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (c0000000003d7dc0)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (c00000000041fc50)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffe0002132ca)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffe000236530)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8126b48f)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8129ae96)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8125d72f)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff8128ca56)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff8126922f)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff81298ca6)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
In mm/rmap.c (ffffffff81278d6d)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_unlock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/ksm.c (ffffffff812a8a8c)
Location: include/linux/rmap.h:133
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
```
</details>
</li>
</ul>

## Differences
