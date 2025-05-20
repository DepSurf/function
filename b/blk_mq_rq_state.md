# Function: <code>blk_mq_rq_state</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148df38)
Location: block/blk-mq.h:96
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-debugfs.c (ffffffff814ba653)
Location: block/blk-mq.h:96
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814a77c5)
Location: block/blk-mq.h:137
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-debugfs.c (ffffffff814ce7b0)
Location: block/blk-mq.h:137
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814d5808)
Location: block/blk-mq.h:135
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-debugfs.c (ffffffff814fd075)
Location: block/blk-mq.h:135
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814eeae8)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffff8151afc5)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff8154deb5)
Location: include/linux/blk-mq.h:484
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-tag.c (ffffffff81554815)
Location: include/linux/blk-mq.h:484
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
```
In block/blk-mq-debugfs.c (ffffffff8157bb55)
Location: include/linux/blk-mq.h:484
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff8156cc80)
Location: include/linux/blk-mq.h:482
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-tag.c (ffffffff81570ef5)
Location: include/linux/blk-mq.h:482
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
```
In block/blk-mq-debugfs.c (ffffffff81598c15)
Location: include/linux/blk-mq.h:482
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff81574b20)
Location: include/linux/blk-mq.h:487
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-tag.c (ffffffff81578d55)
Location: include/linux/blk-mq.h:487
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff8159fa1e)
Location: include/linux/blk-mq.h:487
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff815d905a)
Location: include/linux/blk-mq.h:497
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-tag.c (ffffffff815ddf85)
Location: include/linux/blk-mq.h:497
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff816081ce)
Location: include/linux/blk-mq.h:497
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff81686cb2)
Location: include/linux/blk-mq.h:774
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-tag.c (ffffffff8168bf45)
Location: include/linux/blk-mq.h:774
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff816bbbe0)
Location: include/linux/blk-mq.h:774
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff81744982)
Location: include/linux/blk-mq.h:794
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_handle_expired
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-tag.c (ffffffff8174a695)
Location: include/linux/blk-mq.h:794
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff8177c4d0)
Location: include/linux/blk-mq.h:794
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff8177c6e5)
Location: include/linux/blk-mq.h:790
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_handle_expired
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-tag.c (ffffffff81786d75)
Location: include/linux/blk-mq.h:790
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff817bbfd0)
Location: include/linux/blk-mq.h:790
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff817bea45)
Location: include/linux/blk-mq.h:781
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_handle_expired
  - block/blk-mq.c:blk_mq_check_expired
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_rq_inflight
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-tag.c (ffffffff817c9455)
Location: include/linux/blk-mq.h:781
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - block/blk-mq-tag.c:bt_tags_iter
```
```
In block/blk-mq-debugfs.c (ffffffff81800690)
Location: include/linux/blk-mq.h:781
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffff8000105ee9b8)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffff80001062310c)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (c0799ce4)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (c07caba4)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (c000000000783790)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (c0000000007c34c4)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffe00042d0b8)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffe000454f56)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814e70c8)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffff815135a5)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814d7638)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffff815038b5)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814e3158)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffff8150f635)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
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
In block/blk-mq.c (ffffffff814fbfe8)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_request_completed
```
```
In block/blk-mq-debugfs.c (ffffffff81528e55)
Location: block/blk-mq.h:136
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
</details>
</li>
</ul>

## Differences
