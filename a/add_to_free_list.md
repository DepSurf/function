# Function: <code>add_to_free_list</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b0ba7)
Location: mm/page_alloc.c:850
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff812c038d)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff812c5b05)
Location: mm/page_alloc.c:913
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff8130a244)
Location: mm/page_alloc.c:963
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff81372acb)
Location: mm/page_alloc.c:926
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff813f023b)
Location: mm/page_alloc.c:998
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff81423dc5)
Location: mm/page_alloc.c:687
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff81450ca3)
Location: mm/page_alloc.c:663
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
```
</details>
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
