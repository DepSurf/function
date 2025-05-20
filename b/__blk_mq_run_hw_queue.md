# Function: <code>__blk_mq_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c46f0)
Location: block/blk-mq.c:722
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_delay_work_fn
  - block/blk-mq.c:blk_mq_run_work_fn
```
**Symbols:**

```
ffffffff813c46f0-ffffffff813c4a66: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81408880)
Location: block/blk-mq.c:799
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_delay_work_fn
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81408880-ffffffff81408c0a: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814238c0)
Location: block/blk-mq.c:931
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_delay_work_fn
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff814238c0-ffffffff81423949: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814301b0)
Location: block/blk-mq.c:1101
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814301b0-ffffffff8143023b: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b0b0)
Location: block/blk-mq.c:1204
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8145b0b0-ffffffff8145b183: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e050)
Location: block/blk-mq.c:1227
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8148e050-ffffffff8148e12d: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a78f0)
Location: block/blk-mq.c:1351
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814a78f0-ffffffff814a79cd: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5930)
Location: block/blk-mq.c:1349
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814d5930-ffffffff814d5a40: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eec60)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814eec60-ffffffff814eed70: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154ff00)
Location: block/blk-mq.c:1386
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8154ff00-ffffffff8155001b: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b9c0)
Location: block/blk-mq.c:1502
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8156b9c0-ffffffff8156ba2b: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573690)
Location: block/blk-mq.c:1467
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff81573690-ffffffff815736fb: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8070)
Location: block/blk-mq.c:1478
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff815d8070-ffffffff815d811a: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816833e0)
Location: block/blk-mq.c:2006
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff816833e0-ffffffff8168348a: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817405a0)
Location: block/blk-mq.c:2173
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff817405a0-ffffffff8174065d: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee2f8)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffff8000105ee2f8-ffff8000105ee458: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a06c)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
c079a06c-c079a220: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783a10)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
c000000000783a10-c000000000783bf0: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d218)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffe00042d218-ffffffe00042d34c: __blk_mq_run_hw_queue (STB_LOCAL)
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7240)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814e7240-ffffffff814e7350: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d77b0)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814d77b0-ffffffff814d78c0: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e32d0)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814e32d0-ffffffff814e33e0: __blk_mq_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc1f0)
Location: block/blk-mq.c:1365
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff814fc1f0-ffffffff814fc2cd: __blk_mq_run_hw_queue (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
