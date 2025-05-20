# Function: <code>blk_mq_dispatch_rq_list</code>

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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81423540)
Location: block/blk-mq.c:815
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_process_rq_list
```
**Symbols:**

```
ffffffff81423540-ffffffff81423749: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431880)
Location: block/blk-mq.c:983
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81431880-ffffffff81431bb0: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d210)
Location: block/blk-mq.c:1077
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff8145d210-ffffffff8145d6cd: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490a00)
Location: block/blk-mq.c:1083
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81490a00-ffffffff81490eed: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9b50)
Location: block/blk-mq.c:1197
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814a9b50-ffffffff814aa044: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1195
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814daca3-ffffffff814dacba: blk_mq_dispatch_rq_list.cold (STB_LOCAL)
ffffffff814d7ae0-ffffffff814d8014: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0e60)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814f0e60-ffffffff814f13a6: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551f70)
Location: block/blk-mq.c:1210
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81551f70-ffffffff8155245e: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156e0a0)
Location: block/blk-mq.c:1348
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff8156e0a0-ffffffff8156e60e: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575bf0)
Location: block/blk-mq.c:1312
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81575bf0-ffffffff815761e5: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da790)
Location: block/blk-mq.c:1318
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff815da790-ffffffff815dad8a: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81688590)
Location: block/blk-mq.c:1847
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81688590-ffffffff81688c28: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81746a70)
Location: block/blk-mq.c:2013
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81746a70-ffffffff81747118: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81783cd0)
Location: block/blk-mq.c:2013
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81783cd0-ffffffff81784217: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx *hctx, struct list_head *list, unsigned int nr_budgets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c6010)
Location: block/blk-mq.c:2031
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff817c6010-ffffffff817c652e: blk_mq_dispatch_rq_list (STB_GLOBAL)
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
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0338)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffff8000105f0338-ffff8000105f09b0: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c464)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
c079c464-c079ca4c: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786bb0)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
c000000000786bb0-c000000000787410: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f21a)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffe00042f21a-ffffffe00042f778: blk_mq_dispatch_rq_list (STB_GLOBAL)
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
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9440)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814e9440-ffffffff814e9986: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d99b0)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814d99b0-ffffffff814d9eea: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e54d0)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814e54d0-ffffffff814e5a16: blk_mq_dispatch_rq_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct request_queue *q, struct list_head *list, bool got_budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe430)
Location: block/blk-mq.c:1211
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff814fe430-ffffffff814fe977: blk_mq_dispatch_rq_list (STB_GLOBAL)
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
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool got_budget</code>
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_budgets</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>bool got_budget</code>
</li>
</ul>
</details>
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
