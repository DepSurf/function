# Function: <code>blk_mq_debugfs_register_hctx</code>

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
int blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a170)
Location: block/blk-mq-debugfs.c:863
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8145a170-ffffffff8145a2cc: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485ef0)
Location: block/blk-mq-debugfs.c:864
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81485ef0-ffffffff8148604c: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bae20)
Location: block/blk-mq-debugfs.c:890
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814bae20-ffffffff814baf7c: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cefe0)
Location: block/blk-mq-debugfs.c:929
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814cefe0-ffffffff814cf153: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fd870)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814fd870-ffffffff814fd97c: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151b7c0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8151b7c0-ffffffff8151b8cc: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157bf30)
Location: block/blk-mq-debugfs.c:880
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8157bf30-ffffffff8157c06a: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598fd0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81598fd0-ffffffff8159910a: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159fdd0)
Location: block/blk-mq-debugfs.c:874
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8159fdd0-ffffffff8159ff0a: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816085f0)
Location: block/blk-mq-debugfs.c:875
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff816085f0-ffffffff8160872a: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc010)
Location: block/blk-mq-debugfs.c:726
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff816bc010-ffffffff816bc1c9: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177c9a0)
Location: block/blk-mq-debugfs.c:726
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8177c9a0-ffffffff8177cb59: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc340)
Location: block/blk-mq-debugfs.c:700
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff817bc340-ffffffff817bc4f9: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800a00)
Location: block/blk-mq-debugfs.c:681
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81800a00-ffffffff81800bb9: blk_mq_debugfs_register_hctx (STB_GLOBAL)
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
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623df8)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffff800010623df8-ffff800010623f18: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb460)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c07cb460-c07cb574: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c47c0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c0000000007c47c0-c0000000007c4928: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455a28)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffe000455a28-ffffffe000455b12: blk_mq_debugfs_register_hctx (STB_GLOBAL)
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
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513da0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81513da0-ffffffff81513eac: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815040b0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815040b0-ffffffff815041bc: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150fe30)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8150fe30-ffffffff8150ff3c: blk_mq_debugfs_register_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815295f0)
Location: block/blk-mq-debugfs.c:876
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815295f0-ffffffff815296fc: blk_mq_debugfs_register_hctx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
