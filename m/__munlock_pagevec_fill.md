# Function: <code>__munlock_pagevec_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3309)
Location: mm/mlock.c:359
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811df049)
Location: mm/mlock.c:364
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eee57)
Location: mm/mlock.c:367
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9eeb)
Location: mm/mlock.c:367
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8121233b)
Location: mm/mlock.c:368
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff812330ff)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff812468cd)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff81258b6f)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff8126703f)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __munlock_pagevec_fill(struct pagevec *pvec, struct vm_area_struct *vma, struct zone *zone, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81296990)
Location: mm/mlock.c:374
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff81296990-ffffffff81296b2d: __munlock_pagevec_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __munlock_pagevec_fill(struct pagevec *pvec, struct vm_area_struct *vma, struct zone *zone, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a1800)
Location: mm/mlock.c:350
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff812a1800-ffffffff812a199d: __munlock_pagevec_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __munlock_pagevec_fill(struct pagevec *pvec, struct vm_area_struct *vma, struct zone *zone, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a6fc0)
Location: mm/mlock.c:349
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff812a6fc0-ffffffff812a715d: __munlock_pagevec_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int __munlock_pagevec_fill(struct pagevec *pvec, struct vm_area_struct *vma, struct zone *zone, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mlock.c (0)
Location: mm/mlock.c:350
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff812e8490-ffffffff812e867e: __munlock_pagevec_fill (STB_LOCAL)
ffffffff81cbc697-ffffffff81cbc6e8: __munlock_pagevec_fill.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fe2c8)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (c051d324)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c9a3c)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffe00020c770)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
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
In mm/mlock.c (ffffffff8125f68f)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff81251aaf)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff8125d42f)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/mlock.c (ffffffff8126ce15)
Location: mm/mlock.c:374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
</ul>
