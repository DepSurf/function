# Function: <code>__propagate_weights</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158b920)
Location: block/blk-iocost.c:1068
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff8158b920-ffffffff8158ba05: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815927a0)
Location: block/blk-iocost.c:1064
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff815927a0-ffffffff815928c3: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815f9b20)
Location: block/blk-iocost.c:1064
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff815f9b20-ffffffff815f9c43: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816abca0)
Location: block/blk-iocost.c:1063
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff816abca0-ffffffff816abddd: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176a690)
Location: block/blk-iocost.c:1068
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff8176a690-ffffffff8176a7cb: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817a9790)
Location: block/blk-iocost.c:1084
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff817a9790-ffffffff817a98cb: __propagate_weights (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __propagate_weights(struct ioc_gq *iocg, u32 active, u32 inuse, bool save, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ed550)
Location: block/blk-iocost.c:1084
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff817ed550-ffffffff817ed68b: __propagate_weights (STB_LOCAL)
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
