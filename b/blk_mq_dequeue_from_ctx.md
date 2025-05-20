# Function: <code>blk_mq_dequeue_from_ctx</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c810)
Location: block/blk-mq.c:946
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff8145c810-ffffffff8145c94f: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490070)
Location: block/blk-mq.c:944
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff81490070-ffffffff814901b1: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a98e0)
Location: block/blk-mq.c:1018
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814a98e0-ffffffff814a9a31: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7880)
Location: block/blk-mq.c:1017
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814d7880-ffffffff814d79d2: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0c00)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814f0c00-ffffffff814f0d52: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551e10)
Location: block/blk-mq.c:1032
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff81551e10-ffffffff81551f6e: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156df40)
Location: block/blk-mq.c:1082
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff8156df40-ffffffff8156e09e: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575a80)
Location: block/blk-mq.c:1040
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff81575a80-ffffffff81575be4: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1046
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff81cd84a8-ffffffff81cd8515: blk_mq_dequeue_from_ctx.cold (STB_LOCAL)
ffffffff815d9fa0-ffffffff815da139: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1585
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff81e8bb40-ffffffff81e8bc0b: blk_mq_dequeue_from_ctx.cold (STB_LOCAL)
ffffffff81687a10-ffffffff81687c12: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1746
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff820761c7-ffffffff82076291: blk_mq_dequeue_from_ctx.cold (STB_LOCAL)
ffffffff81745dd0-ffffffff81745fba: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1739
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff820f603d-ffffffff820f611f: blk_mq_dequeue_from_ctx.cold (STB_LOCAL)
ffffffff817825e0-ffffffff817827f6: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1754
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff821d3547-ffffffff821d3629: blk_mq_dequeue_from_ctx.cold (STB_LOCAL)
ffffffff817c4980-ffffffff817c4b96: blk_mq_dequeue_from_ctx (STB_GLOBAL)
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
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0068)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffff8000105f0068-ffff8000105f01e4: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c1d0)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
c079c1d0-c079c324: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786800)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
c000000000786800-c000000000786a08: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f01c)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffe00042f01c-ffffffe00042f144: blk_mq_dequeue_from_ctx (STB_GLOBAL)
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
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e91e0)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814e91e0-ffffffff814e9332: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9750)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814d9750-ffffffff814d98a2: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5270)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814e5270-ffffffff814e53c2: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *blk_mq_dequeue_from_ctx(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe1d0)
Location: block/blk-mq.c:1033
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
```
**Symbols:**

```
ffffffff814fe1d0-ffffffff814fe322: blk_mq_dequeue_from_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
