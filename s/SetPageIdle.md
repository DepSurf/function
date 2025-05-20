# Function: <code>SetPageIdle</code>

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
In mm/migrate.c (ffffffff811f1ca6)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f73ac)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff81208421)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812106e4)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81217cd5)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff8122df2b)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff81222833)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122a293)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff8124047b)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff8122e2bf)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81235e94)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff8124c2f3)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff81249393)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81254bee)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff8126c703)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff8126ce14)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81278a4e)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff812912ad)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff81281640)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8128d0fc)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_idle.c (ffffffff812a62cd)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff8129d8d3)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a23de)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812c19dd)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812ad1f1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b38dd)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812d390d)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812e2e31)
Location: include/linux/page-flags.h:439
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812e8950)
Location: include/linux/page-flags.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/page_idle.c (ffffffff8130967d)
Location: include/linux/page-flags.h:439
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812ee273)
Location: include/linux/page-flags.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f3db1)
Location: include/linux/page-flags.h:443
Inline: True
```
```
In mm/page_idle.c (ffffffff8131548d)
Location: include/linux/page-flags.h:443
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812f3d63)
Location: include/linux/page-flags.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812fa211)
Location: include/linux/page-flags.h:443
Inline: True
```
```
In mm/page_idle.c (ffffffff8131bb5d)
Location: include/linux/page-flags.h:443
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff8133e70f)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81343f31)
Location: include/linux/page-flags.h:457
Inline: True
```
```
In mm/page_idle.c (ffffffff81368e1d)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034f6e0)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010354aa4)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffff800010379328)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (c00000000043196c)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c00000000043b98c)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (c00000000046c918)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffe00023e510)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/page_idle.c (ffffffe000250bb8)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812a57d1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812abebd)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812cbeed)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812972a1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8129da2d)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812bcd5d)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812a35e1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a9ccd)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812c9cfd)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
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
In mm/migrate.c (ffffffff812b3df1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b9f4d)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/page_idle.c (ffffffff812da9f8)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
```
</details>
</li>
</ul>

## Differences
