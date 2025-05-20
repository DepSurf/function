# Function: <code>calc_wb_limits</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool calc_wb_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81449f77)
Location: block/blk-wbt.c:192
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_queue_depth
  - block/blk-wbt.c:scale_down
```
**Symbols:**

```
ffffffff81449d00-ffffffff81449dcb: calc_wb_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool calc_wb_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458190)
Location: block/blk-wbt.c:192
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81458190-ffffffff8145824c: calc_wb_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool calc_wb_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81483ef0)
Location: block/blk-wbt.c:191
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81483ef0-ffffffff81483fac: calc_wb_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool calc_wb_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b8cd0)
Location: block/blk-wbt.c:220
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814b8cd0-ffffffff814b8d8b: calc_wb_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd174)
Location: block/blk-wbt.c:295
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_down
  - block/blk-wbt.c:scale_up
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_down
  - block/blk-wbt.c:scale_up
```
**Symbols:**

```
ffffffff814cd110-ffffffff814cd141: calc_wb_limits.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb9e5)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_down
  - block/blk-wbt.c:scale_up
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_down
  - block/blk-wbt.c:scale_up
```
**Symbols:**

```
ffffffff814fb980-ffffffff814fb9b1: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff815198a5)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff81519840-ffffffff81519871: calc_wb_limits.part.0 (STB_LOCAL)
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
In block/blk-wbt.c (ffffffff8157a27f)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81597166)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8159df26)
Location: block/blk-wbt.c:297
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81606603)
Location: block/blk-wbt.c:297
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff816ba373)
Location: block/blk-wbt.c:297
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8177a8f3)
Location: block/blk-wbt.c:298
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817ba846)
Location: block/blk-wbt.c:366
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817fefb6)
Location: block/blk-wbt.c:365
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffff800010620e10)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffff800010620d90-ffff800010620de8: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (c07c8ee4)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
c07c8e78-c07c8eb8: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (c0000000007c12bc)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
c0000000007c1230-c0000000007c127c: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffe0004538fc)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffe000453886-ffffffe0004538d2: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81511e85)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff81511e20-ffffffff81511e51: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff815021a5)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff81502140-ffffffff81502171: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff8150df15)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff8150deb0-ffffffff8150dee1: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81527535)
Location: block/blk-wbt.c:296
Inline: True
Inline callers:
  - block/blk-wbt.c:__wbt_update_limits
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff815274d0-ffffffff81527501: calc_wb_limits.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
