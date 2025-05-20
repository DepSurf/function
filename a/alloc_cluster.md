# Function: <code>alloc_cluster</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d540)
Location: mm/swapfile.c:428
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff8120d540-ffffffff8120d5a6: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81227020)
Location: mm/swapfile.c:440
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff81227020-ffffffff81227098: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248d20)
Location: mm/swapfile.c:440
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff81248d20-ffffffff81248d98: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125d3e0)
Location: mm/swapfile.c:468
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff8125d3e0-ffffffff8125d440: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812786b0)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff812786b0-ffffffff81278700: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812881a0)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff812881a0-ffffffff812881f0: alloc_cluster (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812bb38c)
Location: mm/swapfile.c:502
Inline: True
Inline callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff812c6e2c)
Location: mm/swapfile.c:515
Inline: True
Inline callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff812cfc88)
Location: mm/swapfile.c:514
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff8131525a)
Location: mm/swapfile.c:522
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff8138080a)
Location: mm/swapfile.c:524
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff813ff0ff)
Location: mm/swapfile.c:528
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff81432022)
Location: mm/swapfile.c:529
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffff8146b412)
Location: mm/swapfile.c:531
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffff8000103230c4)
Location: mm/swapfile.c:503
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (c053bbfc)
Location: mm/swapfile.c:503
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (c0000000003f9350)
Location: mm/swapfile.c:503
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
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
In mm/swapfile.c (ffffffe000223bb2)
Location: mm/swapfile.c:503
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280780)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff81280780-ffffffff812807d0: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812725f0)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff812725f0-ffffffff81272640: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127e590)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff8127e590-ffffffff8127e5e0: alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void alloc_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128eca0)
Location: mm/swapfile.c:503
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
```
**Symbols:**

```
ffffffff8128eca0-ffffffff8128ecf0: alloc_cluster (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
