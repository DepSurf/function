# Function: <code>queue_set_hctx_shared</code>

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
In block/blk-mq.c (ffffffff813c4f49)
Location: block/blk-mq.c:1876
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814094de)
Location: block/blk-mq.c:1900
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff81423eec)
Location: block/blk-mq.c:1947
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142ed30)
Location: block/blk-mq.c:2131
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
```
**Symbols:**

```
ffffffff8142ed30-ffffffff8142ed9c: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a1c0)
Location: block/blk-mq.c:2269
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
```
**Symbols:**

```
ffffffff8145a1c0-ffffffff8145a22e: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148d840)
Location: block/blk-mq.c:2332
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
```
**Symbols:**

```
ffffffff8148d840-ffffffff8148d8ad: queue_set_hctx_shared (STB_LOCAL)
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
In block/blk-mq.c (ffffffff814abf29)
Location: block/blk-mq.c:2518
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff814da199)
Location: block/blk-mq.c:2562
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff814f354a)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff81553a2b)
Location: block/blk-mq.c:2773
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff815700ee)
Location: block/blk-mq.c:2878
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_shared
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
In block/blk-mq.c (ffffffff8157809a)
Location: block/blk-mq.c:2938
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_shared
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7650)
Location: block/blk-mq.c:2994
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815d7650-ffffffff815d76c8: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683c30)
Location: block/blk-mq.c:3764
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81683c30-ffffffff81683cff: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817413e0)
Location: block/blk-mq.c:3928
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817413e0-ffffffff817414af: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177d390)
Location: block/blk-mq.c:3940
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8177d390-ffffffff8177d461: queue_set_hctx_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue *q, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bf720)
Location: block/blk-mq.c:3956
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817bf720-ffffffff817bf7f1: queue_set_hctx_shared (STB_LOCAL)
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
In block/blk-mq.c (ffff8000105f2d44)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (c079ee8c)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (c00000000078a288)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffe00043155a)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff814ebb2a)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff814dc07a)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff814e7bba)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
In block/blk-mq.c (ffffffff81500b5a)
Location: block/blk-mq.c:2581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_tag_set_depth
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
