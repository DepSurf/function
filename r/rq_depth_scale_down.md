# Function: <code>rq_depth_scale_down</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814bda60)
Location: block/blk-rq-qos.c:160
Inline: False
Direct callers:
  - block/blk-wbt.c:scale_down
```
**Symbols:**

```
ffffffff814bda60-ffffffff814bda8e: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ec100)
Location: block/blk-rq-qos.c:162
Inline: False
Direct callers:
  - block/blk-wbt.c:scale_down
```
**Symbols:**

```
ffffffff814ec100-ffffffff814ec12e: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81505540)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
ffffffff81505540-ffffffff81505575: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565e80)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81565e80-ffffffff81565f31: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580e00)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81580e00-ffffffff81580eb1: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81588960)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81588960-ffffffff81588a16: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81cd9b34-ffffffff81cd9b56: rq_depth_scale_down.cold (STB_LOCAL)
ffffffff815ee650-ffffffff815ee723: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81e8d5c9-ffffffff81e8d5eb: rq_depth_scale_down.cold (STB_LOCAL)
ffffffff8169ef00-ffffffff8169eff4: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:177
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff82076be8-ffffffff82076c0a: rq_depth_scale_down.cold (STB_LOCAL)
ffffffff8175d7b0-ffffffff8175d8a4: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:177
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff820f6a06-ffffffff820f6a28: rq_depth_scale_down.cold (STB_LOCAL)
ffffffff8179c510-ffffffff8179c60a: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:177
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff821d3e54-ffffffff821d3e76: rq_depth_scale_down.cold (STB_LOCAL)
ffffffff817dff70-ffffffff817e006a: rq_depth_scale_down (STB_GLOBAL)
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
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff800010607688)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffff800010607688-ffff8000106076f0: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b2860)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
c07b2860-c07b28b0: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a4250)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
c0000000007a4250-c0000000007a42e8: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe00044224e)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
ffffffe00044224e-ffffffe0004422a2: rq_depth_scale_down (STB_GLOBAL)
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
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fdb20)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
ffffffff814fdb20-ffffffff814fdb55: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ee030)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
ffffffff814ee030-ffffffff814ee065: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f9bb0)
Location: block/blk-rq-qos.c:183
Inline: False
```
**Symbols:**

```
ffffffff814f9bb0-ffffffff814f9be5: rq_depth_scale_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rq_depth_scale_down(struct rq_depth *rqd, bool hard_throttle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512c10)
Location: block/blk-rq-qos.c:183
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81512c10-ffffffff81512c45: rq_depth_scale_down (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
