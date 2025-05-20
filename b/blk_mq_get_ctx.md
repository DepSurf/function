# Function: <code>blk_mq_get_ctx</code>

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
In block/blk-mq.c (ffffffff813c4ad4)
Location: block/blk-mq.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_insert_request
```
```
In block/blk-mq-tag.c (ffffffff813c72ce)
Location: block/blk-mq.h:86
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
In block/blk-mq.c (ffffffff81408dc3)
Location: block/blk-mq.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff8140b4fe)
Location: block/blk-mq.h:87
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
In block/blk-mq.c (ffffffff814221c2)
Location: block/blk-mq.h:76
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-mq-tag.c (ffffffff81425b3e)
Location: block/blk-mq.h:76
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
In block/blk-mq.c (ffffffff8142f11a)
Location: block/blk-mq.h:98
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81433b93)
Location: block/blk-mq.h:98
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81435850)
Location: block/blk-mq.h:98
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
In block/blk-mq.c (ffffffff8145a659)
Location: block/blk-mq.h:100
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8145f853)
Location: block/blk-mq.h:100
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814615e0)
Location: block/blk-mq.h:100
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
In block/blk-mq.c (ffffffff8148ebb9)
Location: block/blk-mq.h:113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814930eb)
Location: block/blk-mq.h:113
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81494ff9)
Location: block/blk-mq.h:113
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
In block/blk-mq.c (ffffffff814a85c2)
Location: block/blk-mq.h:154
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad03e)
Location: block/blk-mq.h:154
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814af06a)
Location: block/blk-mq.h:154
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
In block/blk-mq.c (ffffffff814d6000)
Location: block/blk-mq.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814db325)
Location: block/blk-mq.h:152
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814dd32f)
Location: block/blk-mq.h:152
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
In block/blk-mq.c (ffffffff814ef347)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814f4755)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814f679f)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffff8154ed18)
Location: block/blk-mq.h:143
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff81554f25)
Location: block/blk-mq.h:143
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8155724e)
Location: block/blk-mq.h:143
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
In block/blk-mq.c (ffffffff8156b43c)
Location: block/blk-mq.h:145
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815715dd)
Location: block/blk-mq.h:145
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815738df)
Location: block/blk-mq.h:145
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
In block/blk-mq.c (ffffffff815730a8)
Location: block/blk-mq.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff8157960d)
Location: block/blk-mq.h:146
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8157b996)
Location: block/blk-mq.h:146
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
In block/blk-mq.c (ffffffff815d77fc)
Location: block/blk-mq.h:148
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815de80d)
Location: block/blk-mq.h:148
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815e0cfb)
Location: block/blk-mq.h:148
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
In block/blk-mq.c (ffffffff81684dc8)
Location: block/blk-mq.h:144
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8168ca66)
Location: block/blk-mq.h:144
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8168f891)
Location: block/blk-mq.h:144
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
In block/blk-mq.c (ffffffff817428a8)
Location: block/blk-mq.h:145
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8174b256)
Location: block/blk-mq.h:145
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8174e3e1)
Location: block/blk-mq.h:145
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
In block/blk-mq.c (ffffffff8177dff6)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff81787976)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8178a921)
Location: block/blk-mq.h:141
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
In block/blk-mq.c (ffffffff817c0663)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817ca046)
Location: block/blk-mq.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff817cd071)
Location: block/blk-mq.h:141
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
In block/blk-mq.c (ffff8000105ef808)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4530)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffff8000105f6dc8)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (c079a8cc)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a018c)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c07a2588)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (c000000000784630)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078bd3c)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c00000000078f258)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffe00042d92a)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe0004324d4)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffe00043457c)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffff814e7927)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ecd35)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eed7f)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffff814d7e97)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814dd285)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814df2bf)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffff814e39b7)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814e8dc5)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eae0f)
Location: block/blk-mq.h:153
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
In block/blk-mq.c (ffffffff814fcf1b)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501d65)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81503df0)
Location: block/blk-mq.h:153
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
</ul>

## Differences
