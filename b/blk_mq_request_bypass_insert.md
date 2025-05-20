# Function: <code>blk_mq_request_bypass_insert</code>

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
void blk_mq_request_bypass_insert(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431c90)
Location: block/blk-mq.c:1364
Inline: False
```
**Symbols:**

```
ffffffff81431c90-ffffffff81431cf8: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d7b0)
Location: block/blk-mq.c:1499
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff8145d7b0-ffffffff8145d822: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490fd0)
Location: block/blk-mq.c:1532
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff81490fd0-ffffffff8149104e: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa140)
Location: block/blk-mq.c:1657
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814aa140-ffffffff814aa1a2: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8110)
Location: block/blk-mq.c:1655
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814d8110-ffffffff814d8172: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f14a0)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814f14a0-ffffffff814f1528: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550e44)
Location: block/blk-mq.c:1741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81552550-ffffffff815525d8: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d4d0)
Location: block/blk-mq.c:1833
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff8156e6e0-ffffffff8156e768: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815753d0)
Location: block/blk-mq.c:1852
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff815762c0-ffffffff81576348: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da716)
Location: block/blk-mq.c:1863
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff815daeb0-ffffffff815daf38: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168969c)
Location: block/blk-mq.c:2377
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81688d80-ffffffff81688e30: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747b61)
Location: block/blk-mq.c:2520
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81747290-ffffffff81747340: blk_mq_request_bypass_insert (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff81782cf4)
Location: block/blk-mq.c:2447
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_requeue_work
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
In block/blk-mq.c (ffffffff817c5044)
Location: block/blk-mq.c:2467
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_requeue_work
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
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0ad0)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffff8000105f0ad0-ffff8000105f0bb8: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079cb44)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
c079cb44-c079cbd4: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787590)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
c000000000787590-c0000000007876c8: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f85e)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffe00042f85e-ffffffe00042f926: blk_mq_request_bypass_insert (STB_GLOBAL)
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
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9a80)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814e9a80-ffffffff814e9b08: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9fe0)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814d9fe0-ffffffff814da068: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5b10)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814e5b10-ffffffff814e5b98: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request *rq, bool at_head, bool run_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fea90)
Location: block/blk-mq.c:1671
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814fea90-ffffffff814feb24: blk_mq_request_bypass_insert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool run_queue</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool at_head</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, run_queue</code> ➡️ <code>rq, at_head, run_queue</code>
</li>
</ul>
</details>
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
