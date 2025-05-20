# Function: <code>scan_swap_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int scan_swap_map(struct swap_info_struct *si, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d4a40)
Location: mm/swapfile.c:493
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page_of_type
```
**Symbols:**

```
ffffffff811d4a40-ffffffff811d4f1f: scan_swap_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int scan_swap_map(struct swap_info_struct *si, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f2920)
Location: mm/swapfile.c:490
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
**Symbols:**

```
ffffffff811f2920-ffffffff811f2e64: scan_swap_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int scan_swap_map(struct swap_info_struct *si, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81203390)
Location: mm/swapfile.c:496
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
**Symbols:**

```
ffffffff81203390-ffffffff812038d7: scan_swap_map (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8120f195)
Location: mm/swapfile.c:880
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8122a9d5)
Location: mm/swapfile.c:912
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8124bc75)
Location: mm/swapfile.c:912
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812602f6)
Location: mm/swapfile.c:942
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8127af7a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8128aa5a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812bd77c)
Location: mm/swapfile.c:1017
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812c92a0)
Location: mm/swapfile.c:1032
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812cfe20)
Location: mm/swapfile.c:1031
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In mm/swapfile.c (ffff800010325cb8)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (c053d410)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (c0000000003fc018)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffe000226084)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8128303a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81274b5a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81280e4a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81290b5a)
Location: mm/swapfile.c:977
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
