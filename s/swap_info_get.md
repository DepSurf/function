# Function: <code>swap_info_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct swap_info_struct *swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d2f60)
Location: mm/swapfile.c:731
Inline: False
Direct callers:
  - mm/swapfile.c:swap_free
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:add_swap_count_continuation
```
**Symbols:**

```
ffffffff811d2f60-ffffffff811d302e: swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct swap_info_struct *swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f0df0)
Location: mm/swapfile.c:728
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff811f0df0-ffffffff811f0ec3: swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct swap_info_struct *swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81201760)
Location: mm/swapfile.c:734
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81201760-ffffffff81201833: swap_info_get (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81211615)
Location: mm/swapfile.c:1049
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8122bf65)
Location: mm/swapfile.c:1084
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8124e43b)
Location: mm/swapfile.c:1084
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812627fb)
Location: mm/swapfile.c:1114
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff8127a41b)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81289efb)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812bcc06)
Location: mm/swapfile.c:1187
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812c8736)
Location: mm/swapfile.c:1202
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812cf0e0)
Location: mm/swapfile.c:1201
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81314680)
Location: mm/swapfile.c:1170
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffff800010324d6c)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (c053c808)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (c0000000003faed0)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffe0002253f2)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812824db)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81273ffb)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff812802eb)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
In mm/swapfile.c (ffffffff81290004)
Location: mm/swapfile.c:1151
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
