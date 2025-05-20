# Function: <code>add_to_free_area_tail</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d972)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8127451b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127c792)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8128332b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314250)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffff80001031b27c)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e75c)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c0535328)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e5964)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c0000000003eeb80)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ae78)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffe0002203c8)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274de2)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8127b97b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81266d52)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8126d85b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272b82)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8127971b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282634)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8128930b)
Location: include/linux/mmzone.h:112
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
</ul>

## Differences
