# Function: <code>__blk_mq_free_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_mq_free_request(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c2fc0)
Location: block/blk-mq.c:269
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813c2fc0-ffffffff813c3008: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __blk_mq_free_request(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406bf0)
Location: block/blk-mq.c:325
Inline: False
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_hctx_request
```
**Symbols:**

```
ffffffff81406bf0-ffffffff81406c38: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __blk_mq_free_request(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81420fc0)
Location: block/blk-mq.c:322
Inline: False
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_hctx_request
```
**Symbols:**

```
ffffffff81420fc0-ffffffff81421035: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148dbf0)
Location: block/blk-mq.c:471
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8148dbf0-ffffffff8148dc74: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a74c0)
Location: block/blk-mq.c:484
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814a74c0-ffffffff814a756a: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5410)
Location: block/blk-mq.c:481
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814d5410-ffffffff814d54c0: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee6f0)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814ee6f0-ffffffff814ee7a0: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e610)
Location: block/blk-mq.c:494
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8154e610-ffffffff8154e6cb: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a9d0)
Location: block/blk-mq.c:488
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8156a9d0-ffffffff8156aa8b: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572900)
Location: block/blk-mq.c:489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81572900-ffffffff815729bb: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d6f30)
Location: block/blk-mq.c:496
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff815d6f30-ffffffff815d6feb: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81682b40)
Location: block/blk-mq.c:604
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81682b40-ffffffff81682c14: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817401c0)
Location: block/blk-mq.c:710
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff817401c0-ffffffff81740294: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177eab0)
Location: block/blk-mq.c:699
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8177eab0-ffffffff8177ebca: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0050)
Location: block/blk-mq.c:705
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff817c0050-ffffffff817c016b: __blk_mq_free_request (STB_LOCAL)
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
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed380)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffff8000105ed380-ffff8000105ed428: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799868)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c0799868-c0799908: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783140)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c000000000783140-c000000000783240: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cd00)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffe00042cd00-ffffffe00042cdac: __blk_mq_free_request (STB_LOCAL)
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
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6cd0)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814e6cd0-ffffffff814e6d80: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7240)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814d7240-ffffffff814d72f0: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2d60)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814e2d60-ffffffff814e2e10: __blk_mq_free_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbbe0)
Location: block/blk-mq.c:492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814fbbe0-ffffffff814fbc90: __blk_mq_free_request (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
