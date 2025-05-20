# Function: <code>__swap_info_get</code>

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
struct swap_info_struct *__swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120c710)
Location: mm/swapfile.c:1001
Inline: False
Direct callers:
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:_swap_info_get
```
**Symbols:**

```
ffffffff8120c710-ffffffff8120c7a5: __swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct swap_info_struct *__swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226410)
Location: mm/swapfile.c:1036
Inline: False
Direct callers:
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:_swap_info_get
```
**Symbols:**

```
ffffffff81226410-ffffffff812264a8: __swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *__swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1036
Inline: False
Direct callers:
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:_swap_info_get
```
**Symbols:**

```
ffffffff812489e0-ffffffff81248a36: __swap_info_get (STB_LOCAL)
ffffffff8124e688-ffffffff8124e6df: __swap_info_get.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *__swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1066
Inline: False
Direct callers:
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:_swap_info_get
```
**Symbols:**

```
ffffffff8125cfc0-ffffffff8125d013: __swap_info_get (STB_LOCAL)
ffffffff81262b68-ffffffff81262bbf: __swap_info_get.cold.49 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81278285)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff81287d75)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff812ba135)
Location: mm/swapfile.c:1140
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff812c5ba5)
Location: mm/swapfile.c:1156
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff812cc6b5)
Location: mm/swapfile.c:1155
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff813119f5)
Location: mm/swapfile.c:1124
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffff800010322bb8)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (c053af34)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (c0000000003f8710)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffe000223766)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff81280355)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff812721c5)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff8127e165)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
In mm/swapfile.c (ffffffff8128dd15)
Location: mm/swapfile.c:1104
Inline: True
Inline callers:
  - mm/swapfile.c:_swap_info_get
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
</ul>
