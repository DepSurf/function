# Function: <code>ioc_start_period</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff81510f00)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81510f00-ffffffff81510f65: ioc_start_period.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81571460)
Location: block/blk-iocost.c:874
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff81571460-ffffffff815714cd: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c590)
Location: block/blk-iocost.c:1050
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff8158c590-ffffffff8158c5ff: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815932d0)
Location: block/blk-iocost.c:1046
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815932d0-ffffffff8159333f: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fa580)
Location: block/blk-iocost.c:1046
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815fa580-ffffffff815fa5ef: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816ac920)
Location: block/blk-iocost.c:1045
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff816ac920-ffffffff816ac99b: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176b430)
Location: block/blk-iocost.c:1050
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff8176b430-ffffffff8176b4ab: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817aa590)
Location: block/blk-iocost.c:1066
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817aa590-ffffffff817aa60b: ioc_start_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ee340)
Location: block/blk-iocost.c:1066
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff817ee340-ffffffff817ee3bb: ioc_start_period (STB_LOCAL)
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
In block/blk-iocost.c (ffff800010614370)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffff800010614370-ffff80001061440c: ioc_start_period.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_start_period(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07befac)
Location: block/blk-iocost.c:876
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
c07befac-c07bf064: ioc_start_period (STB_LOCAL)
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
In block/blk-iocost.c (c0000000007b3d30)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
c0000000007b3d30-c0000000007b3de8: ioc_start_period.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffe00044bd10)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffe00044bd10-ffffffe00044bd9a: ioc_start_period.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff815094e0)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815094e0-ffffffff81509545: ioc_start_period.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff814f9990)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff814f9990-ffffffff814f99f5: ioc_start_period.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff81505570)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81505570-ffffffff815055d5: ioc_start_period.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff8151eeb0)
Location: block/blk-iocost.c:876
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8151eeb0-ffffffff8151ef15: ioc_start_period.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
