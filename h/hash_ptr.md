# Function: <code>hash_ptr</code>

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
In kernel/locking/qspinlock.c (0)
Location: include/linux/hash.h:71
Inline: True
```
```
In kernel/kprobes.c (ffffffff8112c8e5)
Location: include/linux/hash.h:71
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In mm/filemap.c (0)
Location: include/linux/hash.h:71
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/hash.h:71
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff810cf5e3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff81135302)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8119fe1d)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:unlock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - mm/filemap.c:wait_on_page_bit
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
In kernel/locking/qspinlock.c (ffffffff810d5fc3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8113f082)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff811b1057)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In net/ipv4/udp.c (ffffffff81824d07)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/locking/qspinlock.c (ffffffff810d4f43)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff811405ff)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff811b84b2)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In net/ipv4/udp.c (ffffffff818481bb)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/locking/qspinlock.c (ffffffff810dcea3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8114d4a2)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff811ccc19)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In net/ipv4/udp.c (ffffffff818c7c01)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810d9ab5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810e5543)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8115be3a)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff811edd03)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In net/ipv4/udp.c (ffffffff8191df74)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810e35b5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810f0ad3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff81168bca)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff811ff2bc)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In net/ipv4/udp.c (ffffffff8194cbc4)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810ea1c5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810f91a9)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8117585d)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8121631e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff81952985)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819b1387)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810f5b95)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff81104f99)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff811816cd)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff81223c2e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff81988cd5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819e80b3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810ff135)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8110fd79)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff81196bb8)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff81252dfd)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In fs/io-wq.c (ffffffff8138b0e5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In block/keyslot-manager.c (ffffffff8158143b)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60995)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff81ad5ff6)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810fdc35)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8110cf39)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff81193c68)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fc25)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff8125d9ca)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__wait_on_page_locked_async
  - mm/filemap.c:wake_up_page_bit
```
```
In fs/io-wq.c (ffffffff8139c345)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In block/keyslot-manager.c (ffffffff8159e46b)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In net/ipv4/udp.c (ffffffff81ae25d6)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff81100015)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8110ed2c)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff81194c48)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812251e5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff8126071c)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_private_2_killable
  - mm/filemap.c:wait_on_page_private_2
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137ea3c)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io-wq.c (ffffffff813a3495)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In block/keyslot-manager.c (ffffffff815a524d)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In net/ipv4/udp.c (ffffffff81acd4f6)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff8111c0b5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8112e58a)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff811bdb08)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d1aa)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff8129d10e)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_private_2_killable
  - mm/filemap.c:wait_on_page_private_2
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cbb1c)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io-wq.c (ffffffff813f2975)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In block/keyslot-manager.c (ffffffff8160dd03)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In net/ipv4/udp.c (ffffffff81b8bee0)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/build_utility.c (ffffffff8113b875)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8114f79a)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff811f1bd4)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a730a)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff812f4154)
Location: include/linux/hash.h:85
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
  - mm/filemap.c:folio_wake_bit
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81454259)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In block/blk-crypto-profile.c (ffffffff816c27b5)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io-wq.c (ffffffff816db505)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/udp.c (ffffffff81d18b8a)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/build_utility.c (ffffffff811662a5)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff820d6a7a)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/kprobes.c (ffffffff81238883)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813059ea)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff8135c988)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff8137fa57)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e3109)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/kernfs/file.c (ffffffff8154d8f5)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In block/blk-crypto-profile.c (ffffffff81783b15)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io-wq.c (ffffffff817a75e5)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/udp.c (ffffffff81ee1a4d)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/build_utility.c (ffffffff81176715)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff82159e61)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/module/main.c (ffffffff811e0562)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/kprobes.c (ffffffff8124f9e3)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813346ca)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff8138e9b8)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813b0fdc)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815199f2)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/kernfs/file.c (ffffffff81585595)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In block/blk-crypto-profile.c (ffffffff817c3e05)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io-wq.c (ffffffff817e8635)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/udp.c (ffffffff81f4144e)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/build_utility.c (ffffffff81184995)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff8223d6e1)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/module/main.c (ffffffff811f6292)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/kprobes.c (ffffffff81269913)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81358dda)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In mm/filemap.c (ffffffff813b8248)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813da558)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In mm/zswap.c (ffffffff81470f90)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:zswap_free_entry
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154ddd2)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/kernfs/file.c (ffffffff815be045)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In block/blk-crypto-profile.c (ffffffff81808a95)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io-wq.c (ffffffff8182e3d5)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/udp.c (ffffffff820070aa)
Location: include/linux/hash.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffff800010159200)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/kprobes.c (ffff8000101f8438)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
```
```
In mm/filemap.c (ffff8000102b1638)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffff800010c311c8)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffff800010c9c5f0)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (c03a6560)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/kprobes.c (c0436cec)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (c04ddfd8)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/highmem.c (c0515f04)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - mm/highmem.c:set_page_address
```
```
In net/core/bpf_sk_storage.c (c0d47db0)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (c0da77a4)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (c0000000001ad6d0)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/kprobes.c (c00000000026cd04)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (c000000000366e80)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (c000000000d29ea0)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (c000000000daeb44)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffe0000ff2bc)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In mm/filemap.c (ffffffe0001d6d40)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a6e20)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffe0007fa67a)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810eef95)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810fe2a9)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff81179ced)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8121c27e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff81928b45)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff81987f23)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810df015)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810ee4a9)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8116ce8d)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8120f46e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff818e28f5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819419e3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810ec0c5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff810fb469)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff81177abd)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8121a01e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff81979cd5)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819f26f3)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In kernel/sched/wait_bit.c (ffffffff810f7115)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
```
In kernel/locking/qspinlock.c (ffffffff81106639)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/kprobes.c (ffffffff8118537d)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In mm/filemap.c (ffffffff8122910e)
Location: include/linux/hash.h:88
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
  - mm/filemap.c:wake_up_page_bit
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c205)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819fc53f)
Location: include/linux/hash.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
</details>
</li>
</ul>

## Differences
