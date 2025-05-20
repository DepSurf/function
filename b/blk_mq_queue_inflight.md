# Function: <code>blk_mq_queue_inflight</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7160)
Location: block/blk-mq.c:833
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814a7160-ffffffff814a71aa: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d50a0)
Location: block/blk-mq.c:832
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814d50a0-ffffffff814d50ea: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee380)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814ee380-ffffffff814ee3ca: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154dfe0)
Location: block/blk-mq.c:844
Inline: False
```
**Symbols:**

```
ffffffff8154dfe0-ffffffff8154e02a: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a480)
Location: block/blk-mq.c:894
Inline: False
```
**Symbols:**

```
ffffffff8156a480-ffffffff8156a4ca: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815723c0)
Location: block/blk-mq.c:868
Inline: False
```
**Symbols:**

```
ffffffff815723c0-ffffffff8157240a: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:874
Inline: False
```
**Symbols:**

```
ffffffff81cd8284-ffffffff81cd829f: blk_mq_queue_inflight.cold (STB_LOCAL)
ffffffff815d7280-ffffffff815d72d5: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1414
Inline: False
```
**Symbols:**

```
ffffffff81e8b734-ffffffff81e8b74f: blk_mq_queue_inflight.cold (STB_LOCAL)
ffffffff816832e0-ffffffff8168333f: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1541
Inline: False
```
**Symbols:**

```
ffffffff82075ecd-ffffffff82075ee8: blk_mq_queue_inflight.cold (STB_LOCAL)
ffffffff81740b30-ffffffff81740b8f: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1534
Inline: False
```
**Symbols:**

```
ffffffff820f5db9-ffffffff820f5dd4: blk_mq_queue_inflight.cold (STB_LOCAL)
ffffffff8177cd60-ffffffff8177cdbf: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1549
Inline: False
```
**Symbols:**

```
ffffffff821d32c3-ffffffff821d32de: blk_mq_queue_inflight.cold (STB_LOCAL)
ffffffff817bf190-ffffffff817bf1ef: blk_mq_queue_inflight (STB_GLOBAL)
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
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ecfb0)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffff8000105ecfb0-ffff8000105ed014: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c07994b4)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
c07994b4-c0799520: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782a70)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
c000000000782a70-c000000000782ae4: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ca1e)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffe00042ca1e-ffffffe00042ca5c: blk_mq_queue_inflight (STB_GLOBAL)
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
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6960)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814e6960-ffffffff814e69aa: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6ed0)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814d6ed0-ffffffff814d6f1a: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e29f0)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814e29f0-ffffffff814e2a3a: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_queue_inflight(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fb870)
Location: block/blk-mq.c:845
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff814fb870-ffffffff814fb8ba: blk_mq_queue_inflight (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
