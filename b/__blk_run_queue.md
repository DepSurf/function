# Function: <code>__blk_run_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5420)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-core.c:blk_post_runtime_resume
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff813b5420-ffffffff813b545e: __blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa2a0)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:blk_post_runtime_resume
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff813fa2a0-ffffffff813fa2de: __blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413c20)
Location: block/blk-core.c:338
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:blk_post_runtime_resume
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff81413c20-ffffffff81413c5e: __blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422390)
Location: block/blk-core.c:388
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff81422390-ffffffff814223ec: __blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d470)
Location: block/blk-core.c:421
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff8144d470-ffffffff8144d4ce: __blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480720)
Location: block/blk-core.c:482
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_run_queue
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_delay_work
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/cfq-iosched.c:cfq_kick_queue
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff81480720-ffffffff8148077e: __blk_run_queue (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
