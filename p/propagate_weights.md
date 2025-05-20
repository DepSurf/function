# Function: <code>propagate_weights</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158e6d2)
Location: block/blk-iocost.c:1133
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-iocost.c (ffffffff81595432)
Location: block/blk-iocost.c:1139
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff815fc352)
Location: block/blk-iocost.c:1139
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:weight_updated
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815fba80-ffffffff815fbac6: propagate_weights (STB_LOCAL)
ffffffff81cd9e23-ffffffff81cd9e38: propagate_weights.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff816b0a55)
Location: block/blk-iocost.c:1138
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:weight_updated
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff816af040-ffffffff816af095: propagate_weights (STB_LOCAL)
ffffffff81e8d8ca-ffffffff81e8d8df: propagate_weights.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff817708b9)
Location: block/blk-iocost.c:1143
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:weight_updated
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff8176e550-ffffffff8176e5a5: propagate_weights (STB_LOCAL)
ffffffff82076e63-ffffffff82076e78: propagate_weights.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff817af909)
Location: block/blk-iocost.c:1159
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:weight_updated
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817ae0d0-ffffffff817ae125: propagate_weights (STB_LOCAL)
ffffffff820f6ce7-ffffffff820f6cfc: propagate_weights.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff817f3719)
Location: block/blk-iocost.c:1159
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:weight_updated
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817f1ee0-ffffffff817f1f35: propagate_weights (STB_LOCAL)
ffffffff821d4135-ffffffff821d414a: propagate_weights.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
