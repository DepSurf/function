# Function: <code>blk_mq_try_issue_directly</code>

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
void blk_mq_try_issue_directly(struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424ce0)
Location: block/blk-mq.c:1299
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81424ce0-ffffffff81424dd8: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431230)
Location: block/blk-mq.c:1536
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81431230-ffffffff814312aa: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145cc20)
Location: block/blk-mq.c:1673
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8145cc20-ffffffff8145cc9a: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490480)
Location: block/blk-mq.c:1719
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81490480-ffffffff81490536: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa690)
Location: block/blk-mq.c:1808
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814aa690-ffffffff814aa954: blk_mq_try_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8340)
Location: block/blk-mq.c:1854
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814d8340-ffffffff814d8409: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f16f0)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f16f0-ffffffff814f17bb: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550db0)
Location: block/blk-mq.c:1934
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81550db0-ffffffff81550eaf: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d460)
Location: block/blk-mq.c:2031
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8156d460-ffffffff8156d533: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575360)
Location: block/blk-mq.c:2055
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81575360-ffffffff81575433: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da680)
Location: block/blk-mq.c:2066
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815da680-ffffffff815da784: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81688190)
Location: block/blk-mq.c:2531
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81688190-ffffffff81688239: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817465d0)
Location: block/blk-mq.c:2674
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff817465d0-ffffffff81746691: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817839a0)
Location: block/blk-mq.c:2632
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff817839a0-ffffffff81783a90: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c5d10)
Location: block/blk-mq.c:2654
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff817c5d10-ffffffff817c5e04: blk_mq_try_issue_directly (STB_LOCAL)
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0d78)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105f0d78-ffff8000105f0e5c: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079cdb4)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c079cdb4-c079cecc: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787990)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c000000000787990-c000000000787ae8: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042fa74)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe00042fa74-ffffffe00042fb42: blk_mq_try_issue_directly (STB_LOCAL)
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9cd0)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e9cd0-ffffffff814e9d9b: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da230)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814da230-ffffffff814da2fb: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5d60)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e5d60-ffffffff814e5e2b: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fecf0)
Location: block/blk-mq.c:1874
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814fecf0-ffffffff814fed91: blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, cookie</code> ➡️ <code>hctx, rq, cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bypass</code>
</li>
<li>
<b>Param added. </b>
<code>bool last</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool bypass</code>
</li>
<li>
<b>Param removed. </b>
<code>bool last</code>
</li>
<li>
<b>Return type changed. </b>
<code>blk_status_t</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>blk_qc_t *cookie</code>
</li>
</ul>
</details>
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
