# Function: <code>swap_alloc_cluster</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120ef20)
Location: mm/swapfile.c:835
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8122a85b)
Location: mm/swapfile.c:867
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8124bac2)
Location: mm/swapfile.c:867
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8126018d)
Location: mm/swapfile.c:894
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8127ae11)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8128a8f1)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int swap_alloc_cluster(struct swap_info_struct *si, swp_entry_t *slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb330)
Location: mm/swapfile.c:969
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812bb330-ffffffff812bb43e: swap_alloc_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int swap_alloc_cluster(struct swap_info_struct *si, swp_entry_t *slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6dd0)
Location: mm/swapfile.c:987
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812c6dd0-ffffffff812c6ede: swap_alloc_cluster (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812cfc31)
Location: mm/swapfile.c:986
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff81315203)
Location: mm/swapfile.c:994
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff813807af)
Location: mm/swapfile.c:998
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff813ff0a4)
Location: mm/swapfile.c:1001
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff81431fbf)
Location: mm/swapfile.c:1003
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff8146b3af)
Location: mm/swapfile.c:1003
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:929
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:929
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:929
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:929
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
In mm/swapfile.c (ffffffff81282ed1)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff812749f1)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff81280ce1)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
In mm/swapfile.c (ffffffff812909ec)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
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
