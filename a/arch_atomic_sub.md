# Function: <code>arch_atomic_sub</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016a3e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101831f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff819f1b7a)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810e691d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811b3656)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff811f0ca1)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8120edf7)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff81241620)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff81247a42)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff8132d14f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8139399a)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff81395b9e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff813d8b92)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff817f40b5)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff81876daf)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff8187a2b9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818b81e5)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190dfd1)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff8191de9d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819302b8)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff8195df83)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197e8e2)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198f437)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819a5f3f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810171be)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018aef)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a2d13a)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810f1f1d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811c1d36)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff81202afd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8122171d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff81255d20)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff8125c005)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff813444ef)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813ac6ba)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813ae8ea)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff813f2a12)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81820095)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff818971ef)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff8189aec9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818dec45)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c3c1)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff8194caed)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8195f798)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81992ac4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b47e3)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c5cf7)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819dc5ef)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101894e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a18f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a9d30d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fa48d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d2386)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff81219f30)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81230f7a)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812771d4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff8136c70e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813d6928)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813d8daf)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8141f842)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81862555)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff818dfa8f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff818e5249)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8192cb85)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff819532fb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a07f5)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819b12a1)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819c462d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff819fe3e4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23275)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a34b6b)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a4c2df)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192de)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab0f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81ad4aed)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110626d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811de926)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff812278a0)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8123f185)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81286cb4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812bdfcb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff813848be)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813f0968)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813f2d9f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81439662)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81894185)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff81911c3f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819173d9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8195ee85)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81989d67)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d73c9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819e7fcd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819fb1cd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a34fd4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a59ce4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6b6bb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a82eaf)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101aa3e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c682)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81bcca2d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8111118d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff812541df)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8126cb28)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81287d2e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/swap_state.c (ffffffff812b9234)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812f3920)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813cd54f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813cf30f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8143ca59)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff814404f0)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8148987d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff819637a5)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff819e3c3f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819e9c69)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81a32175)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a62105)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5e3e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ad5edd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ae9afd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b27a5f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b2ab11)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b52288)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b64616)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b7cd16)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101af2e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb82)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81c4558d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110e30d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81be6a7f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81277482)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8129192e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff812c49f4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812ff11d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813df17f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e0f3f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff81458dd9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff8145c724)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814a6eb6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8196a0a2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In net/core/sock.c (ffffffff819e35cf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819e9a09)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff819f4e22)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a344bd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69285)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1a6e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ae24bd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81af699d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b36337)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b394a1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5ff0c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81b72da6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b8bdc6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81bbb2b0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101c2de)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e030)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81c3881d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee1d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81bd8815)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8127c4e5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81296c4e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff812cb6a5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81305d92)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813e5d04)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e7b6f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8145e7d4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81461d8e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814ace06)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8194da32)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In net/core/sock.c (ffffffff819ca88f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819cfb29)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff819dafaa)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a1b52d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51a05)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abca8e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81acd3dd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ae20ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b23f14)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b27171)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e1ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81b61870)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b7ac3e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81baa8f0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101f443)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810228ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81d570fd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8112e6bd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81cb9e6f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff812ba50d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812d75fe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff8131077c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134fbf9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff81437884)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8143988f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff814b3b44)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff814b7281)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff815052f1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff819f2e32)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In net/core/sock.c (ffffffff81a789cf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81a7f679)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81a8b63d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81acec0d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a545)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7981e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81b8bd9d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ba188d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81be8560)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81becdae)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c15526)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81c29341)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81c458fe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81c77960)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810221a7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810246e6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81f29b85)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8114f8e1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81e6b4b6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff81317ba9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813370d9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8137b464)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c7e50)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff814b25fc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff814b4907)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8153d374)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81540bea)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81596cbe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In block/blk-flush.c (ffffffff8167c095)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81688c0b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In drivers/md/md.c (ffffffff81b5b122)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b72cb9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81bec3ff)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81bf39d9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81c00c6b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c4c27d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90ac5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0957a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81d18a7d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81d33e6d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81d7fce6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d85298)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0d2d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81dc6733)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81de4a14)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81e1b90e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d67)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810298a6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff820d5a35)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff820d6c31)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81359a58)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff8138af48)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813ae58a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff813f8dfe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8144c022)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff8154917c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8154a39f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff815dbb94)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff815df7cd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff817388fa)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817470f9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In drivers/md/md.c (ffffffff81cf4b22)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d0fa92)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81d9a0ff)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81da17b9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81db00ce)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e00fed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4bf65)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece81e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ee190d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81efc2ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81f4d9d3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f52ce8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80bc7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81f97353)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81fb7184)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ff2ece)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d47)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810298d6)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff82158e15)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff82159fc1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811cbbe1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81279ab5)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In mm/filemap.c (ffffffff8138b3a5)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813bd576)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e2d77)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8142bbce)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81481835)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff81580d5f)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff81581fcf)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81613654)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81616fa9)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff81774f3a)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817841fe)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
```
In drivers/md/md.c (ffffffff81d5c932)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d78ee8)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81e071ef)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81e100a9)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81e203a8)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e72aad)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7665)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dbde)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81f4133d)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81f5bd1a)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81fad524)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb26d1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0a3c)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81ff7d08)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820178c1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8206f14e)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102cea7)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102fa36)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8223c695)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8223d841)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811dd8e1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81294595)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/context_tracking.c (ffffffff82224574)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
```
```
In mm/filemap.c (ffffffff813b4ecc)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813e87e8)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8140d5b4)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8146532b)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff814b087d)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff815b97db)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff815baaaf)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8164c454)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:__jbd2_journal_unreserve_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff8164fdc1)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff817b7261)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c650d)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
```
In drivers/md/md.c (ffffffff81e13f82)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e30069)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81ec513f)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81eccb59)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81ede285)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f321ed)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a115)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff73e8)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff82006f8d)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8202227a)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/tcp_ao.c (ffffffff820550bc)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_time_wait
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
```
```
In net/unix/af_unix.c (ffffffff8207b99d)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8207fe61)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af068)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff820c5958)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820e6891)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8214324e)
Location: arch/x86/include/asm/atomic.h:38
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009cce0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e54)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In kernel/fork.c (ffff8000100f427c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2a0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In kernel/exit.c (ffff8000100fa998)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff8000101205d4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffff80001012d2d8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffff80001012e900)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffff8000101302dc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffff80001013a3e8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff80001014c434)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001015026c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152ba8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159f48)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/locking/spinlock.c (ffff800010da746c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffff80001016c740)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff80001016ffc8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffff80001017d0a0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffff800010189060)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffff80001018a6d8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffff8000101b9088)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffff8000101d719c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de254)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffff8000101f9884)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffff800010210ef4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff80001021a658)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffff800010221588)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffff800010230194)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102308f4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333f0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffff800010238090)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff8000102551c4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff80001025fee8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102784ac)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffff80001028a2cc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029c8b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffff8000102a35f0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffff8000102a543c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102a9aec)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (ffff8000102aeed8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffff8000102d18ac)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102ddb88)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffff8000103037bc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304e2c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff8000103053b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309b58)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In mm/swap_state.c (ffff8000103215a4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327acc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a4d4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032b4e8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffff8000103562a8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035f584)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffff800010365f80)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff8000103729b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
```
```
In fs/open.c (ffff80001037dcd8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff80001038559c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff800010398314)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffff8000103c7854)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dc020)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffff8000103ea604)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5a8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffff800010424edc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffff800010428b98)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffff80001042fad4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In fs/kernfs/dir.c (ffff80001045374c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (ffff80001045ebc8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffff8000104611b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010465934)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010475acc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010477630)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff800010485768)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff8000104964f8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff8000104989cc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffff80001049958c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8610)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104ca580)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffff8000104ce224)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d018c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bc4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df31c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df5b4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df95c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfc88)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dffb8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fda88)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffff80001051ce34)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In ipc/msg.c (ffff80001051fb80)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffff80001052d190)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532fcc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffff80001054710c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffff80001054e388)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffff80001056bc10)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffff80001057b5b4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e650)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580070)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_update_domain
```
```
In security/tomoyo/environ.c (ffff800010580db8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010582840)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffff800010582e94)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffff800010583c30)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff8000105844d8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffff80001058571c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffff800010586734)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587404)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffff8000105e6fc4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8ae8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffff8000105f0894)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffff8000105f4368)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffff8000106154b4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a04c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c28)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e8fa0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010709290)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/ats.c (ffff8000107165e4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e6c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b00b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffff8000107fd480)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d528)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (ffff80001084cf5c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d99c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffff800011493260)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8668)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8ea8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d60fc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd278)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de0b4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In drivers/base/dd.c (ffff8000108ea8f8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd7f0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e408)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff80001094088c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ab28)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffff800010977088)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe7f8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffff800010a1c1b0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffff800010a210b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac499c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca41c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbd70)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffff800010ae7f60)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afdd20)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffff800010b0dd28)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14154)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b1a8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d8c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81108)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffff800010b9e5a4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffff800010bab774)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffff800010bb365c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/dev.c (ffff800010bcb3d8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In net/core/neighbour.c (ffff800010be61cc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/filter.c (ffff800010c0222c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffff800010c068d0)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08264)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In net/core/sock_map.c (ffff800010c21004)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c32404)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/cls_api.c (ffff800010c42754)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c4734c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ee8c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bdbc)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d834)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c1f4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffff800010c9c4ec)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffff800010cb2d3c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf24c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc030)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdce54)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce6198)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/af_inet6.c (ffff800010cf6618)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (ffff800010d0f5b8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f60c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d25510)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a23c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffff800010d32ef4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37794)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3ce00)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eff4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d44c4c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/calipso.c (ffff800010d4d5d8)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51f6c)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffff800010d577a4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68dac)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e84)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6aba4)
Location: arch/arm64/include/asm/atomic.h:30
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffff8000101b69e8-ffff8000101b6a0c: arch_atomic_sub.constprop.0 (STB_LOCAL)
ffff800010295230-ffff800010295254: arch_atomic_sub.constprop.0 (STB_LOCAL)
ffff8000103723a8-ffff8000103723cc: arch_atomic_sub.constprop.0 (STB_LOCAL)
ffff800010708ae8-ffff800010708b24: arch_atomic_sub.constprop.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192de)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab0f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a7395d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ff57d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d6f46)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff8121fef0)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff812377d5)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127f304)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b65ab)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8137ce9e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813e8f48)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813eb37f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81431c42)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8183a005)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff818b1c3f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff818b73d9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818fee55)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81929bd7)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977239)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81987e3d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8199af6d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff819d4664)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9374)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a0ad4b)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a2253f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810186ae)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a1af)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a2fcbd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ef76d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811c9d06)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff812130a0)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8122a65f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127111e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812a7781)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8136d95e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813d99c8)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813dbdff)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814226c2)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81801675)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff8186bb8f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81871329)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818b8c85)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3987)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930cf9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819418fd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81954a2d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81991424)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6134)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c7b0b)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819df2ff)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101929e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aacf)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81adfd6d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fc73d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d4d16)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff8121dc90)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81235575)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127d0a4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b43bb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8137a96e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813e62c8)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813e86ff)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8142dde2)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81889635)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff81902c3f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819083d9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8194fe85)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff8197ad67)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1a09)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819f260d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81a0580d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f0e4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a63df4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a757cb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a8cfbf)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810194de)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad0f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81aec56f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110796d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811e3046)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In mm/filemap.c (ffffffff8122cd00)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8124567c)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128cc5b)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812c4887)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8138e46e)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813fb7b8)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffffffff813fdf37)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8144483f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff818a6d65)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/core/sock.c (ffffffff81923bef)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819293b9)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81971855)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d2c0)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb739)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819fc45d)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81a0fddd)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aba4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a702f4)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a81eeb)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a99c7f)
Location: arch/x86/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
</details>
</li>
</ul>

## Differences
