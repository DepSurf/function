# Function: <code>blk_mq_check_inflight</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b830)
Location: block/blk-mq.c:92
Inline: True
```
**Symbols:**

```
ffffffff8145b830-ffffffff8145b875: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e2b0)
Location: block/blk-mq.c:92
Inline: True
```
**Symbols:**

```
ffffffff8148e2b0-ffffffff8148e2e5: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7b90)
Location: block/blk-mq.c:96
Inline: True
```
**Symbols:**

```
ffffffff814a7b90-ffffffff814a7bba: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5c50)
Location: block/blk-mq.c:98
Inline: True
```
**Symbols:**

```
ffffffff814d5c50-ffffffff814d5c7a: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eef80)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffff814eef80-ffffffff814eefaa: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154ea90)
Location: block/blk-mq.c:100
Inline: True
```
**Symbols:**

```
ffffffff8154ea90-ffffffff8154eabe: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156af70)
Location: block/blk-mq.c:102
Inline: True
```
**Symbols:**

```
ffffffff8156af70-ffffffff8156afb2: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572d70)
Location: block/blk-mq.c:102
Inline: True
```
**Symbols:**

```
ffffffff81572d70-ffffffff81572db2: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7410)
Location: block/blk-mq.c:102
Inline: True
```
**Symbols:**

```
ffffffff815d7410-ffffffff815d7452: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_check_inflight(struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81682560)
Location: block/blk-mq.c:131
Inline: False
```
**Symbols:**

```
ffffffff81682560-ffffffff816825bf: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_check_inflight(struct request *rq, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8173fc10)
Location: block/blk-mq.c:132
Inline: False
```
**Symbols:**

```
ffffffff8173fc10-ffffffff8173fc6f: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_check_inflight(struct request *rq, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177c130)
Location: block/blk-mq.c:91
Inline: False
```
**Symbols:**

```
ffffffff8177c130-ffffffff8177c18c: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_check_inflight(struct request *rq, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817be520)
Location: block/blk-mq.c:91
Inline: False
```
**Symbols:**

```
ffffffff817be520-ffffffff817be57c: blk_mq_check_inflight (STB_LOCAL)
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
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed4f8)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffff8000105ed4f8-ffff8000105ed554: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a420)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
c079a420-c079a458: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784070)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
c000000000784070-c0000000007840a8: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d50e)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffe00042d50e-ffffffe00042d556: blk_mq_check_inflight (STB_LOCAL)
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
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7560)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffff814e7560-ffffffff814e758a: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7ad0)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffff814d7ad0-ffffffff814d7afa: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e35f0)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffff814e35f0-ffffffff814e361a: blk_mq_check_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc6f0)
Location: block/blk-mq.c:99
Inline: True
```
**Symbols:**

```
ffffffff814fc6f0-ffffffff814fc71a: blk_mq_check_inflight (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, rq, priv, reserved</code> ➡️ <code>rq, priv, reserved</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool reserved</code>
</li>
</ul>
</details>
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
