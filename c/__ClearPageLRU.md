# Function: <code>__ClearPageLRU</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119c990)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff811a22b7)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2a8f)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811b7d7d)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c310f)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811c83cb)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb5a6)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d0d70)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0a4d)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811e6260)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202311)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812077d0)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81214c93)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121a350)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81223df0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122c6eb)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff81231b80)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123a90b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125e73f)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265386)
Location: include/linux/page-flags.h:328
Inline: True
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
In mm/swap.c (ffffffff81268989)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81270052)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff8126e820)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812750c4)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff812ab831)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b239c)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c1848)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102cb850)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (c04ecbac)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f56e8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (c00000000037b608)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c0000000003889c8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffe0001e2d20)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ea52c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff8122a1d0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81232f5b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff8121d2f0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81225ffb)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff81227f70)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81230cfb)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff812372b0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8124014b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
</details>
</li>
</ul>

## Differences
