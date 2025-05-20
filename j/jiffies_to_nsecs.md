# Function: <code>jiffies_to_nsecs</code>

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
In kernel/sched/cputime.c (ffffffff810b1ab2)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
```
```
In kernel/delayacct.c (ffffffff8113df97)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
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
In kernel/sched/cputime.c (ffffffff810b46bc)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
```
In kernel/delayacct.c (ffffffff811465bb)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff811475dc)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
```
```
In block/cfq-iosched.c (ffffffff8142b4ed)
Location: include/linux/jiffies.h:287
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
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
In kernel/sched/cputime.c (ffffffff810bac9c)
Location: include/linux/jiffies.h:291
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
```
In kernel/delayacct.c (ffffffff811503fb)
Location: include/linux/jiffies.h:291
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8115147c)
Location: include/linux/jiffies.h:291
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
```
```
In block/cfq-iosched.c (ffffffff814453cc)
Location: include/linux/jiffies.h:291
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81454257)
Location: include/linux/jiffies.h:290
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147fd8c)
Location: include/linux/jiffies.h:291
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b4769)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
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
In kernel/sched/psi.c (ffffffff810ef486)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff81499d1b)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff810f5cf1)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814c7db5)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff81101a81)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814e0eb5)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff8110c311)
Location: include/linux/jiffies.h:292
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/blk-core.c (ffffffff81542c9e)
Location: include/linux/jiffies.h:292
Inline: True
Inline callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81976e75)
Location: include/linux/jiffies.h:292
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/psi.c (ffffffff81109511)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/blk-core.c (ffffffff8155f573)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
```
```
In drivers/md/dm.c (ffffffff8197baa5)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/psi.c (ffffffff831e676b)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/blk-core.c (ffffffff81567d06)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
```
```
In drivers/md/dm.c (ffffffff8195fca5)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/psi.c (ffffffff832ca8a8)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/blk-core.c (ffffffff815cc336)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81a07c75)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/build_utility.c (ffffffff8347dd5b)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_init
```
```
In block/blk-core.c (ffffffff81679c0d)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81b6fe15)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/build_utility.c (ffffffff83ea9904)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_init
```
```
In block/blk-core.c (ffffffff8173606d)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81d0c5a5)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/build_utility.c (ffffffff836ce6d4)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_init
```
```
In block/blk-core.c (ffffffff817725e6)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81d75795)
Location: include/linux/jiffies.h:293
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/build_utility.c (ffffffff838ffad4)
Location: include/linux/jiffies.h:443
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_init
```
```
In block/blk-core.c (ffffffff817b4986)
Location: include/linux/jiffies.h:443
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
```
```
In drivers/md/dm.c (ffffffff81e2c895)
Location: include/linux/jiffies.h:443
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_time_ns_from_clone
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
In kernel/sched/psi.c (ffff80001144588c)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffff8000105ddad0)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (c151fa7c)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (c078ae48)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (c00000000136a3c0)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (c00000000076f3e0)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffe0000075e0)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffe000420a7e)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff810fad91)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814d9495)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff810eafb1)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814c9e45)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff810f7f51)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814d5525)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
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
In kernel/sched/psi.c (ffffffff81103091)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
```
```
In block/bio.c (ffffffff814ee121)
Location: include/linux/jiffies.h:294
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
</details>
</li>
</ul>

## Differences
