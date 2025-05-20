# Function: <code>blk_cgroup_congested</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212cb2)
Location: include/linux/blk-cgroup.h:291
Inline: True
```
```
In mm/swapfile.c (ffffffff81262a66)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8122268d)
Location: include/linux/blk-cgroup.h:298
Inline: True
```
```
In mm/swapfile.c (ffffffff8127d969)
Location: include/linux/blk-cgroup.h:298
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8123013d)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffff8128d409)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8125d37d)
Location: include/linux/blk-cgroup.h:278
Inline: True
```
```
In mm/swapfile.c (ffffffff812bfe95)
Location: include/linux/blk-cgroup.h:278
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff81267958)
Location: include/linux/blk-cgroup.h:268
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff812cba45)
Location: include/linux/blk-cgroup.h:268
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8126c562)
Location: include/linux/blk-cgroup.h:268
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff812d25e9)
Location: include/linux/blk-cgroup.h:268
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff812a9282)
Location: include/linux/blk-cgroup.h:273
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff81317ee9)
Location: include/linux/blk-cgroup.h:273
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_cgroup_congested();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a4e60)
Location: block/blk-cgroup.c:2017
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
**Symbols:**

```
ffffffff816a4e60-ffffffff816a4eda: blk_cgroup_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_cgroup_congested();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81763c90)
Location: block/blk-cgroup.c:2040
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
**Symbols:**

```
ffffffff81763c90-ffffffff81763d0a: blk_cgroup_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_cgroup_congested();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a2d00)
Location: block/blk-cgroup.c:2132
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:__folio_throttle_swaprate
```
**Symbols:**

```
ffffffff817a2d00-ffffffff817a2d7a: blk_cgroup_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_cgroup_congested();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e6840)
Location: block/blk-cgroup.c:2148
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:__folio_throttle_swaprate
```
**Symbols:**

```
ffffffff817e6840-ffffffff817e68ba: blk_cgroup_congested (STB_GLOBAL)
```
</details>
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
In mm/readahead.c (ffff8000102bf9b8)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffff800010328c90)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (c04eb454)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (c054001c)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (c0000000003788b0)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (c000000000400050)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffe0001e19fa)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffe000228a24)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8122878d)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffff812859e9)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8121b8cd)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffff81277859)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff8122652d)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffff812837f9)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
In mm/readahead.c (ffffffff81235854)
Location: include/linux/blk-cgroup.h:300
Inline: True
```
```
In mm/swapfile.c (ffffffff812934e6)
Location: include/linux/blk-cgroup.h:300
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
