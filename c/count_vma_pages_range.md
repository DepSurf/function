# Function: <code>count_vma_pages_range</code>

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
In mm/mmap.c (ffffffff811c7074)
Location: mm/mmap.c:588
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff811e3632)
Location: mm/mmap.c:480
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff811f3612)
Location: mm/mmap.c:507
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff811fe66a)
Location: mm/mmap.c:523
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81216c1a)
Location: mm/mmap.c:524
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81237c00)
Location: mm/mmap.c:533
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff8124b599)
Location: mm/mmap.c:557
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff8125da43)
Location: mm/mmap.c:559
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff8126c213)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff8129bf56)
Location: mm/mmap.c:563
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff812a71dd)
Location: mm/mmap.c:605
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812acd9b)
Location: mm/mmap.c:609
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ee4eb)
Location: mm/mmap.c:608
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813518e2)
Location: mm/mmap.c:614
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int count_vma_pages_range(struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c64a0)
Location: mm/mmap.c:392
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff813c64a0-ffffffff813c6554: count_vma_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int count_vma_pages_range(struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fa8f0)
Location: mm/mmap.c:379
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff813fa8f0-ffffffff813fa9a8: count_vma_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int count_vma_pages_range(struct mm_struct *mm, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff814266b0)
Location: mm/mmap.c:367
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff814266b0-ffffffff81426767: count_vma_pages_range (STB_LOCAL)
```
</details>
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
In mm/mmap.c (ffff8000103035ac)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (c0521c44)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (c0000000003d0090)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffe000210110)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81264863)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81256c83)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81262603)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
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
In mm/mmap.c (ffffffff81271fc3)
Location: mm/mmap.c:560
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
