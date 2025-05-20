# Function: <code>iocg_kick_delay</code>

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
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150fb50)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff8150fb50-ffffffff8150fd1a: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570c50)
Location: block/blk-iocost.c:1210
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff81570c50-ffffffff81570de8: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158bb30)
Location: block/blk-iocost.c:1320
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff8158bb30-ffffffff8158bd6c: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815929f0)
Location: block/blk-iocost.c:1326
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff815929f0-ffffffff81592c2c: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1326
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff815f9e80-ffffffff815fa0ca: iocg_kick_delay (STB_LOCAL)
ffffffff81cd9d2a-ffffffff81cd9d49: iocg_kick_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1325
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff816ac130-ffffffff816ac36a: iocg_kick_delay (STB_LOCAL)
ffffffff81e8d80f-ffffffff81e8d82e: iocg_kick_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1330
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff8176b120-ffffffff8176b354: iocg_kick_delay (STB_LOCAL)
ffffffff82076da8-ffffffff82076dc7: iocg_kick_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1346
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff817aa200-ffffffff817aa434: iocg_kick_delay (STB_LOCAL)
ffffffff820f6c04-ffffffff820f6c23: iocg_kick_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1346
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_kick_waitq
```
**Symbols:**

```
ffffffff817edfc0-ffffffff817ee1ec: iocg_kick_delay (STB_LOCAL)
ffffffff821d4052-ffffffff821d4071: iocg_kick_delay.cold (STB_LOCAL)
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
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010615320)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffff800010615320-ffff800010615584: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07be3cc)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
c07be3cc-c07be760: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b2180)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
c0000000007b2180-c0000000007b2470: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044ad1e)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffe00044ad1e-ffffffe00044aea0: iocg_kick_delay (STB_LOCAL)
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
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508130)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff81508130-ffffffff815082fa: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f85e0)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff814f85e0-ffffffff814f87aa: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815041c0)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff815041c0-ffffffff8150438a: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool iocg_kick_delay(struct ioc_gq *iocg, struct ioc_now *now, u64 cost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151d770)
Location: block/blk-iocost.c:1215
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_delay_timer_fn
```
**Symbols:**

```
ffffffff8151d770-ffffffff8151d93a: iocg_kick_delay (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 cost</code>
</li>
</ul>
</details>
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
