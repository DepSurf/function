# Function: <code>__find_buddy_pfn</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bf3fb)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff81246b51)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff811d3f1b)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff81266cc1)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff811f5bcd)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff8128b58e)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81207869)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812a04de)
Location: mm/internal.h:146
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff8126db34)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812bb75b)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff8127c954)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812cd63b)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff812af1db)
Location: mm/internal.h:176
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff8130388b)
Location: mm/internal.h:176
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff812bae4f)
Location: mm/internal.h:174
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff8130f906)
Location: mm/internal.h:174
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff812bff91)
Location: mm/internal.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff81315b06)
Location: mm/internal.h:173
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81302bad)
Location: mm/internal.h:178
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff81361bbd)
Location: mm/internal.h:178
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff813696c4)
Location: mm/internal.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff813ddb84)
Location: mm/internal.h:308
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff813e5693)
Location: mm/internal.h:310
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff81464804)
Location: mm/internal.h:310
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff8141a3c7)
Location: mm/internal.h:324
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff8149a304)
Location: mm/internal.h:324
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff8144762d)
Location: mm/internal.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff814c9a84)
Location: mm/internal.h:341
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffff800010314a70)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffff80001037189c)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (c052e504)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (c055e8f8)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (c0000000003e5a70)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (c000000000463038)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffe00021abdc)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffe00024ae44)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81274fa4)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812c5c1b)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81266f14)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812b6c5b)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81272d44)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812c3a2b)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff81282809)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page_isolation.c (ffffffff812d44cb)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
</ul>

## Differences
