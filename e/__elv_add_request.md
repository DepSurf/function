# Function: <code>__elv_add_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3f70)
Location: block/elevator.c:593
Inline: False
Direct callers:
  - block/elevator.c:elv_requeue_request
  - block/elevator.c:elv_add_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff813b3f70-ffffffff813b4221: __elv_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7c50)
Location: block/elevator.c:592
Inline: False
Direct callers:
  - block/elevator.c:elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff813f7c50-ffffffff813f7f04: __elv_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411680)
Location: block/elevator.c:590
Inline: False
Direct callers:
  - block/elevator.c:elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81411680-ffffffff8141192d: __elv_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f270)
Location: block/elevator.c:633
Inline: False
Direct callers:
  - block/elevator.c:elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff8141f270-ffffffff8141f491: __elv_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449d50)
Location: block/elevator.c:650
Inline: False
Direct callers:
  - block/elevator.c:elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81449d50-ffffffff81449f88: __elv_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __elv_add_request(struct request_queue *q, struct request *rq, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:619
Inline: False
Direct callers:
  - block/elevator.c:elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_queue_bio
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff8147d78d-ffffffff8147d7a5: __elv_add_request.cold.32 (STB_LOCAL)
ffffffff8147caa0-ffffffff8147ccf2: __elv_add_request (STB_GLOBAL)
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
