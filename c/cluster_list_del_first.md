# Function: <code>cluster_list_del_first</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81201b9c)
Location: mm/swapfile.c:291
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8120d545)
Location: mm/swapfile.c:348
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81227025)
Location: mm/swapfile.c:360
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81248d39)
Location: mm/swapfile.c:360
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8125d3f0)
Location: mm/swapfile.c:388
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812786c0)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812881b0)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:422
Inline: True
Inline callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:435
Inline: True
Inline callers:
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:434
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:434
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:436
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:440
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:441
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:443
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffff8000103230d0)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (c053bc0c)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (c0000000003f935c)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:inc_cluster_info_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81280790)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81272600)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8127e5a0)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8128ecb0)
Location: mm/swapfile.c:423
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:alloc_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
</details>
</li>
</ul>

## Differences
