# Function: <code>current_hweight</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150f730)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff8150f730-ffffffff8150f833: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570830)
Location: block/blk-iocost.c:955
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff81570830-ffffffff81570938: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158ba10)
Location: block/blk-iocost.c:1140
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff8158ba10-ffffffff8158bb2d: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815928d0)
Location: block/blk-iocost.c:1146
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff815928d0-ffffffff815929eb: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815f9c50)
Location: block/blk-iocost.c:1146
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff815f9c50-ffffffff815f9d6b: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816abde0)
Location: block/blk-iocost.c:1145
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff816abde0-ffffffff816abf0a: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176a7e0)
Location: block/blk-iocost.c:1150
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff8176a7e0-ffffffff8176a90a: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817a98e0)
Location: block/blk-iocost.c:1166
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff817a98e0-ffffffff817a9a0a: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ed6a0)
Location: block/blk-iocost.c:1166
Inline: False
Direct callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
```
**Symbols:**

```
ffffffff817ed6a0-ffffffff817ed7ca: current_hweight (STB_LOCAL)
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
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff8000106134a0)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffff8000106134a0-ffff800010613598: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bdbe8)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
c07bdbe8-c07bdd14: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b1b10)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
c0000000007b1b10-c0000000007b1cac: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044a8a0)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffe00044a8a0-ffffffe00044a994: current_hweight (STB_LOCAL)
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
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81507d10)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff81507d10-ffffffff81507e13: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f81c0)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff814f81c0-ffffffff814f82c3: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81503da0)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff81503da0-ffffffff81503ea3: current_hweight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq *iocg, u32 *hw_activep, u32 *hw_inusep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151d350)
Location: block/blk-iocost.c:957
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff8151d350-ffffffff8151d453: current_hweight (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
