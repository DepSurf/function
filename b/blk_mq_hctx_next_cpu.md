# Function: <code>blk_mq_hctx_next_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff813c37e0)
Location: block/blk-mq.c:835
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
**Symbols:**

```
ffffffff813c37e0-ffffffff813c3847: blk_mq_hctx_next_cpu.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8140737f)
Location: block/blk-mq.c:913
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
**Symbols:**

```
ffffffff814072e0-ffffffff81407347: blk_mq_hctx_next_cpu.part.23 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff81421b46)
Location: block/blk-mq.c:955
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff81421ab0-ffffffff81421b0a: blk_mq_hctx_next_cpu.part.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fb10)
Location: block/blk-mq.c:1127
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8142fb10-ffffffff8142fb91: blk_mq_hctx_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b1c0)
Location: block/blk-mq.c:1258
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8145b1c0-ffffffff8145b237: blk_mq_hctx_next_cpu (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8148e584)
Location: block/blk-mq.c:1284
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814a7f14)
Location: block/blk-mq.c:1408
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814d5dd4)
Location: block/blk-mq.c:1406
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814ef104)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff81550074)
Location: block/blk-mq.c:1443
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff8156c544)
Location: block/blk-mq.c:1534
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff81573f4c)
Location: block/blk-mq.c:1499
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff815d845c)
Location: block/blk-mq.c:1510
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684b7b)
Location: block/blk-mq.c:2033
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742618)
Location: block/blk-mq.c:2200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177ddfb)
Location: block/blk-mq.c:2171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c046b)
Location: block/blk-mq.c:2189
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffff8000105eec60)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (c079a60c)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (c000000000784220)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffe00042d6a0)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814e76e4)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814d7c54)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814e3774)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In block/blk-mq.c (ffffffff814fc874)
Location: block/blk-mq.c:1422
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
</ul>
