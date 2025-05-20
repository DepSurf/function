# Function: <code>blk_mq_hctx_has_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4e3a)
Location: block/blk-mq.c:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140900a)
Location: block/blk-mq.c:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814239df)
Location: block/blk-mq.c:42
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_mq_hctx_has_pending(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430b60)
Location: block/blk-mq.c:63
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
```
**Symbols:**

```
ffffffff81430b60-ffffffff81430bbe: blk_mq_hctx_has_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b2f6)
Location: block/blk-mq.c:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e70f)
Location: block/blk-mq.c:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a809c)
Location: block/blk-mq.c:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6c12)
Location: block/blk-mq.c:66
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eff92)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815502a2)
Location: block/blk-mq.c:68
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c734)
Location: block/blk-mq.c:70
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815741c4)
Location: block/blk-mq.c:70
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d870e)
Location: block/blk-mq.c:70
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_hctx_has_pending(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81682ec0)
Location: block/blk-mq.c:99
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff81682ec0-ffffffff81682f3d: blk_mq_hctx_has_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_hctx_has_pending(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817406b0)
Location: block/blk-mq.c:100
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff817406b0-ffffffff8174072d: blk_mq_hctx_has_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_hctx_has_pending(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177c890)
Location: block/blk-mq.c:59
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff8177c890-ffffffff8177c90d: blk_mq_hctx_has_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_hctx_has_pending(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bec90)
Location: block/blk-mq.c:59
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff817bec90-ffffffff817bed0d: blk_mq_hctx_has_pending (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eeea0)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b7d8)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785910)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e2d8)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8572)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8ae2)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4602)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fca59)
Location: block/blk-mq.c:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
