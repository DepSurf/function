# Function: <code>check_new_pages</code>

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
In mm/page_alloc.c (ffffffff811a96bc)
Location: mm/page_alloc.c:1706
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811b9c1d)
Location: mm/page_alloc.c:1725
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811c1c4d)
Location: mm/page_alloc.c:1738
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811d619b)
Location: mm/page_alloc.c:1776
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1883
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1927
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2123
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2186
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2265
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2301
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2375
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool check_new_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2310
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff81368df0-ffffffff81368efa: check_new_pages (STB_LOCAL)
ffffffff81e6efc8-ffffffff81e6efe6: check_new_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool check_new_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2388
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff813e4d80-ffffffff813e4e8a: check_new_pages (STB_LOCAL)
ffffffff82064d6f-ffffffff82064d8d: check_new_pages.cold (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff8141dfb0)
Location: mm/page_alloc.c:1472
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
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
In mm/page_alloc.c (ffffffff8144ab60)
Location: mm/page_alloc.c:1435
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffe00021c838)
Location: mm/page_alloc.c:2114
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2114
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
