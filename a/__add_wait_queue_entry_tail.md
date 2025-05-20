# Function: <code>__add_wait_queue_entry_tail</code>

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
In kernel/sched/wait.c (ffffffff810c9a0b)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:add_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81907248)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff811b84e9)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
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
In kernel/sched/wait.c (ffffffff810d122b)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81991461)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff811ccc52)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
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
In kernel/sched/wait.c (ffffffff810d977b)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff819ed833)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff811edd6c)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
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
In kernel/sched/wait.c (ffffffff810e327b)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81a28a43)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff811ff34c)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
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
In kernel/sched/wait.c (ffffffff810e9e7f)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81a99449)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff812163d8)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
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
In kernel/sched/wait.c (ffffffff810f584f)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81ad0d99)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff81223ce8)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffff815137f7)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810feebf)
Location: include/linux/wait.h:183
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f343)
Location: include/linux/wait.h:183
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff8124eabd)
Location: include/linux/wait.h:183
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-iocost.c (ffffffff81574b78)
Location: include/linux/wait.h:183
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810fd91f)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c503)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff81258f2d)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:__wait_on_page_locked_async
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-iocost.c (ffffffff8159195e)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810ffcff)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e33b)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff81261cb0)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-iocost.c (ffffffff815987bd)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff8111bdeb)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112da7a)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff8129e290)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-iocost.c (ffffffff815fff95)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/build_utility.c (ffffffff8114016a)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_exclusive
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114ebeb)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff812f42a9)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In block/blk-iocost.c (ffffffff816b263c)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/build_utility.c (ffffffff8116c3da)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_exclusive
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117dd9b)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff8135c9b7)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-iocost.c (ffffffff81771b81)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/build_utility.c (ffffffff8117cb3a)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_exclusive
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118ea3b)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff8138e9ea)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-iocost.c (ffffffff817b0e39)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/build_utility.c (ffffffff8118a91a)
Location: include/linux/wait.h:192
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_exclusive
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d3eb)
Location: include/linux/wait.h:192
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
```
```
In mm/filemap.c (ffffffff813b827a)
Location: include/linux/wait.h:192
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In block/blk-iocost.c (ffffffff817f4c49)
Location: include/linux/wait.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffff8000101584ec)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffff800010da28bc)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In mm/filemap.c (ffff8000102aef90)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
```
```
In block/blk-iocost.c (ffff800010617d18)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (c03a6088)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (c0e9aa74)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (c04de06c)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (c07c3090)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (c0000000001ad168)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (c000000000ee40c8)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (c000000000366f58)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (c0000000007b7424)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffe0000fedac)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffe0008c5eea)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffe0001d6d86)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffe00044e288)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810eec4f)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81a6fc09)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff8121c338)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffff8150bdd7)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810decdf)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81a2c029)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff8120f528)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffff814fc221)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810ebd7f)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81adc019)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff8121a0d8)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffff81507e67)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In kernel/sched/wait.c (ffffffff810f6ddf)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff81ae8225)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff812291c0)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In block/blk-iocost.c (ffffffff8151f15b)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
</details>
</li>
</ul>

## Differences
