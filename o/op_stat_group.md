# Function: <code>op_stat_group</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499cf8)
Location: include/linux/blk_types.h:411
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff8149f40d)
Location: include/linux/blk_types.h:411
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff81820f5f)
Location: include/linux/blk_types.h:411
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818348f1)
Location: include/linux/blk_types.h:411
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814c7da0)
Location: include/linux/blk_types.h:412
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814cd4fa)
Location: include/linux/blk_types.h:412
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff8186336e)
Location: include/linux/blk_types.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8187670e)
Location: include/linux/blk_types.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814e0ea0)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814e67ea)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff8189509c)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818a850e)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff815437da)
Location: include/linux/blk_types.h:464
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff8154ae63)
Location: include/linux/blk_types.h:464
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
  - block/blk-merge.c:blk_account_io_merge_request
```
```
In drivers/md/dm.c (ffffffff819796b1)
Location: include/linux/blk_types.h:464
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff815606b2)
Location: include/linux/blk_types.h:528
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff81566c27)
Location: include/linux/blk_types.h:528
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197d3a4)
Location: include/linux/blk_types.h:528
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff81568d13)
Location: include/linux/blk_types.h:502
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff8156f167)
Location: include/linux/blk_types.h:502
Inline: True
```
```
In drivers/md/dm.c (ffffffff81961483)
Location: include/linux/blk_types.h:502
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff815ccfad)
Location: include/linux/blk_types.h:493
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff815d3817)
Location: include/linux/blk_types.h:493
Inline: True
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
In block/blk-core.c (ffffffff81679bc5)
Location: include/linux/blk_types.h:525
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
```
```
In block/blk-merge.c (ffffffff81680e11)
Location: include/linux/blk_types.h:525
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff81682c39)
Location: include/linux/blk_types.h:525
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_account_io_done
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
In block/blk-core.c (ffffffff81736025)
Location: include/linux/blk_types.h:524
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
```
```
In block/blk-merge.c (ffffffff8173e2f7)
Location: include/linux/blk_types.h:524
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff817402c9)
Location: include/linux/blk_types.h:524
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_account_io_done
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
In block/blk-core.c (ffffffff81772545)
Location: include/linux/blk_types.h:529
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
```
```
In block/blk-merge.c (ffffffff8177a859)
Location: include/linux/blk_types.h:529
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff8177ec27)
Location: include/linux/blk_types.h:529
Inline: True
Inline callers:
  - block/blk-mq.c:blk_account_io_done
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
In block/blk-core.c (ffffffff817b48e5)
Location: include/linux/blk_types.h:528
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
```
```
In block/blk-merge.c (ffffffff817bcc39)
Location: include/linux/blk_types.h:528
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff817c1477)
Location: include/linux/blk_types.h:528
Inline: True
Inline callers:
  - block/blk-mq.c:blk_account_io_done
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
In block/bio.c (ffff8000105ddac0)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffff8000105e3f94)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffff800010ae8100)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffff800010aff33c)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (c078ae34)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (c0791280)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (c0bcb884)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (c0bde144)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (c00000000076f3c8)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (c000000000777c74)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (c000000000bd5c28)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (c000000000bed268)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffe000420a5e)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffe00042590a)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffe0006dd652)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffe0006ee97e)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814d9480)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814dedca)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff8183af1c)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8184e38e)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814c9e30)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814cf76a)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff8180258c)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818159ae)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814d5510)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814dae5a)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff8188a54c)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8189d9be)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff814ee0fb)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814f3bea)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In drivers/md/md.c (ffffffff818a93ac)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818b9d30)
Location: include/linux/blk_types.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
</details>
</li>
</ul>

## Differences
