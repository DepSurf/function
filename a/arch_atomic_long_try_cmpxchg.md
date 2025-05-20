# Function: <code>arch_atomic_long_try_cmpxchg</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81d543a1)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d7cb)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0b6e)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
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
In kernel/locking/rwsem.c (ffffffff81f25574)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8115f795)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd42e)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
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
In kernel/locking/rwsem.c (ffffffff820d0efb)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81192af5)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In io_uring/rsrc.c (ffffffff817a0876)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff818a4294)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56b0e)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/skbuff.c (ffffffff81da6640)
Location: include/linux/atomic/atomic-long.h:435
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
