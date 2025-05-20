# Function: <code>rq_depth_calc_max_depth</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814bd9b0)
Location: block/blk-rq-qos.c:96
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff814bd9b0-ffffffff814bda2b: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ec040)
Location: block/blk-rq-qos.c:98
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff814ec040-ffffffff814ec0c7: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81505480)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff81505480-ffffffff81505507: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565eaa)
Location: block/blk-rq-qos.c:116
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff81565d50-ffffffff81565dd7: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580e2a)
Location: block/blk-rq-qos.c:116
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff81580cd0-ffffffff81580d57: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8158898d)
Location: block/blk-rq-qos.c:116
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff81588840-ffffffff815888b1: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (ffffffff815ee683)
Location: block/blk-rq-qos.c:116
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff81cd9ade-ffffffff81cd9afd: rq_depth_calc_max_depth.cold (STB_LOCAL)
ffffffff815ee4e0-ffffffff815ee581: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8169ef35)
Location: block/blk-rq-qos.c:116
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff81e8d570-ffffffff81e8d592: rq_depth_calc_max_depth.cold (STB_LOCAL)
ffffffff8169ed50-ffffffff8169ee18: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8175d7e5)
Location: block/blk-rq-qos.c:110
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff82076b8f-ffffffff82076bb1: rq_depth_calc_max_depth.cold (STB_LOCAL)
ffffffff8175d5e0-ffffffff8175d6a8: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8179c549)
Location: block/blk-rq-qos.c:110
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff820f69ad-ffffffff820f69cf: rq_depth_calc_max_depth.cold (STB_LOCAL)
ffffffff8179c340-ffffffff8179c40c: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (ffffffff817dffa9)
Location: block/blk-rq-qos.c:110
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
Direct callers:
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff821d3dfb-ffffffff821d3e1d: rq_depth_calc_max_depth.cold (STB_LOCAL)
ffffffff817dfda0-ffffffff817dfe6c: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff800010607558)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffff800010607558-ffff800010607628: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b2768)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
c07b2768-c07b2814: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a40d0)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
c0000000007a40d0-c0000000007a41d0: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe000442166)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffe000442166-ffffffe000442210: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fda60)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff814fda60-ffffffff814fdae7: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814edf70)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff814edf70-ffffffff814edff7: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f9af0)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff814f9af0-ffffffff814f9b77: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rq_depth_calc_max_depth(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512b50)
Location: block/blk-rq-qos.c:116
Inline: True
Direct callers:
  - block/blk-rq-qos.c:rq_depth_scale_down
  - block/blk-rq-qos.c:rq_depth_scale_up
  - block/blk-wbt.c:__wbt_update_limits
```
**Symbols:**

```
ffffffff81512b50-ffffffff81512bd7: rq_depth_calc_max_depth (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
