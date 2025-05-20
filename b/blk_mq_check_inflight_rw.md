# Function: <code>blk_mq_check_inflight_rw</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e2f0)
Location: block/blk-mq.c:118
Inline: True
```
**Symbols:**

```
ffffffff8148e2f0-ffffffff8148e31c: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7bc0)
Location: block/blk-mq.c:122
Inline: True
```
**Symbols:**

```
ffffffff814a7bc0-ffffffff814a7bf6: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5c80)
Location: block/blk-mq.c:124
Inline: True
```
**Symbols:**

```
ffffffff814d5c80-ffffffff814d5cb6: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eefb0)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffff814eefb0-ffffffff814eefe6: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed558)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffff8000105ed558-ffff8000105ed5c4: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a458)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
c079a458-c079a4a8: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007840b0)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
c0000000007840b0-c0000000007840f8: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d556)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffe00042d556-ffffffe00042d5a8: blk_mq_check_inflight_rw (STB_LOCAL)
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
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7590)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffff814e7590-ffffffff814e75c6: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7b00)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffff814d7b00-ffffffff814d7b36: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3620)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffff814e3620-ffffffff814e3656: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_check_inflight_rw(struct blk_mq_hw_ctx *hctx, struct request *rq, void *priv, bool reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc720)
Location: block/blk-mq.c:125
Inline: True
```
**Symbols:**

```
ffffffff814fc720-ffffffff814fc756: blk_mq_check_inflight_rw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
