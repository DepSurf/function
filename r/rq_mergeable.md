# Function: <code>rq_mergeable</code>

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
In block/elevator.c (ffffffff813b3b44)
Location: include/linux/blkdev.h:646
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-merge.c (ffffffff813c12a5)
Location: include/linux/blkdev.h:646
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_rq_merge_ok
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
In block/elevator.c (ffffffff813f7dbf)
Location: include/linux/blkdev.h:664
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-merge.c (ffffffff81405b45)
Location: include/linux/blkdev.h:664
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
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
In block/elevator.c (ffffffff814117e3)
Location: include/linux/blkdev.h:773
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8141fde5)
Location: include/linux/blkdev.h:773
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
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
In block/elevator.c (ffffffff8141f3cb)
Location: include/linux/blkdev.h:816
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8142dd38)
Location: include/linux/blkdev.h:816
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff814353a8)
Location: include/linux/blkdev.h:816
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
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
In block/elevator.c (ffffffff81449eb5)
Location: include/linux/blkdev.h:836
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff81458f65)
Location: include/linux/blkdev.h:836
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff814611d5)
Location: include/linux/blkdev.h:836
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
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
In block/elevator.c (ffffffff8147cbc1)
Location: include/linux/blkdev.h:850
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8148c4c5)
Location: include/linux/blkdev.h:850
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff81494bf5)
Location: include/linux/blkdev.h:850
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
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
In block/elevator.c (ffffffff8149a692)
Location: include/linux/blkdev.h:715
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814a6095)
Location: include/linux/blkdev.h:715
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814aed35)
Location: include/linux/blkdev.h:715
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814c7f14)
Location: include/linux/blkdev.h:715
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814c8769)
Location: include/linux/blkdev.h:727
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814d3f75)
Location: include/linux/blkdev.h:727
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814dcff5)
Location: include/linux/blkdev.h:727
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814f67aa)
Location: include/linux/blkdev.h:727
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814e1889)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814ed2a5)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814f6465)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815145da)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff815403f9)
Location: include/linux/blkdev.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8154ce25)
Location: include/linux/blkdev.h:757
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:attempt_back_merge
```
```
In block/blk-mq-sched.c (ffffffff81556ac5)
Location: include/linux/blkdev.h:757
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81575426)
Location: include/linux/blkdev.h:757
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff8155cb99)
Location: include/linux/blkdev.h:806
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff815692c5)
Location: include/linux/blkdev.h:806
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq-sched.c (ffffffff81573535)
Location: include/linux/blkdev.h:806
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81592211)
Location: include/linux/blkdev.h:806
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff8156542c)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff81571225)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq-sched.c (ffffffff8157b435)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815993a8)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff815c9801)
Location: include/linux/blkdev.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff815d58e5)
Location: include/linux/blkdev.h:774
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq-sched.c (ffffffff815e07b5)
Location: include/linux/blkdev.h:774
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81601ac2)
Location: include/linux/blkdev.h:774
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_request
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
In block/elevator.c (ffffffff81674a61)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff81681715)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff8168f2e5)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff816b45a4)
Location: block/blk.h:124
Inline: True
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
In block/elevator.c (ffffffff817307a1)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8173ece5)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff8174dd75)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81773f3a)
Location: block/blk.h:121
Inline: True
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
In block/elevator.c (ffffffff8176ca01)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff8177b255)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff8178a2f5)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff817b412f)
Location: block/blk.h:125
Inline: True
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
In block/elevator.c (ffffffff817aec31)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff817bd645)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq-sched.c (ffffffff817cca55)
Location: block/blk.h:124
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff817f80c5)
Location: block/blk.h:124
Inline: True
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
In block/elevator.c (ffff8000105de97c)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffff8000105ebd24)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffff8000105f684c)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffff8000106193c0)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (c078b918)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (c0798224)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (c07a21e0)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c07c3ce0)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (c0000000007706d0)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (c0000000007811dc)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (c00000000078ecd0)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c0000000007b87d8)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffe00042155c)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffe00042ba8c)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffe000434240)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffe00044ee74)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814d9e69)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814e5885)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814eea45)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff8150cbba)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814ca819)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814d5e35)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814def95)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814fcfea)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814d5ef9)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814e1915)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff814eaad5)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81508c4a)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/elevator.c (ffffffff814eeaf9)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-merge.c (ffffffff814fa7d5)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq-sched.c (ffffffff81503ac5)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81522348)
Location: include/linux/blkdev.h:744
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
</ul>

## Differences
