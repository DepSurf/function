# Function: <code>walk_hugetlb_range</code>

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
In mm/pagewalk.c (ffffffff811d0147)
Location: mm/pagewalk.c:132
Inline: True
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
In mm/pagewalk.c (ffffffff811ed2e9)
Location: mm/pagewalk.c:132
Inline: True
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
In mm/pagewalk.c (ffffffff811f76d9)
Location: mm/pagewalk.c:132
Inline: True
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
In mm/pagewalk.c (ffffffff8120256d)
Location: mm/pagewalk.c:176
Inline: True
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
In mm/pagewalk.c (ffffffff8121b1dc)
Location: mm/pagewalk.c:177
Inline: True
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
In mm/pagewalk.c (ffffffff8123d28e)
Location: mm/pagewalk.c:177
Inline: True
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
In mm/pagewalk.c (ffffffff812518b1)
Location: mm/pagewalk.c:177
Inline: True
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
In mm/pagewalk.c (ffffffff81263b81)
Location: mm/pagewalk.c:177
Inline: True
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
In mm/pagewalk.c (ffffffff81272384)
Location: mm/pagewalk.c:182
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_hugetlb_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a2310)
Location: mm/pagewalk.c:245
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812a2310-ffffffff812a2419: walk_hugetlb_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_hugetlb_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812adc50)
Location: mm/pagewalk.c:245
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812adc50-ffffffff812add59: walk_hugetlb_range (STB_LOCAL)
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
In mm/pagewalk.c (ffffffff812b3c72)
Location: mm/pagewalk.c:245
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffffffff812f5832)
Location: mm/pagewalk.c:293
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffffffff813596fc)
Location: mm/pagewalk.c:293
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffffffff813d3fa2)
Location: mm/pagewalk.c:293
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffffffff8140897b)
Location: mm/pagewalk.c:309
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffffffff8143509b)
Location: mm/pagewalk.c:309
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
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
In mm/pagewalk.c (ffff800010307ba0)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:211
Inline: True
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
In mm/pagewalk.c (c0000000003d6488)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (ffffffe000212b60)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (ffffffff8126a9d4)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (ffffffff8125cb34)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (ffffffff81268774)
Location: mm/pagewalk.c:182
Inline: True
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
In mm/pagewalk.c (ffffffff81278104)
Location: mm/pagewalk.c:182
Inline: True
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
</ul>
