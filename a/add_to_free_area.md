# Function: <code>add_to_free_area</code>

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
In mm/page_alloc.c (ffffffff8126f3d4)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff812744e9)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffff8127e214)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff812832f9)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffff800010315cd8)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffff80001031b240)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (c0530a34)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c05352f0)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (c0000000003e7db8)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c0000000003eeb28)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffe00021acee)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffe000220396)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffff81276864)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8127b949)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffff812687a2)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff8126d829)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffff81274604)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff812796e9)
Location: include/linux/mmzone.h:104
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
In mm/page_alloc.c (ffffffff812846f5)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff812892d9)
Location: include/linux/mmzone.h:104
Inline: True
Inline callers:
  - mm/shuffle.c:add_to_free_area_random
```
</details>
</li>
</ul>

## Differences
