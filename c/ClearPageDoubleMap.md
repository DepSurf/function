# Function: <code>ClearPageDoubleMap</code>

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
In mm/page_alloc.c (ffffffff811a77c7)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff811b7bbc)
Location: include/linux/page-flags.h:606
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff811bf9f9)
Location: include/linux/page-flags.h:609
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff811d4526)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff811f5f2a)
Location: include/linux/page-flags.h:617
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff81207bc8)
Location: include/linux/page-flags.h:634
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff8126deee)
Location: include/linux/page-flags.h:667
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff8127cd0e)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff812af057)
Location: include/linux/page-flags.h:699
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff812baabd)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff812bfc16)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff81302656)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
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
In mm/rmap.c (ffffffff8135d3cd)
Location: include/linux/page-flags.h:892
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff8136a3f0)
Location: include/linux/page-flags.h:892
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
</details>
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
In mm/page_alloc.c (ffff800010314870)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:705
Inline: False
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
In mm/page_alloc.c (c0000000003e5ff0)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:705
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
In mm/page_alloc.c (ffffffff8127535e)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff812672b8)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff812730fe)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
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
In mm/page_alloc.c (ffffffff81282be3)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
</details>
</li>
</ul>

## Differences
