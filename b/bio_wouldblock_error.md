# Function: <code>bio_wouldblock_error</code>

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
In block/blk-core.c (ffffffff814252a3)
Location: include/linux/bio.h:433
Inline: True
```
```
In block/blk-mq.c (ffffffff81431496)
Location: include/linux/bio.h:433
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff81450370)
Location: include/linux/bio.h:429
Inline: True
```
```
In block/blk-mq.c (ffffffff8145ce77)
Location: include/linux/bio.h:429
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff8148362c)
Location: include/linux/bio.h:462
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff81490952)
Location: include/linux/bio.h:462
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff8149edf6)
Location: include/linux/bio.h:411
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814aad0b)
Location: include/linux/bio.h:411
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814cced9)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814d86e6)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814e6109)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814f1a96)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff81544ff0)
Location: include/linux/bio.h:426
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
```
```
In block/blk-mq.c (ffffffff8155138c)
Location: include/linux/bio.h:426
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff8156195a)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff8156f1e3)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In drivers/md/dm.c (ffffffff8197e3cc)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff81569f2f)
Location: include/linux/bio.h:435
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff81576dd0)
Location: include/linux/bio.h:435
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In drivers/md/dm.c (ffffffff8196217f)
Location: include/linux/bio.h:435
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff815cd5a3)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-mq.c (ffffffff815dbafb)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In drivers/md/dm.c (ffffffff81a0b2bf)
Location: include/linux/bio.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff81678ada)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-mq.c (ffffffff8168424b)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In drivers/md/md.c (ffffffff81b5c027)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81b72e46)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff81734f57)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-mq.c (ffffffff81741a2b)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In drivers/md/md.c (ffffffff81cf6017)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d0fc06)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff817714b6)
Location: include/linux/bio.h:440
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-mq.c (ffffffff81781f4b)
Location: include/linux/bio.h:440
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In drivers/md/md.c (ffffffff81d5fd7c)
Location: include/linux/bio.h:440
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d79083)
Location: include/linux/bio.h:440
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff817b37f6)
Location: include/linux/bio.h:450
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-mq.c (ffffffff817c6c71)
Location: include/linux/bio.h:450
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In drivers/md/md.c (ffffffff81e17358)
Location: include/linux/bio.h:450
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81e301f6)
Location: include/linux/bio.h:450
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/blk-core.c (ffff8000105e36c4)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffff8000105f12bc)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (c07909c0)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (c079d438)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (c00000000077705c)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (c0000000007880f0)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffe000424fec)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffe00042ff28)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814de6e9)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814ea076)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814cf089)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814da5d6)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814da779)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814e6106)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814f3477)
Location: include/linux/bio.h:418
Inline: True
```
```
In block/blk-mq.c (ffffffff814ff08a)
Location: include/linux/bio.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
</ul>

## Differences
