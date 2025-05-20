# Function: <code>__blk_mq_get_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4adb)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_insert_request
```
```
In block/blk-mq-tag.c (ffffffff813c72d5)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140a08e)
Location: block/blk-mq.h:75
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff8140b505)
Location: block/blk-mq.h:75
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424a86)
Location: block/blk-mq.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-mq-tag.c (ffffffff81425b45)
Location: block/blk-mq.h:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814303d6)
Location: block/blk-mq.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81433b9a)
Location: block/blk-mq.h:86
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81435857)
Location: block/blk-mq.h:86
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c486)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8145f85a)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814615e7)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148fd8d)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814930f2)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81495000)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9684)
Location: block/blk-mq.h:142
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad045)
Location: block/blk-mq.h:142
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814af071)
Location: block/blk-mq.h:142
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d74e4)
Location: block/blk-mq.h:140
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814db32c)
Location: block/blk-mq.h:140
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814dd336)
Location: block/blk-mq.h:140
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0864)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814f475c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814f67a6)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551512)
Location: block/blk-mq.h:131
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff81554f2c)
Location: block/blk-mq.h:131
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81557255)
Location: block/blk-mq.h:131
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d652)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815715e4)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815738e6)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815754b2)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff81579614)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8157b99d)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9a86)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815de814)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815e0d02)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687402)
Location: block/blk-mq.h:132
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8168ca6d)
Location: block/blk-mq.h:132
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8168f898)
Location: block/blk-mq.h:132
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745662)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8174b25d)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8174e3e8)
Location: block/blk-mq.h:133
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817815e2)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8178797d)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8178a928)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c35c2)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817ca04d)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff817cd078)
Location: block/blk-mq.h:129
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ef3fc)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4534)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffff8000105f6dc8)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bc40)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a018c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c07a2588)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785fbc)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078bd3c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c00000000078f258)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ec7c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe0004324d4)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffe00043457c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8e44)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ecd3c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eed86)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d93b4)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814dd28c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814df2c6)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4ed4)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814e8dcc)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eae16)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fdd04)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501d6c)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81503df7)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
</ul>

## Differences
