# Function: <code>signal_pending_state</code>

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
In kernel/sched/core.c (ffffffff8181ff67)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810c38de)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io_timeout
```
```
In kernel/sched/completion.c (ffffffff81821224)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (ffffffff81821aef)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff818226b8)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_killable
```
```
In block/blk-core.c (ffffffff813bbc65)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In lib/percpu_ida.c (ffffffff813ff933)
Location: include/linux/sched.h:2915
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
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
In kernel/sched/core.c (ffffffff8189a17e)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff8189b18c)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810c75ee)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff8189b534)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff8189bef8)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff8189cc68)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189db09)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In block/blk-core.c (ffffffff813ffa7d)
Location: include/linux/sched.h:3192
Inline: True
```
```
In lib/percpu_ida.c (ffffffff81447023)
Location: include/linux/sched.h:3192
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
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
In kernel/sched/core.c (ffffffff818ceab6)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff818cf70c)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810cd4be)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff818cfb55)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff818d1532)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff818d1b48)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d29be)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In mm/filemap.c (ffffffff811aff2b)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff81422090)
Location: include/linux/sched.h:3348
Inline: True
```
```
In lib/percpu_ida.c (ffffffff81465846)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/md/dm.c (ffffffff817343f6)
Location: include/linux/sched.h:3348
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81905bdb)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810c9899)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81906b4c)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810c9e3e)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819072c4)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81907cd9)
Location: include/linux/sched/signal.h:327
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81908d17)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8190989d)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In mm/filemap.c (ffffffff811b9a16)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff81430857)
Location: include/linux/sched/signal.h:327
Inline: True
```
```
In lib/percpu_ida.c (ffffffff8146a6a9)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/md/dm.c (ffffffff8174d868)
Location: include/linux/sched/signal.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff8198fc4b)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810d10b9)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81990bbc)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:atomic_t_wait
```
```
In kernel/sched/swait.c (ffffffff810d165f)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819914df)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81991d90)
Location: include/linux/sched/signal.h:328
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81992be2)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819937d5)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In mm/filemap.c (ffffffff811ced4d)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff8145bd3e)
Location: include/linux/sched/signal.h:328
Inline: True
```
```
In lib/percpu_ida.c (ffffffff81496993)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/md/dm.c (ffffffff817bf964)
Location: include/linux/sched/signal.h:328
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff819ec4ad)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810d959c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff819ed4c2)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810d9baf)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819ed84b)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff819ee48c)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff819ef375)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efd6b)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In mm/filemap.c (ffffffff811ee568)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff8148f4c6)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In lib/percpu_ida.c (ffffffff814cbd20)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/md/dm.c (ffffffff818079dc)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81a276fd)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810e309c)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a286f2)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810e36cc)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a28a5b)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a29732)
Location: include/linux/sched/signal.h:365
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a2a6b5)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b79b)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In mm/filemap.c (ffffffff811ffd03)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814a8f62)
Location: include/linux/sched/signal.h:365
Inline: True
```
```
In drivers/md/dm.c (ffffffff81833e55)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81a97fc3)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810e9d0f)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a98ee2)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ea34f)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a99492)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a99d7d)
Location: include/linux/sched/signal.h:370
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a9acad)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810f8440)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff81216da9)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814d6912)
Location: include/linux/sched/signal.h:370
Inline: True
```
```
In drivers/md/dm.c (ffffffff81875c42)
Location: include/linux/sched/signal.h:370
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81acf894)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810f56df)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ad0832)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f5d1f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81ad0de2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81ad16cd)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81ad25fd)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110427a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff812246b9)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814efc6b)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffff818a7a42)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:371
Inline: True
```
```
In kernel/sched/core.c (ffffffff81bc8512)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810fef5f)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81bc911f)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ff4ff)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81bc921e)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81bc9896)
Location: include/linux/sched/signal.h:371
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81bca631)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110ee74)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:371
Inline: True
```
```
In mm/filemap.c (ffffffff8124f886)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-mq.c (ffffffff8154efcd)
Location: include/linux/sched/signal.h:371
Inline: True
```
```
In drivers/md/dm.c (ffffffff81977811)
Location: include/linux/sched/signal.h:371
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:384
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c4125b)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810fd7cf)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c41f2f)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810fe05f)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c42049)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c426ce)
Location: include/linux/sched/signal.h:384
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c43768)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110c052)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:384
Inline: True
```
```
In mm/filemap.c (ffffffff8125a7b7)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-mq.c (ffffffff8156ce05)
Location: include/linux/sched/signal.h:384
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197c495)
Location: include/linux/sched/signal.h:384
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:385
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c331c1)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ffbaf)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c33e9f)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff8110043f)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c33fb9)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c3458a)
Location: include/linux/sched/signal.h:385
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c354f2)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8110de86)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:385
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81c360e0)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In mm/filemap.c (ffffffff8125effc)
Location: include/linux/sched/signal.h:385
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-mq.c (ffffffff81574ca5)
Location: include/linux/sched/signal.h:385
Inline: True
```
```
In drivers/md/dm.c (ffffffff819600ab)
Location: include/linux/sched/signal.h:385
Inline: True
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:383
Inline: True
```
```
In kernel/sched/core.c (ffffffff81d51bb6)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff8111bca7)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81d5283f)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff8111c4b7)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81d52955)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81d52f0b)
Location: include/linux/sched/signal.h:383
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81d53cef)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8112d65a)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:383
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d5494d)
Location: include/linux/sched/signal.h:383
Inline: True
```
```
In mm/filemap.c (ffffffff8129b768)
Location: include/linux/sched/signal.h:383
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-mq.c (ffffffff815d91f0)
Location: include/linux/sched/signal.h:383
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a0807b)
Location: include/linux/sched/signal.h:383
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In kernel/sched/core.c (ffffffff81f220ef)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8113fac7)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81f23b4e)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24d34)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f258b9)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f264d7)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:413
Inline: True
```
```
In mm/filemap.c (ffffffff812f5f6c)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
```
```
In block/blk-mq.c (ffffffff8168bdb9)
Location: include/linux/sched/signal.h:413
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
```
```
In drivers/md/dm.c (ffffffff81b70c8b)
Location: include/linux/sched/signal.h:413
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/sched/core.c (ffffffff820cca00)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8116a6a7)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff820cf01b)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d03bb)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff820d129f)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d1fba)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In mm/filemap.c (ffffffff8135c41c)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-mq.c (ffffffff81741c8e)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
```
```
In drivers/md/dm.c (ffffffff81d0d61d)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/sched/core.c (ffffffff82150cd2)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8117adb7)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff821533d5)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff8215474b)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82155604)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff821563d9)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:414
Inline: True
```
```
In mm/filemap.c (ffffffff8138e44c)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-mq.c (ffffffff8177d2cc)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In drivers/md/dm.c (ffffffff81d7653d)
Location: include/linux/sched/signal.h:414
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
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
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In kernel/sched/core.c (ffffffff82233afe)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff811887c7)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff82236215)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff8223758b)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82238444)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239219)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:406
Inline: True
```
```
In mm/filemap.c (ffffffff813b7b0c)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-mq.c (ffffffff817bf65c)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In drivers/md/dm.c (ffffffff81e2d76d)
Location: include/linux/sched/signal.h:406
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
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
In kernel/sched/core.c (ffff800010da1778)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffff8000101582c4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffff800010da2788)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffff80001015939c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffff800010da28c8)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffff800010da3208)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffff800010da4b68)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffff800010169b50)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffff8000102af6b4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-mq.c (ffff8000105eda3c)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffff800010afc87c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (c0e9984c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (c03a5e74)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c0e9a834)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c03a68a8)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (c0e9aad4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (c0e9b998)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (c0e9cd40)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (c03b5dd4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (c04de988)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (c079b374)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (c0bdd1f4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (c000000000ee27e0)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (c0000000001acf04)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c000000000ee3d4c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c0000000001ad914)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (c000000000ee4144)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (c000000000ee56cc)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (c000000000ee7264)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (c0000000001c1850)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (c000000000367ab0)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (c00000000078516c)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (c000000000bebba0)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffe0008c4f9c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffe0000fecf4)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffe0008c5c8c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffe0000ff41a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffe0008c5f80)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffe0008c6ce8)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffe0008c7a9e)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffe00010add0)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffe0001d75aa)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffe00042e1cc)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffe0006edc2a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81a6e704)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810eeadf)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a6f6a2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ef11f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a6fc52)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a7053d)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a7146d)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810fd58a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff8121cd09)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814e824b)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffff8184d8c2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81a2aaff)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810deb6f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a2bad2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810df19f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a2c06c)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a2c92d)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a2da17)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810ed78a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff8120fee3)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814d87bb)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffff81814ee2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81adab14)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ebc0f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81adbab2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ec24f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81adc062)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81adc94d)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81add87d)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810fa74a)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff8121aaa9)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814e42db)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffff8189cef2)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/core.c (ffffffff81ae6fc6)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810f6c6f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ae8052)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f737f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81ae8266)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81ae8d83)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81ae9f14)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110590f)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/filemap.c (ffffffff81229b6b)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In block/blk-mq.c (ffffffff814fd85b)
Location: include/linux/sched/signal.h:362
Inline: True
```
```
In drivers/md/dm.c (ffffffff818b9252)
Location: include/linux/sched/signal.h:362
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
</ul>

## Differences
