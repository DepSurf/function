# Function: <code>blk_mq_insert_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c6200)
Location: block/blk-mq.c:995
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff813c6200-ffffffff813c62b1: blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140a190)
Location: block/blk-mq.c:1074
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff8140a190-ffffffff8140a2a5: blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424bc0)
Location: block/blk-mq.c:1138
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff81424bc0-ffffffff81424cda: blk_mq_insert_request (STB_GLOBAL)
```
</details>
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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_insert_request(struct request *rq, blk_insert_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81780270)
Location: block/blk-mq.c:2494
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81780270-ffffffff817804a5: blk_mq_insert_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_insert_request(struct request *rq, blk_insert_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c2840)
Location: block/blk-mq.c:2516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff817c2840-ffffffff817c2a75: blk_mq_insert_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
