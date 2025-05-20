# Function: <code>blk_mq_tags_from_data</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f1b2)
Location: block/blk-mq.h:119
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81433a73)
Location: block/blk-mq.h:119
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff8145a6f8)
Location: block/blk-mq.h:121
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8145f733)
Location: block/blk-mq.h:121
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff8148ec4d)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81493131)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814a86b2)
Location: block/blk-mq.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad0be)
Location: block/blk-mq.h:176
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814d6092)
Location: block/blk-mq.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814db366)
Location: block/blk-mq.h:169
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814ef3d6)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814f4796)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff8154e365)
Location: block/blk-mq.h:160
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-mq-tag.c (ffffffff81554f64)
Location: block/blk-mq.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff8156a795)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-mq-tag.c (ffffffff81571617)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff815726d5)
Location: block/blk-mq.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-mq-tag.c (ffffffff81579647)
Location: block/blk-mq.h:168
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff815d6d05)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-mq-tag.c (ffffffff815de860)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff81683bab)
Location: block/blk-mq.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-tag.c (ffffffff8168cabe)
Location: block/blk-mq.h:171
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tags
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
In block/blk-mq.c (ffffffff817411a6)
Location: block/blk-mq.h:172
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-tag.c (ffffffff8174b2ae)
Location: block/blk-mq.h:172
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tags
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
In block/blk-mq.c (ffffffff81782120)
Location: block/blk-mq.h:222
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817879ce)
Location: block/blk-mq.h:222
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tags
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
In block/blk-mq.c (ffffffff817c4590)
Location: block/blk-mq.h:222
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-tag.c (ffffffff817ca09e)
Location: block/blk-mq.h:222
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tags
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
In block/blk-mq.c (ffff8000105ef8a8)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4578)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (c079a970)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a01d0)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (c0000000007846dc)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078bd98)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffe00042d9ae)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe000432574)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814e79b6)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ecd76)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814d7f26)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814dd2c6)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814e3a46)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814e8e06)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff814fcfaa)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501da6)
Location: block/blk-mq.h:170
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
</details>
</li>
</ul>

## Differences
