# Function: <code>blk_mq_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4640)
Location: block/blk-mq.c:856
Inline: True
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq-tag.c:bt_get
```
**Symbols:**

```
ffffffff813c4640-ffffffff813c46e5: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814087d0)
Location: block/blk-mq.c:934
Inline: True
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-tag.c:bt_get
```
**Symbols:**

```
ffffffff814087d0-ffffffff81408871: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814234c0)
Location: block/blk-mq.c:974
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814234c0-ffffffff81423538: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814304e7)
Location: block/blk-mq.c:1177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814302e0-ffffffff814302f6: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b2f0)
Location: block/blk-mq.c:1308
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff8145b2f0-ffffffff8145b373: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e6d0)
Location: block/blk-mq.c:1351
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff8148e6d0-ffffffff8148e7ef: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8060)
Location: block/blk-mq.c:1475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814a8060-ffffffff814a8179: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6b70)
Location: block/blk-mq.c:1473
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814d6b70-ffffffff814d6c8d: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814efef0)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814efef0-ffffffff814f000d: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550210)
Location: block/blk-mq.c:1535
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff81550210-ffffffff81550317: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c6e0)
Location: block/blk-mq.c:1626
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff8156c6e0-ffffffff8156c7b7: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574170)
Location: block/blk-mq.c:1591
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff81574170-ffffffff81574247: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8680)
Location: block/blk-mq.c:1602
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff815d8680-ffffffff815d8796: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684e20)
Location: block/blk-mq.c:2125
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
**Symbols:**

```
ffffffff81684e20-ffffffff81684f3a: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742910)
Location: block/blk-mq.c:2288
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
**Symbols:**

```
ffffffff81742910-ffffffff81742a3e: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e050)
Location: block/blk-mq.c:2236
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
**Symbols:**

```
ffffffff8177e050-ffffffff8177e258: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c06c0)
Location: block/blk-mq.c:2254
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
**Symbols:**

```
ffffffff817c06c0-ffffffff817c08c2: blk_mq_run_hw_queue (STB_GLOBAL)
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eee40)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffff8000105eee40-ffff8000105eef68: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b760)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
c079b760-c079b8b0: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785890)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
c000000000785890-c000000000785a7c: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e288)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffe00042e288-ffffffe00042e36e: blk_mq_run_hw_queue (STB_GLOBAL)
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e84d0)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814e84d0-ffffffff814e85ed: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8a40)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814d8a40-ffffffff814d8b5d: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4560)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814e4560-ffffffff814e467d: blk_mq_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc9f0)
Location: block/blk-mq.c:1489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
**Symbols:**

```
ffffffff814fc9f0-ffffffff814fcad9: blk_mq_run_hw_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
