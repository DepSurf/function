# Function: <code>blk_mq_hctx_mark_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c2d80)
Location: block/blk-mq.c:64
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_hctx_notify
```
**Symbols:**

```
ffffffff813c2d80-ffffffff813c2dc2: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406980)
Location: block/blk-mq.c:64
Inline: False
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
```
**Symbols:**

```
ffffffff81406980-ffffffff814069b7: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81421860)
Location: block/blk-mq.c:50
Inline: True
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
```
**Symbols:**

```
ffffffff81421860-ffffffff8142189e: blk_mq_hctx_mark_pending.isra.26 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8142ff50)
Location: block/blk-mq.c:73
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff8142ff50-ffffffff8142ff8f: blk_mq_hctx_mark_pending.isra.28 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8145b8d0)
Location: block/blk-mq.c:74
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff8145b8d0-ffffffff8145b90f: blk_mq_hctx_mark_pending.isra.33 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8148e370)
Location: block/blk-mq.c:74
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff8148e370-ffffffff8148e3af: blk_mq_hctx_mark_pending.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7430)
Location: block/blk-mq.c:74
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814a7430-ffffffff814a747f: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5be0)
Location: block/blk-mq.c:76
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814d5be0-ffffffff814d5c50: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eef10)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814eef10-ffffffff814eef80: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f7d0)
Location: block/blk-mq.c:78
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff8154f7d0-ffffffff8154f842: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156bbb0)
Location: block/blk-mq.c:80
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff8156bbb0-ffffffff8156bc22: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815733b0)
Location: block/blk-mq.c:80
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff815733b0-ffffffff81573428: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:80
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff815d7c30-ffffffff815d7d0a: blk_mq_hctx_mark_pending (STB_LOCAL)
ffffffff81cd829f-ffffffff81cd834e: blk_mq_hctx_mark_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:109
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff816842a0-ffffffff81684384: blk_mq_hctx_mark_pending (STB_LOCAL)
ffffffff81e8b8d2-ffffffff81e8b971: blk_mq_hctx_mark_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:110
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff81741d50-ffffffff81741e34: blk_mq_hctx_mark_pending (STB_LOCAL)
ffffffff82075f8e-ffffffff8207602d: blk_mq_hctx_mark_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:69
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff8177d5f0-ffffffff8177d6d4: blk_mq_hctx_mark_pending (STB_LOCAL)
ffffffff820f5e17-ffffffff820f5ea6: blk_mq_hctx_mark_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:69
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff817bf980-ffffffff817bfa64: blk_mq_hctx_mark_pending (STB_LOCAL)
ffffffff821d3321-ffffffff821d33b0: blk_mq_hctx_mark_pending.cold (STB_LOCAL)
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105edd88)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffff8000105edd88-ffff8000105ede28: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a2d4)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
c079a2d4-c079a334: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782830)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
c000000000782830-c0000000007828a8: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042c80a)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffe00042c80a-ffffffe00042c88a: blk_mq_hctx_mark_pending (STB_LOCAL)
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e74f0)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814e74f0-ffffffff814e7560: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7a60)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814d7a60-ffffffff814d7ad0: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3580)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814e3580-ffffffff814e35f0: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc5a0)
Location: block/blk-mq.c:77
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
**Symbols:**

```
ffffffff814fc5a0-ffffffff814fc610: blk_mq_hctx_mark_pending (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
