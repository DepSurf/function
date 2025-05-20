# Function: <code>iocg_kick_waitq</code>

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
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150fd20)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8150fd20-ffffffff8150fec6: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570df0)
Location: block/blk-iocost.c:1140
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff81570df0-ffffffff81570f75: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158d1e0)
Location: block/blk-iocost.c:1455
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8158d1e0-ffffffff8158d4bf: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815945c0)
Location: block/blk-iocost.c:1462
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff815945c0-ffffffff815948a2: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fbad0)
Location: block/blk-iocost.c:1462
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff815fbad0-ffffffff815fbd97: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816af0a0)
Location: block/blk-iocost.c:1461
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff816af0a0-ffffffff816af379: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176e5c0)
Location: block/blk-iocost.c:1466
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8176e5c0-ffffffff8176e899: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ae140)
Location: block/blk-iocost.c:1482
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff817ae140-ffffffff817ae419: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, bool pay_debt, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817f1f50)
Location: block/blk-iocost.c:1489
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff817f1f50-ffffffff817f2229: iocg_kick_waitq (STB_LOCAL)
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
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010615b70)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffff800010615b70-ffff800010615d5c: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07be760)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
c07be760-c07beb14: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b2470)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
c0000000007b2470-c0000000007b26d8: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044aea0)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffe00044aea0-ffffffe00044aff8: iocg_kick_waitq (STB_LOCAL)
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
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508300)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff81508300-ffffffff815084a6: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f87b0)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff814f87b0-ffffffff814f8956: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504390)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff81504390-ffffffff81504536: iocg_kick_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iocg_kick_waitq(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151d940)
Location: block/blk-iocost.c:1142
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8151d940-ffffffff8151dae6: iocg_kick_waitq (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool pay_debt</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocg, now</code> ➡️ <code>iocg, pay_debt, now</code>
</li>
</ul>
</details>
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
