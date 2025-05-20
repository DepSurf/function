# Function: <code>page_trans_huge_map_swapcount</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229bb9)
Location: mm/swapfile.c:1456
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8124ae72)
Location: mm/swapfile.c:1456
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8125f4be)
Location: mm/swapfile.c:1472
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8127a17e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81289c5e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_trans_huge_map_swapcount(struct page *page, int *total_mapcount, int *total_swapcount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bc5f0)
Location: mm/swapfile.c:1618
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812bc5f0-ffffffff812bc7d9: page_trans_huge_map_swapcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_trans_huge_map_swapcount(struct page *page, int *total_mapcount, int *total_swapcount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c8110)
Location: mm/swapfile.c:1636
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812c8110-ffffffff812c82ed: page_trans_huge_map_swapcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_trans_huge_map_swapcount(struct page *page, int *total_mapcount, int *total_swapcount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ceb90)
Location: mm/swapfile.c:1635
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812ceb90-ffffffff812ced5a: page_trans_huge_map_swapcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_trans_huge_map_swapcount(struct page *page, int *total_mapcount, int *total_swapcount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81314120)
Location: mm/swapfile.c:1604
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff81314120-ffffffff813142ea: page_trans_huge_map_swapcount (STB_LOCAL)
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
In mm/swapfile.c (ffff800010324c18)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (c053c704)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (c0000000003fad14)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffe000225312)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8128223e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81273d5e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8128004e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8128fd3e)
Location: mm/swapfile.c:1581
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
