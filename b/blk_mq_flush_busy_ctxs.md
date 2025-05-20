# Function: <code>blk_mq_flush_busy_ctxs</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430a90)
Location: block/blk-mq.c:838
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81430a90-ffffffff81430b60: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c210)
Location: block/blk-mq.c:911
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8145c210-ffffffff8145c318: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148fc40)
Location: block/blk-mq.c:909
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8148fc40-ffffffff8148fd4f: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9450)
Location: block/blk-mq.c:982
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814a9450-ffffffff814a9560: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d71c0)
Location: block/blk-mq.c:981
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814d71c0-ffffffff814d72d0: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0540)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814f0540-ffffffff814f0650: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550860)
Location: block/blk-mq.c:996
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81550860-ffffffff81550973: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156cfa0)
Location: block/blk-mq.c:1046
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8156cfa0-ffffffff8156d0b3: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574fd0)
Location: block/blk-mq.c:1004
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81574fd0-ffffffff815750e2: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1010
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81cd83a7-ffffffff81cd83fc: blk_mq_flush_busy_ctxs.cold (STB_LOCAL)
ffffffff815d9450-ffffffff815d957f: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1549
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81e8b9c6-ffffffff81e8ba6a: blk_mq_flush_busy_ctxs.cold (STB_LOCAL)
ffffffff81685fc0-ffffffff81686163: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1710
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff82076097-ffffffff8207613b: blk_mq_flush_busy_ctxs.cold (STB_LOCAL)
ffffffff81744100-ffffffff81744298: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1703
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff820f5f10-ffffffff820f5fb4: blk_mq_flush_busy_ctxs.cold (STB_LOCAL)
ffffffff8177fb20-ffffffff8177fcb8: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1718
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff821d345d-ffffffff821d3501: blk_mq_flush_busy_ctxs.cold (STB_LOCAL)
ffffffff817c2600-ffffffff817c2798: blk_mq_flush_busy_ctxs (STB_GLOBAL)
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
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee0b8)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffff8000105ee0b8-ffff8000105ee1dc: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b650)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
c079b650-c079b760: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007856f0)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
c0000000007856f0-c00000000078588c: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e94a)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffe00042e94a-ffffffe00042ea36: blk_mq_flush_busy_ctxs (STB_GLOBAL)
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
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8b20)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814e8b20-ffffffff814e8c30: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9090)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814d9090-ffffffff814d91a0: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4bb0)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814e4bb0-ffffffff814e4cc0: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_flush_busy_ctxs(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fdbb0)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814fdbb0-ffffffff814fdcc0: blk_mq_flush_busy_ctxs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
