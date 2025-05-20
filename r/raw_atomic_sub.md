# Function: <code>raw_atomic_sub</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810298d6)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff82158e15)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff82159fc1)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811cbbe1)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81279ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In mm/filemap.c (ffffffff8138b3a5)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813bd576)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e2d77)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8142bbce)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81481835)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff81580d5f)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff81581fcf)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81613654)
Location: include/linux/atomic/atomic-arch-fallback.h:758
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
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff81774f3a)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817841fe)
Location: include/linux/atomic/atomic-arch-fallback.h:758
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
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d78ee8)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81e071ef)
Location: include/linux/atomic/atomic-arch-fallback.h:758
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
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81e203a8)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e72aad)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7665)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dbde)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81f4133d)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81f5bd1a)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81fad524)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb26d1)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0a3c)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81ff7d08)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820178c1)
Location: include/linux/atomic/atomic-arch-fallback.h:758
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8206f14e)
Location: include/linux/atomic/atomic-arch-fallback.h:758
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
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102fa36)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8223c695)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8223d841)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811dd8e1)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81294595)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/context_tracking.c (ffffffff82224574)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
```
```
In mm/filemap.c (ffffffff813b4ecc)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813e87e8)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8140d5b4)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8146532b)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff814b087d)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff815b97db)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff815baaaf)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8164c454)
Location: include/linux/atomic/atomic-arch-fallback.h:767
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
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff817b7261)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c650d)
Location: include/linux/atomic/atomic-arch-fallback.h:767
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
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e30069)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81ec513f)
Location: include/linux/atomic/atomic-arch-fallback.h:767
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
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81ede285)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f321ed)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a115)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff73e8)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff82006f8d)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8202227a)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/tcp_ao.c (ffffffff820550bc)
Location: include/linux/atomic/atomic-arch-fallback.h:767
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
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8207fe61)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af068)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff820c5958)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820e6891)
Location: include/linux/atomic/atomic-arch-fallback.h:767
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8214324e)
Location: include/linux/atomic/atomic-arch-fallback.h:767
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
