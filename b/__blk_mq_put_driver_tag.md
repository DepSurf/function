# Function: <code>__blk_mq_put_driver_tag</code>

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
void __blk_mq_put_driver_tag(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f670)
Location: block/blk-mq.c:889
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8142f670-ffffffff8142f6b7: __blk_mq_put_driver_tag (STB_LOCAL)
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
In block/blk-flush.c (ffffffff8145483a)
Location: block/blk-mq.h:159
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8145cac4)
Location: block/blk-mq.h:159
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff81487c79)
Location: block/blk-mq.h:174
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81490e07)
Location: block/blk-mq.h:174
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814a1ada)
Location: block/blk-mq.h:215
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814a9c97)
Location: block/blk-mq.h:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814cfc21)
Location: block/blk-mq.h:208
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814d7c3e)
Location: block/blk-mq.h:208
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814e8f78)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814f0fba)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff81547ea8)
Location: block/blk-mq.h:199
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815520cf)
Location: block/blk-mq.h:199
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff81563bcc)
Location: block/blk-mq.h:225
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8156e568)
Location: block/blk-mq.h:225
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff8156c34c)
Location: block/blk-mq.h:243
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81576149)
Location: block/blk-mq.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff815d07ec)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815dacd3)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff8167bfea)
Location: block/blk-mq.h:251
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81688b7e)
Location: block/blk-mq.h:251
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff8173886a)
Location: block/blk-mq.h:252
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8174706c)
Location: block/blk-mq.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff81774eaa)
Location: block/blk-mq.h:302
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8178419d)
Location: block/blk-mq.h:302
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff817b71b6)
Location: block/blk-mq.h:334
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c64bb)
Location: block/blk-mq.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffff8000105e6ef4)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffff8000105f074c)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (c0793c08)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (c079c778)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (c00000000077bacc)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (c000000000786da0)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffe000428056)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffe00042f5be)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814e1558)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814e959a)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814d1ee8)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814d9b0a)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814dd5e8)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814e562a)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-flush.c (ffffffff814f6448)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814fe58a)
Location: block/blk-mq.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
