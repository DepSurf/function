# Function: <code>scale_up</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff8144a398)
Location: block/blk-wbt.c:348
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81449e30-ffffffff81449e79: scale_up.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81458430)
Location: block/blk-wbt.c:340
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81458250-ffffffff8145828a: scale_up.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814841b1)
Location: block/blk-wbt.c:339
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81483fb0-ffffffff81483fea: scale_up.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814b92b2)
Location: block/blk-wbt.c:368
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814b8d90-ffffffff814b8dca: scale_up.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd1a0)
Location: block/blk-wbt.c:308
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814cd1a0-ffffffff814cd1f2: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fba20)
Location: block/blk-wbt.c:309
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff814fba20-ffffffff814fba78: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519b50)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81519b50-ffffffff81519bac: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157a320)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8157a320-ffffffff8157a3e4: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815971e0)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff815971e0-ffffffff815972a4: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dfa0)
Location: block/blk-wbt.c:310
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8159dfa0-ffffffff8159e064: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816066a0)
Location: block/blk-wbt.c:310
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff816066a0-ffffffff8160678a: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba6c0)
Location: block/blk-wbt.c:310
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff816ba6c0-ffffffff816ba7c6: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177ac90)
Location: block/blk-wbt.c:311
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8177ac90-ffffffff8177ad96: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba690)
Location: block/blk-wbt.c:379
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff817ba690-ffffffff817ba796: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fee00)
Location: block/blk-wbt.c:378
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff817fee00-ffffffff817fef03: scale_up (STB_LOCAL)
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
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010621810)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffff800010621810-ffff80001062192c: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c9104)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
c07c9104-c07c916c: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c16e0)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
c0000000007c16e0-c0000000007c17b4: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453b24)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffe000453b24-ffffffe000453b86: scale_up (STB_LOCAL)
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
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512130)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81512130-ffffffff8151218c: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502450)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff81502450-ffffffff815024ac: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e1c0)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8150e1c0-ffffffff8150e21c: scale_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scale_up(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815277e0)
Location: block/blk-wbt.c:309
Inline: True
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff815277e0-ffffffff815278e3: scale_up (STB_LOCAL)
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
