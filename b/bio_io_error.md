# Function: <code>bio_io_error</code>

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
In block/blk-core.c (ffffffff813b9ce5)
Location: include/linux/bio.h:467
Inline: True
```
```
In block/blk-mq.c (ffffffff813c5e56)
Location: include/linux/bio.h:467
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In drivers/block/brd.c (ffffffff8156d945)
Location: include/linux/bio.h:467
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/md/md.c (ffffffff816904ab)
Location: include/linux/bio.h:467
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff816a2b43)
Location: include/linux/bio.h:467
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_make_request
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
In block/blk-core.c (ffffffff813fdac3)
Location: include/linux/bio.h:416
Inline: True
```
```
In block/blk-mq.c (ffffffff81409cd4)
Location: include/linux/bio.h:416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In drivers/block/brd.c (ffffffff815c31e5)
Location: include/linux/bio.h:416
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/md/md.c (ffffffff816f119a)
Location: include/linux/bio.h:416
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8170365a)
Location: include/linux/bio.h:416
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff81417403)
Location: include/linux/bio.h:415
Inline: True
```
```
In block/blk-mq.c (ffffffff81424717)
Location: include/linux/bio.h:415
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In drivers/md/md.c (ffffffff81722a45)
Location: include/linux/bio.h:415
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff81735513)
Location: include/linux/bio.h:415
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff8142520e)
Location: include/linux/bio.h:427
Inline: True
```
```
In drivers/md/md.c (ffffffff81739e9d)
Location: include/linux/bio.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8174e753)
Location: include/linux/bio.h:427
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff814502d6)
Location: include/linux/bio.h:423
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/bio.h:423
Inline: True
```
```
In drivers/md/dm.c (ffffffff817c0788)
Location: include/linux/bio.h:423
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff814835a7)
Location: include/linux/bio.h:456
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In drivers/md/md.c (0)
Location: include/linux/bio.h:456
Inline: True
```
```
In drivers/md/dm.c (ffffffff818089d2)
Location: include/linux/bio.h:456
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff8149ed71)
Location: include/linux/bio.h:405
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In drivers/md/md.c (0)
Location: include/linux/bio.h:405
Inline: True
```
```
In drivers/md/dm.c (ffffffff81834d8c)
Location: include/linux/bio.h:405
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__process_bio
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
In block/blk-core.c (ffffffff814cce36)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/dm.c (ffffffff81877487)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff814e6066)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffff818951f7)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818a90b7)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff81544fdb)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:direct_make_request
```
```
In drivers/md/md.c (0)
Location: include/linux/bio.h:420
Inline: True
```
```
In drivers/md/dm.c (ffffffff81979a78)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff81561947)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
```
```
In drivers/md/md.c (ffffffff81968eff)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff8197e325)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff81569ef3)
Location: include/linux/bio.h:429
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
```
```
In drivers/md/md.c (ffffffff8194cf5f)
Location: include/linux/bio.h:429
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff819620d8)
Location: include/linux/bio.h:429
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff815cd50e)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In drivers/md/md.c (ffffffff819f233f)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff81a0b218)
Location: include/linux/bio.h:431
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffffffff81678a33)
Location: include/linux/bio.h:430
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In drivers/md/md.c (ffffffff81b5c17c)
Location: include/linux/bio.h:430
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff81b72dda)
Location: include/linux/bio.h:430
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
In block/blk-core.c (ffffffff81734ead)
Location: include/linux/bio.h:430
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In drivers/md/md.c (ffffffff81cf6187)
Location: include/linux/bio.h:430
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff81d0fb9a)
Location: include/linux/bio.h:430
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
In block/blk-core.c (ffffffff8177140d)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In drivers/md/md.c (ffffffff81d5ff04)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff81d79017)
Location: include/linux/bio.h:434
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
In block/blk-core.c (ffffffff817b374d)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
```
```
In drivers/md/md.c (ffffffff81e174e4)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_bio
```
```
In drivers/md/dm.c (ffffffff81e3018b)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/blk-core.c (ffff8000105e35b8)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffff800010ae8294)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffff800010aff838)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (c0790938)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
```
```
In drivers/md/md.c (c0bcb9e0)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (c0bdf198)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (c000000000776ef8)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (c000000000bd5dc8)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (c000000000bee200)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffe000424fe6)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffe0006dd794)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffe0006ef3de)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff814de646)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffff8183b077)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8184ef37)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff814cefe6)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffff818026e7)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff81816557)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff814da6d6)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffff8188a6a7)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8189e567)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
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
In block/blk-core.c (ffffffff814f33ca)
Location: include/linux/bio.h:412
Inline: True
```
```
In drivers/md/md.c (ffffffff818a9528)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff818bb197)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
```
</details>
</li>
</ul>

## Differences
