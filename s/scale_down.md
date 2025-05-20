# Function: <code>scale_down</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81449dd0)
Location: block/blk-wbt.c:371
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81449dd0-ffffffff81449e30: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458543)
Location: block/blk-wbt.c:362
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814842c3)
Location: block/blk-wbt.c:361
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b941a)
Location: block/blk-wbt.c:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd200)
Location: block/blk-wbt.c:317
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814cd200-ffffffff814cd24e: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fba80)
Location: block/blk-wbt.c:318
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814fba80-ffffffff814fbad4: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519bb0)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81519bb0-ffffffff81519c08: scale_down (STB_LOCAL)
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
In block/blk-wbt.c (ffffffff8157aa01)
Location: block/blk-wbt.c:319
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81597543)
Location: block/blk-wbt.c:319
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8159e7ac)
Location: block/blk-wbt.c:320
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81606f13)
Location: block/blk-wbt.c:320
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff816baa9d)
Location: block/blk-wbt.c:320
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8177b03e)
Location: block/blk-wbt.c:321
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817bab60)
Location: block/blk-wbt.c:389
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817ff2cd)
Location: block/blk-wbt.c:388
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffff800010622000)
Location: block/blk-wbt.c:319
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffff800010621700-ffff80001062180c: scale_down.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c916c)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
c07c916c-c07c91cc: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c17c0)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
c0000000007c17c0-c0000000007c1884: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453b86)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffe000453b86-ffffffe000453be6: scale_down (STB_LOCAL)
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
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512190)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81512190-ffffffff815121e8: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815024b0)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff815024b0-ffffffff81502508: scale_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scale_down(struct rq_wb *rwb, bool hard_throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e220)
Location: block/blk-wbt.c:319
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8150e220-ffffffff8150e278: scale_down (STB_LOCAL)
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
In block/blk-wbt.c (ffffffff81528003)
Location: block/blk-wbt.c:319
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff815278f0-ffffffff815279db: scale_down.part.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
</ul>
