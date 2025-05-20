# Function: <code>int_sqrt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff813eb020)
Location: lib/int_sqrt.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/page_alloc.c:init_per_zone_wmark_min
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff813eb020-ffffffff813eb05d: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff814313a0)
Location: lib/int_sqrt.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff814313a0-ffffffff814313dd: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff8144d610)
Location: lib/int_sqrt.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff8144d610-ffffffff8144d64d: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff818ed2c0)
Location: lib/int_sqrt.c:17
Inline: True
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff818ed2c0-ffffffff818ed2fb: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff819733c0)
Location: lib/int_sqrt.c:19
Inline: True
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff819733c0-ffffffff81973409: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff819cf850)
Location: lib/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff819cf850-ffffffff819cf895: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/int_sqrt.c (ffffffff81a08c90)
Location: lib/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/vmscan.c:inactive_list_is_low
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81a08c90-ffffffff81a08cd5: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff815107a0)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff815107a0-ffffffff815107dc: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff8152e6a0)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff8152e6a0-ffffffff8152e6dc: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff81592580)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81592580-ffffffff815925bc: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff815af0f0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff815af0f0-ffffffff815af139: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff815b9ea0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff815b9ea0-ffffffff815b9ee1: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/math/int_sqrt.c (0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81cdb013-ffffffff81cdb034: int_sqrt.cold (STB_LOCAL)
ffffffff81620820-ffffffff81620879: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/math/int_sqrt.c (0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:calculate_min_free_kbytes
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81e938dc-ffffffff81e93905: int_sqrt.cold (STB_LOCAL)
ffffffff816ee980-ffffffff816ee9f0: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/math/int_sqrt.c (0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:calculate_min_free_kbytes
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff82078a26-ffffffff82078a4f: int_sqrt.cold (STB_LOCAL)
ffffffff817df580-ffffffff817df5f0: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/math/int_sqrt.c (0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:calculate_min_free_kbytes
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff820f8ffd-ffffffff820f9026: int_sqrt.cold (STB_LOCAL)
ffffffff8181ed60-ffffffff8181edd0: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/math/int_sqrt.c (0)
Location: lib/math/int_sqrt.c:20
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_organize_nocb_kthreads
  - mm/vmscan.c:inactive_is_low
  - mm/page_alloc.c:calculate_min_free_kbytes
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff821d6bb3-ffffffff821d6bdc: int_sqrt.cold (STB_LOCAL)
ffffffff81864ce0-ffffffff81864d50: int_sqrt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffff80001063ac28)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffff80001063ac28-ffff80001063ac74: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (c07e0d54)
Location: lib/math/int_sqrt.c:19
Inline: True
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
c07e0d54-c07e0da4: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (c0000000007e1ce0)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
c0000000007e1ce0-c0000000007e1d34: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffe000467164)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffe000467164-ffffffe0004671d8: int_sqrt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff81526c80)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81526c80-ffffffff81526cbc: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff81516f60)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81516f60-ffffffff81516f9c: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff81522d10)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff81522d10-ffffffff81522d4c: int_sqrt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/int_sqrt.c (ffffffff8153c690)
Location: lib/math/int_sqrt.c:19
Inline: False
Direct callers:
  - mm/vmscan.c:inactive_list_is_low
  - mm/page_alloc.c:init_per_zone_wmark_min
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/video/fbdev/core/fbmon.c:fb_timings_dclk
```
**Symbols:**

```
ffffffff8153c690-ffffffff8153c6cc: int_sqrt (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
