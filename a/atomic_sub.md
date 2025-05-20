# Function: <code>atomic_sub</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101815e)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019613)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_cbox_put_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81823fa3)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810cbddd)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/vmalloc.c (ffffffff811ccde6)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/huge_memory.c (ffffffff811f7443)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/kernfs/dir.c (ffffffff8128a8b1)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff812e6bc9)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:sub_reserved_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_stop
```
```
In fs/jbd2/commit.c (ffffffff812ea074)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81325a01)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgrcv
```
```
In lib/genalloc.c (ffffffff81407126)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc
```
```
In drivers/usb/core/devio.c (ffffffff81619668)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81691d72)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In net/core/sock.c (ffffffff817002c3)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_wfree
```
```
In net/core/skbuff.c (ffffffff8170524a)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81732ae9)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ab38)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/igmp.c (ffffffff817960c4)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_drop_socket
```
```
In net/ipv6/af_inet6.c (ffffffff817c2fa3)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817ddb38)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff817ec33a)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_close
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810173cc)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018b58)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:snbep_cbox_put_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8189ec53)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d08ed)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff81180c24)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In mm/filemap.c (ffffffff811a222a)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811c06a4)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff811e9e63)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/kernfs/dir.c (ffffffff812b7e0a)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813159c0)
Location: arch/x86/include/asm/atomic.h:62
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
In fs/jbd2/commit.c (ffffffff81317b81)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8135b540)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In lib/genalloc.c (ffffffff8144eec0)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd790)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8167ad96)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff816f2ae2)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/core/sock.c (ffffffff8176774f)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/skbuff.c (ffffffff8176be1a)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8179e414)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea394)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/igmp.c (ffffffff81807498)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81830013)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184bc60)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8185b3d8)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff8186ff5b)
Location: arch/x86/include/asm/atomic.h:62
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810175dc)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018d28)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:snbep_cbox_put_constraint
```
```
In kernel/locking/spinlock.c (ffffffff818d4113)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d735d)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff8118c944)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In mm/filemap.c (ffffffff811b207a)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811d0c84)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff811fadad)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/kernfs/dir.c (ffffffff812cd5aa)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8132b9b0)
Location: arch/x86/include/asm/atomic.h:62
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
In fs/jbd2/commit.c (ffffffff8132db71)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81371b77)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In lib/genalloc.c (ffffffff8146d880)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff816a8a57)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81724202)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/core/sock.c (ffffffff8179660f)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/skbuff.c (ffffffff81798eea)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff817cce74)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818b89)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81824cc0)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81838528)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81861a93)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187d8ea)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8188d272)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff818a2ecb)
Location: arch/x86/include/asm/atomic.h:62
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810158ec)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810171b3)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8190b2a3)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810d639d)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff81191894)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In mm/filemap.c (ffffffff811b8d2e)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811d91f4)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff81205ab0)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff8120bea2)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff812dabaf)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff81340c8b)
Location: arch/x86/include/asm/atomic.h:62
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
In fs/jbd2/commit.c (ffffffff81342d02)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81384f6c)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In lib/genalloc.c (ffffffff81472f75)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/md/md.c (ffffffff8173c612)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/core/sock.c (ffffffff817b299f)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff817b74fa)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff817ec2a4)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/ip_fragment.c (ffffffff81815db5)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183936c)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81848174)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81859978)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffffffff8186247c)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/af_inet6.c (ffffffff818861b3)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a3a5a)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818b3947)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff818b55a6)
Location: arch/x86/include/asm/atomic.h:62
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/calipso.c (ffffffff818c94aa)
Location: arch/x86/include/asm/atomic.h:62
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015c9c)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81017996)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8199564a)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810de34d)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff8119e864)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In mm/filemap.c (ffffffff811ca266)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff811ee4d4)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff8121e8d0)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff812254a2)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff812ff48f)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8136529b)
Location: arch/x86/include/asm/atomic.h:63
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
In fs/jbd2/commit.c (ffffffff81367335)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff813a9249)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff817ae1e2)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In net/core/sock.c (ffffffff8182abaf)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff8182fafa)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81868098)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/ip_fragment.c (ffffffff81894fdc)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8b15)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff818c7bca)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff818d9878)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffffffff818e257f)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/af_inet6.c (ffffffff819073a3)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819258bc)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819366c7)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff8193831c)
Location: arch/x86/include/asm/atomic.h:63
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/calipso.c (ffffffff8194cb4a)
Location: arch/x86/include/asm/atomic.h:63
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016a3e)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101831f)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff819f1b7a)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810e691d)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811b3656)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
```
```
In mm/filemap.c (ffffffff811f0ca1)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8120edf7)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff81241620)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff81247a42)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff8132d14f)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8139399a)
Location: include/asm-generic/atomic-instrumented.h:136
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
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff813d8b92)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff817f40b5)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
```
```
In net/core/sock.c (ffffffff81876daf)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff8187a2b9)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818b81e5)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190dfd1)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff8191de9d)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819302b8)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff8195df83)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197e8e2)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198f437)
Location: include/asm-generic/atomic-instrumented.h:136
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819a5f3f)
Location: include/asm-generic/atomic-instrumented.h:136
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
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018aef)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a2d13a)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810f1f1d)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811c1d36)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
```
```
In mm/filemap.c (ffffffff81202afd)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8122171d)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmalloc.c (ffffffff81255d20)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (ffffffff8125c005)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff813444ef)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813ac6ba)
Location: include/asm-generic/atomic-instrumented.h:153
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
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff813f2a12)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81820095)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
```
```
In net/core/sock.c (ffffffff818971ef)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff8189aec9)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818dec45)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c3c1)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff8194caed)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8195f798)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81992ac4)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b47e3)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c5cf7)
Location: include/asm-generic/atomic-instrumented.h:153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819dc5ef)
Location: include/asm-generic/atomic-instrumented.h:153
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a18f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a9d30d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fa48d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d2386)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff81219f30)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81230f7a)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812771d4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/kernfs/dir.c (ffffffff8136c70e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813d6928)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8141f842)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81862555)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff818dfa8f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff818e5249)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8192cb85)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff819532fb)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819b12a1)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819c462d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff819fe3e4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23275)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a34b6b)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a4c2df)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab0f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81ad4aed)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110626d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811de926)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff812278a0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8123f185)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81286cb4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812bdfcb)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff813848be)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813f0968)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81439662)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81894185)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff81911c3f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819173d9)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8195ee85)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81989d67)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819e7fcd)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff819fb1cd)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a34fd4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a59ce4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6b6bb)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a82eaf)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c682)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81bcca2d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8111118d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff812541df)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8126cb28)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81287d2e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/swap_state.c (ffffffff812b9234)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812f3920)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813cd54f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813cf30f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8143ca59)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8148987d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff819637a5)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In net/core/sock.c (ffffffff819e3c3f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819e9c69)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81a32175)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a62105)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ad5edd)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ae9afd)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b27a5f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b2ab11)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b52288)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b64616)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b7cd16)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb82)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81c4558d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110e30d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81be6a7f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81277482)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8129192e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff812c49f4)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812ff11d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813df17f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e0f3f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff81458dd9)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814a6eb6)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8196a0a2)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In net/core/sock.c (ffffffff819e35cf)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819e9a09)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff819f4e22)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a344bd)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69285)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1a6e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ae24bd)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81af699d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b36337)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b394a1)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5ff0c)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81b72da6)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b8bdc6)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81bbb2b0)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e030)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81c3881d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee1d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81bd8815)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8127c4e5)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81296c4e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff812cb6a5)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81305d92)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff813e5d04)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e7b6f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8145e7d4)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814ace06)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8194da32)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
```
```
In net/core/sock.c (ffffffff819ca88f)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819cfb29)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff819dafaa)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a1b52d)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51a05)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abca8e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81acd3dd)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ae20ed)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81b23f14)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b27171)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e1ed)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81b61870)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81b7ac3e)
Location: include/asm-generic/atomic-instrumented.h:149
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81baa8f0)
Location: include/asm-generic/atomic-instrumented.h:149
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
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810228ed)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81d570fd)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8112e6bd)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81cb9e6f)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff812ba50d)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812d75fe)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/swap_state.c (ffffffff8131077c)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134fbf9)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff81437884)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8143988f)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff814b3b44)
Location: include/linux/atomic/atomic-instrumented.h:116
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
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff815052f1)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff819f2e32)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
```
```
In net/core/sock.c (ffffffff81a789cf)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81a7f679)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81a8b63d)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81acec0d)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a545)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7981e)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81b8bd9d)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81ba188d)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81be8560)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81becdae)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c15526)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81c29341)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81c458fe)
Location: include/linux/atomic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81c77960)
Location: include/linux/atomic/atomic-instrumented.h:116
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810246e6)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81f29b85)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8114f8e1)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81e6b4b6)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff81317ba9)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813370d9)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8137b464)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c7e50)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff814b25fc)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff814b4907)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff8153d374)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81596cbe)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In block/blk-flush.c (ffffffff8167c095)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81688c0b)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b72cb9)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81bec3ff)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81c00c6b)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c4c27d)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90ac5)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0957a)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81d18a7d)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81d33e6d)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81d7fce6)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d85298)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0d2d)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81dc6733)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81de4a14)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81e1b90e)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810298a6)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff820d5a35)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff820d6c31)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In mm/filemap.c (ffffffff81359a58)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff8138af48)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813ae58a)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff813f8dfe)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8144c022)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff8154917c)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8154a39f)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff815dbb94)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff817388fa)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817470f9)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d0fa92)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81d9a0ff)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81db00ce)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e00fed)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4bf65)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece81e)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81ee190d)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81efc2ed)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81f4d9d3)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f52ce8)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80bc7)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81f97353)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81fb7184)
Location: include/linux/atomic/atomic-instrumented.h:121
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ff2ece)
Location: include/linux/atomic/atomic-instrumented.h:121
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810298d6)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff82158e15)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff82159fc1)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811cbbe1)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81279ab5)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In mm/filemap.c (ffffffff8138b3a5)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813bd576)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e2d77)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8142bbce)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81481835)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff81580d5f)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff81581fcf)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81613654)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff81774f3a)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817841fe)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d78ee8)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81e071ef)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81e203a8)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e72aad)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7665)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dbde)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81f4133d)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81f5bd1a)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/unix/af_unix.c (ffffffff81fad524)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb26d1)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0a3c)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff81ff7d08)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820178c1)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8206f14e)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102fa36)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff8223c695)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8223d841)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811dd8e1)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/trace/ring_buffer.c (ffffffff81294595)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In mm/filemap.c (ffffffff813b4ecc)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813e87e8)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8140d5b4)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
```
```
In mm/swap_state.c (ffffffff8146532b)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff814b087d)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/inode.c (ffffffff815b97db)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff815baaaf)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8164c454)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In block/blk-flush.c (ffffffff817b7261)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c650d)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e30069)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In net/core/sock.c (ffffffff81ec513f)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffff81ede285)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f321ed)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a115)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_uncharge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff73e8)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff82006f8d)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8202227a)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/tcp_ao.c (ffffffff820550bc)
Location: include/linux/atomic/atomic-instrumented.h:268
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
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8207fe61)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af068)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/mcast.c (ffffffff820c5958)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff820e6891)
Location: include/linux/atomic/atomic-instrumented.h:268
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8214324e)
Location: include/linux/atomic/atomic-instrumented.h:268
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009cce0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e54)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In kernel/fork.c (ffff8000100f427c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2a0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In kernel/exit.c (ffff8000100fa998)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff8000101205d4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffff80001012d2d8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffff80001012e900)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffff8000101302dc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffff80001013a3e8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff80001014c434)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001015026c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152ba8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159f48)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/locking/spinlock.c (ffff800010da746c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffff80001016c740)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff80001016ffc8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffff80001017d0a0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffff800010189060)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffff80001018a6d8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffff8000101ba3bc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffff8000101d719c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de254)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffff8000101f9884)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffff800010210ef4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff80001021a658)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffff800010230194)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102308f4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333f0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffff800010238090)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff8000102551c4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff80001025fee8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102784ac)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffff80001028a2cc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029c8b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffff8000102a543c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102a9aec)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (ffff8000102aeed8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffff8000102d18ac)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102ddb88)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffff8000103037bc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304e2c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff8000103053b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309b58)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/swap_state.c (ffff8000103215a4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327acc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a4d4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032b4e8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffff8000103562a8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035f584)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffff800010365f80)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff8000103729b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffff80001037dcd8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff80001038559c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff800010398314)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffff8000103c7854)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dc020)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffff8000103ea604)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5a8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffff800010424edc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffff800010428b98)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffff80001042fad4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In fs/kernfs/dir.c (ffff80001045374c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (ffff80001045ebc8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffff8000104611b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010465934)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010475acc)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff800010485768)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff8000104964f8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff8000104989cc)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8610)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104ca580)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d018c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bc4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df31c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df5b4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df95c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfc88)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dffb8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fda88)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffff80001051ce34)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In ipc/msg.c (ffff80001051fb80)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffff80001052d190)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532fcc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffff80001054710c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffff80001054e388)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffff80001056bc10)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffff80001057b5b4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e650)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580070)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010582840)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff8000105844d8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffff80001058571c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffff800010586734)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587404)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8ae8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffff8000105f0894)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffff8000105f4368)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffff8000106154b4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a04c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c28)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e8fa0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708cf4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffff8000107165e4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e6c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b00b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffff8000107fd480)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d528)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (ffff80001084cf5c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d99c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffff800011493260)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8668)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8ea8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d60fc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd278)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de0b4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In drivers/base/dd.c (ffff8000108ea8f8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd7f0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e408)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff80001094088c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ab28)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffff800010977088)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffff800010a1c1b0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffff800010a210b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac499c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca41c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbd70)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffff800010ae7f60)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afdd20)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffff800010b0dd28)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14154)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b1a8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d8c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81108)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffff800010b9e5a4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffff800010bab774)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffff800010bb365c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/dev.c (ffff800010bcb3d8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/neighbour.c (ffff800010be61cc)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffff800010c068d0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08264)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock_map.c (ffff800010c21004)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c32404)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c4734c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ee8c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bdbc)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d834)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c1f4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffff800010c9c4ec)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffff800010cb2d3c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf24c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc030)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdce54)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce6198)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/af_inet6.c (ffff800010cf6618)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (ffff800010d0f5b8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f60c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d25510)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a23c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffff800010d32ef4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37794)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3ce00)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eff4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d44c4c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/calipso.c (ffff800010d4d5d8)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51f6c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffff800010d577a4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68dac)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e84)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6aba4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/arm/kernel/machine_kexec.c (c0315124)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In arch/arm/mm/pgd.c (c031f9c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In kernel/fork.c (c0352098)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (c03583ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/exit.c (c03587a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (c0374204)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (c037d15c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (c037e394)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (c037fb94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c0389da0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c039a044)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (c039dfb0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c039fc6c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c03a6d54)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (c03a96a8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/power/process.c (c03baa10)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (c03cdb68)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (c03d7914)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (c03d8ca8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (c0403f74)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (c0419e44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (c041fc98)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/cgroup/cpuset.c (c0423fa0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/debug/debug_core.c (c0439b44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/tracepoint.c (c044d36c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/trace/ftrace.c (c044f5d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c0456064)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace.c (c04606b8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (c046b730)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c9a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c046f19c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (c0473b1c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (c048845c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/core.c (c0491fb8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0492dc4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_uncharge_memlock
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/bpf/hashtab.c (c04aa600)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (c04b997c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/bpf/cgroup.c (c04bf04c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c3300)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:exclusive_event_destroy
```
```
In kernel/events/callchain.c (c04d2e54)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (c04d436c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d7a40)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (c04dab0c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (c04f8c20)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (c0503100)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/memory.c (c0517610)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/mmap.c (c0521e08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (c052312c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (c05235f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c05266c4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c052a76c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_state.c (c0539dec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c053ef08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/frontswap.c (c054106c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c0541a08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/ksm.c (c0544f94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c054b330)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (c0553358)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memcontrol.c (c0557c7c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In mm/zpool.c (c055f1fc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In mm/zsmalloc.c (c05613cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/open.c (c05677d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (c056e374)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (c057e938)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/inode.c (c058c6a0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c05a481c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c05b533c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (c05c1a34)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (c05c3b58)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/eventpoll.c (c05c76ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (c05d687c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/mbcache.c (c05edc78)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (c05f14fc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (c05f890c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In fs/kernfs/dir.c (c0616290)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (c061f610)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (c0621870)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0624fd8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0636e00)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c0638318)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (c0645838)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (c065868c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (c065a29c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (c065b018)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c067bebc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (c068df1c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (c0690f0c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0692ee0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (c069b47c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c06a0c8c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c06a0f10)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c06a1210)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c06a1578)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c06a1874)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (c06baee0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (c06d948c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In ipc/msg.c (c06dabe0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (c06e59b0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In security/keys/keyctl.c (c06ea8d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (c06fc430)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (c06fe040)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (c071f1b4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In security/tomoyo/common.c (c072c110)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0730a6c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c073254c)
Location: arch/arm/include/asm/atomic.h:226
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
In security/tomoyo/environ.c (c07331e8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c073466c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (c0734ddc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
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
In security/tomoyo/group.c (c0735814)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0735ed8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (c07370f4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (c0738134)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0738310)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (c0793c38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c0795360)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (c079c9cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (c079ffe8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (c07a5d44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-iocost.c (c07be740)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/genalloc.c (c07eaf04)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/sbitmap.c (c0811e14)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fae0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (c0883f98)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/ats.c (c08a1014)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (c08c804c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (c091eb0c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (c09281d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (c0958d84)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/tty/tty_buffer.c (c0965680)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (c1593ee4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a4c38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (c09a5448)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/connector/cn_queue.c (c09cc664)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/connector/cn_proc.c (c09cd038)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/base/dd.c (c09d8aac)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (c09e8218)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (c0a26830)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (c0a2963c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c0a4a2e4)
Location: arch/arm/include/asm/atomic.h:226
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
In drivers/net/ppp/ppp_generic.c (c0adc1f4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (c0af3e70)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (c0af7030)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/i2c/i2c-core-base.c (c0b92a58)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab21c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (c0babe90)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (c0bcb744)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (c0bdc8dc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (c0bebfd4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf2034)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpuidle/coupled.c (c0c05518)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_set_done
  - drivers/cpuidle/coupled.c:cpuidle_coupled_set_done
```
```
In drivers/mmc/core/sdio_bus.c (c0c15cec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c48)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (c0c646f4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (c0c80534)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In sound/core/pcm_native.c (c0c90d24)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data_close
```
```
In net/core/sock.c (c0cc8860)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/skbuff.c (c0ccdda4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/core/sysctl_net_core.c (c0ce10b8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0ceaa3c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/neighbour.c (c0cfea7c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/filter.c (c0d1b808)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (c0d1fa54)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2112c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/core/net-sysfs.c (c0d23860)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/sock_map.c (c0d38864)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/core/bpf_sk_storage.c (c0d48e2c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/sched/cls_api.c (c0d51388)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_offload_dec
```
```
In net/sched/act_api.c (c0d5824c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5eff4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/ip_fragment.c (c0d6eadc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_timewait_sock.c (c0d7ac48)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c8b0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (c0d86c6c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/tcp_ipv4.c (c0d99d3c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (c0da7694)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (c0dbe7ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (c0dca30c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (c0dce034)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv4/ipmr.c (c0dd8064)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (c0de6df8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/xfrm/xfrm_state.c (c0ded014)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/unix/af_unix.c (c0df7874)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (c0dfb4c0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/ipv6/af_inet6.c (c0dfcf18)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (c0e13db8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (c0e241f8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/ipv6/udp.c (c0e28840)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (c0e2e214)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (c0e35c80)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (c0e39b60)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e40050)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c0e4204c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_free
```
```
In net/ipv6/ip6mr.c (c0e470e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/calipso.c (c0e4f9f4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (c0e53048)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (c0e56ec8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67598)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e683fc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e69104)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xdp_umem.c (c0e7b15c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
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
In arch/powerpc/sysdev/xive/common.c (c0000000000bd1c4)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c0000000001243a0)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_scan_interrupts
```
```
In kernel/bpf/syscall.c (c000000000304c48)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
```
```
In mm/filemap.c (c000000000362430)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (c00000000038f3ac)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f6bf4)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (c00000000044a48c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (c00000000056cb48)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (c000000000603308)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (c000000000606e54)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (c00000000066a17c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (c000000000bd2070)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
```
```
In net/core/sock.c (c000000000c81694)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (c000000000c86694)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (c000000000ceb518)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (c000000000d2b7c4)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97e50)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (c000000000dae99c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (c000000000dc9ec4)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (c000000000e1bdc8)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4df2c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e65454)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (c000000000e85dd8)
Location: arch/powerpc/include/asm/atomic.h:100
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_event.c (ffffffe0000b97d4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In kernel/fork.c (ffffffe0000c00f4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffe0000c43c8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In kernel/exit.c (ffffffe0000c47d2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffe0000d91a6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffe0000e1446)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffe0000e2556)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffe0000e3864)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffe0000e9b6e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffe0000f59a2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffe0000f87c4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa862)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffe0000ff9f6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffffffe000101d50)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/power/process.c (ffffffe00010d7f4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffe0001161dc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffe00011e3de)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffe00011f336)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffffffe00013fe08)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffe0001502c8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155500)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/cgroup/cpuset.c (ffffffe00015912c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/tracepoint.c (ffffffe00016f56c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/trace/ftrace.c (ffffffe0001710b6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177172)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffe000184ab8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffe000187a98)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018928c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a716)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe00019de18)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/hashtab.c (ffffffe0001afc3a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffe0001be3da)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/bpf/cgroup.c (ffffffe0001c276a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001cb1a8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:sw_perf_event_destroy
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
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffe0001d1cc6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffe0001d31f2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (ffffffe0001d442c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffe0001edcea)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffe0001f5e80)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffe000210286)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffe00021102e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffe000211442)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213af2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In mm/swap_state.c (ffffffe0002228f8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffe0002279fe)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffe000229522)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffe00022a2b0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/memcontrol.c (ffffffe00024486e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In mm/zpool.c (ffffffe00024baf4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffffffe00025398e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffe00025823c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffe000265f28)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffe00028679c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe000291a36)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffe00029ee2c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a0e06)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io_uring.c (ffffffe0002af886)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffe0002c4182)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffe0002c6a04)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffe0002cc7ec)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In fs/kernfs/dir.c (ffffffe0002e5d06)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (ffffffe0002ee79e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffe0002f048c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f2dc8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffe00030109e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffe00030213c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffe00030c74a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffe00031b13e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffe00031c612)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffe00031d0d4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffe000335110)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffe0003437be)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffe000345e00)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe0003478cc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffe00034ed08)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffe0003538b0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffe000353b0a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffe000353d7a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffe000353ff4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffe0003542a4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036bfd4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffe00037030e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In ipc/util.c (ffffffe0003848fe)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In ipc/msg.c (ffffffe000385ed2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffe00038eeec)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In security/keys/keyctl.c (ffffffe00039369e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffe0003a2894)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
```
```
In security/selinux/hooks.c (ffffffe0003a37b8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffe0003c08b4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffe0003cb396)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffe0003cf738)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffe0003d0ca4)
Location: arch/riscv/include/asm/atomic.h:77
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
In security/tomoyo/environ.c (ffffffe0003d17c0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffe0003d2c0a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (ffffffe0003d3200)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
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
In security/tomoyo/group.c (ffffffe0003d3dfe)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffe0003d447e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffe0003d5364)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d60c8)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d6226)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
```
```
In block/blk-flush.c (ffffffe000428076)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffe000429516)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffe00042f6a6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffe0004323ec)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffe00044ae72)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffe0004944c0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffe0004bf3c2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d6136)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffe0004dfb5e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f489a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffe0005170ee)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffe00052c1ba)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffe000536722)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffe00002e364)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/connector/cn_queue.c (ffffffe000573e3e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (ffffffe0005744f0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In drivers/base/dd.c (ffffffe00057e832)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffe00058c476)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b1ef6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a52)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c81da)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dda50)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bef6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffe00064031a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffe0006431e6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b93d6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c88da)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_put
```
```
In drivers/md/md.c (ffffffe0006dd492)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffe0006ef976)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffe0006fae76)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe000700930)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe000712750)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/ras/debugfs.c (ffffffe00073697e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffe00073ce54)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/skbuff.c (ffffffe000741858)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/datagram.c (ffffffe00074a68c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/sysctl_net_core.c (ffffffe000752294)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe00075a8e4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/neighbour.c (ffffffe00076b420)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffe000781664)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffffffe000784d8c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786284)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe000789128)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/sock_map.c (ffffffe00079aaee)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/devlink.c (ffffffe00079c26a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7d4e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/cls_api.c (ffffffe0007b0ecc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffe0007b4982)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffe0007babe0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d09c6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d170a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d33e2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffe0007d4a98)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffe0007db774)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5f78)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb2d6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffe0007f53da)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007fa544)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/arp.c (ffffffe0007fefea)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffe00080b108)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffe0008150b0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817c98)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv4/ipmr.c (ffffffe00082098a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082ab50)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffe000831fba)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffe00083e1fa)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/af_inet6.c (ffffffe000841440)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/addrconf.c (ffffffe00084fa02)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffe0008552be)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861bea)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffe000862468)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000865c98)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffe00086aa86)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffe000871e90)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874bd4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe000879696)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b1b6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_free
```
```
In net/ipv6/ip6mr.c (ffffffe00087f60a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882242)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv6/calipso.c (ffffffe00088637c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a5f0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d906)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe00088df86)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bfe0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cae6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d600)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xsk.c (ffffffe0008ac224)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192de)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab0f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a7395d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ff57d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d6f46)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff8121fef0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff812377d5)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127f304)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b65ab)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8137ce9e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813e8f48)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff81431c42)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff8183a005)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff818b1c3f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff818b73d9)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818fee55)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff81929bd7)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81987e3d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff8199af6d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff819d4664)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9374)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a0ad4b)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a2253f)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a1af)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81a2fcbd)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810ef76d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811c9d06)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff812130a0)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8122a65f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127111e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812a7781)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8136d95e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813d99c8)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff814226c2)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81801675)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff8186bb8f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff81871329)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff818b8c85)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3987)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819418fd)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81954a2d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81991424)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6134)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c7b0b)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff819df2ff)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aacf)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81adfd6d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff810fc73d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811d4d16)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff8121dc90)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81235575)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127d0a4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b43bb)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8137a96e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813e62c8)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8142dde2)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff81889635)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff81902c3f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819083d9)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff8194fe85)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff8197ad67)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819f260d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81a0580d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f0e4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a63df4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a757cb)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a8cfbf)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad0f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/spinlock.c (ffffffff81aec56f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffffffff8110796d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/bpf/syscall.c (ffffffff811e3046)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In mm/filemap.c (ffffffff8122cd00)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8124567c)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128cc5b)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812c4887)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/kernfs/dir.c (ffffffff8138e46e)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/jbd2/transaction.c (ffffffff813fb7b8)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In ipc/msg.c (ffffffff8144483f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In drivers/md/md.c (ffffffff818a6d65)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/core/sock.c (ffffffff81923bef)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffffffff819293b9)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/filter.c (ffffffff81971855)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d2c0)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff819fc45d)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffffffff81a0fddd)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aba4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a702f4)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a81eeb)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/calipso.c (ffffffff81a99c7f)
Location: include/asm-generic/atomic-instrumented.h:148
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
