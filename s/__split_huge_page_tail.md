# Function: <code>__split_huge_page_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81217c90)
Location: mm/huge_memory.c:1758
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff8122a24e)
Location: mm/huge_memory.c:1889
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff81235e17)
Location: mm/huge_memory.c:2208
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff81254b71)
Location: mm/huge_memory.c:2360
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff812789b4)
Location: mm/huge_memory.c:2352
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff8128d048)
Location: mm/huge_memory.c:2374
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff812a2479)
Location: mm/huge_memory.c:2432
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/huge_memory.c (ffffffff812b3835)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __split_huge_page_tail(struct page *head, int tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e8860)
Location: mm/huge_memory.c:2347
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812e8860-ffffffff812e896f: __split_huge_page_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812f3c80)
Location: mm/huge_memory.c:2392
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812f3c80-ffffffff812f3dd4: __split_huge_page_tail.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812fa0e0)
Location: mm/huge_memory.c:2403
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812fa0e0-ffffffff812fa234: __split_huge_page_tail.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff81343e00)
Location: mm/huge_memory.c:2340
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81343e00-ffffffff81343f54: __split_huge_page_tail.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff813b9b40)
Location: mm/huge_memory.c:2363
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813b9b40-ffffffff813b9f86: __split_huge_page_tail.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff8143c5c0)
Location: mm/huge_memory.c:2433
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8143c5c0-ffffffff8143ca6c: __split_huge_page_tail.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff81471c00)
Location: mm/huge_memory.c:2426
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81471c00-ffffffff814720d2: __split_huge_page_tail.isra.0 (STB_LOCAL)
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
In mm/huge_memory.c (ffffffff814a23af)
Location: mm/huge_memory.c:2759
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/huge_memory.c (ffff8000103548d8)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043b8e0)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/huge_memory.c (ffffffff812abe15)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/huge_memory.c (ffffffff8129d985)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/huge_memory.c (ffffffff812a9c25)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/huge_memory.c (ffffffff812b9ea5)
Location: mm/huge_memory.c:2437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
