# Function: <code>destroy_compound_page</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125e8fc)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff812668a4)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268883)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff812700f4)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126e5f3)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff8127512f)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ab603)
Location: include/linux/mm.h:940
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff812b240b)
Location: include/linux/mm.h:940
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
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
In mm/swap.c (ffffffff81305429)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff8130d388)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
