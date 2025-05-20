# Function: <code>ioc_now</code>

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
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150fed0)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8150fed0-ffffffff8150ff50: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570f80)
Location: block/blk-iocost.c:851
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff81570f80-ffffffff81571002: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c2e0)
Location: block/blk-iocost.c:1027
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff8158c2e0-ffffffff8158c363: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815931a0)
Location: block/blk-iocost.c:1023
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815931a0-ffffffff81593223: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fa450)
Location: block/blk-iocost.c:1023
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815fa450-ffffffff815fa4d3: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816ac7e0)
Location: block/blk-iocost.c:1022
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff816ac7e0-ffffffff816ac870: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176b080)
Location: block/blk-iocost.c:1026
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff8176b080-ffffffff8176b109: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817aa160)
Location: block/blk-iocost.c:1042
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817aa160-ffffffff817aa1e9: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817edf20)
Location: block/blk-iocost.c:1042
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817edf20-ffffffff817edfa9: ioc_now (STB_LOCAL)
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
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff8000106138e0)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffff8000106138e0-ffff800010613978: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c1258)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
c07c1258-c07c13b0: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b26e0)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
c0000000007b26e0-c0000000007b27bc: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044aff8)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffe00044aff8-ffffffe00044b076: ioc_now (STB_LOCAL)
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
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815084b0)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff815084b0-ffffffff81508530: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8960)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff814f8960-ffffffff814f89e0: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504540)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff81504540-ffffffff815045c0: ioc_now (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioc_now(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151daf0)
Location: block/blk-iocost.c:853
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
**Symbols:**

```
ffffffff8151daf0-ffffffff8151db70: ioc_now (STB_LOCAL)
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
