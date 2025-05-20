# Function: <code>alloc_zeroed_user_highpage_movable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bc487)
Location: include/linux/highmem.h:180
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dbb7b)
Location: include/linux/highmem.h:180
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff811eb3eb)
Location: include/linux/highmem.h:180
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff811f5dfe)
Location: include/linux/highmem.h:180
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8120d87b)
Location: include/linux/highmem.h:181
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8122e48a)
Location: include/linux/highmem.h:181
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff812422e4)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8124fc29)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8125e1c9)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8128e3af)
Location: include/linux/highmem.h:274
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff81299050)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8129e30f)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffff8000102f5c18)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (c0517cb8)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (c0000000003bd22c)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffe000206f36)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff81256819)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff8124920c)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff812545b9)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff81264049)
Location: include/linux/highmem.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
</details>
</li>
</ul>

## Differences
