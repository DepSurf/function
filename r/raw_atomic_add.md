# Function: <code>raw_atomic_add</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027411)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102bacf)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eb68)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff82159fe3)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811e5fbb)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff8123bdf3)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81279a59)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff8137ac16)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff8138c3de)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd51a)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e7e2d)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff814224b4)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8142b57e)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81465578)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff814676cf)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81472525)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8148036d)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148a50f)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff81527697)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff81555182)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff81583a0e)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff815c2345)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff815dc8b4)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600a8c)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In lib/sbitmap.c (ffffffff818e51fd)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81a6668c)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ee28)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81d696e2)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d78ec2)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb7c1)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81e07049)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122cd)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81e72ba2)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81ea3a8d)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea761f)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a82)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ffb0)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2cba0)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378ac)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f43597)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa7677)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81fade0a)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81fe887f)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd084)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b3fc)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82070c75)
Location: include/linux/atomic/atomic-arch-fallback.h:535
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102d571)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81031c2f)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220b88)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8223d863)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811fbd0b)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff81255cc3)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81294539)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff813a3e16)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In kernel/context_tracking.c (ffffffff82224458)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_enter
```
```
In mm/filemap.c (ffffffff813b9747)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e866e)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81412a9a)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141fd65)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/page_alloc.c (ffffffff8144f1f9)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff81464d68)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81494817)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8149895d)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a28b7)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ae45d)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b9dbf)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff8155c4d7)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8158b454)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/kernfs/dir.c (ffffffff815bc4ee)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff81600148)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff81615194)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816397dc)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In block/blk-mq.c (ffffffff817c4cff)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In lib/closure.c (ffffffff81925bc2)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In lib/sbitmap.c (ffffffff8192c1fd)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81ab91bf)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81af18e8)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81e20278)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81e30041)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84301)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81ec38b0)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf48d)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81f32315)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81f6638d)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a0d3)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81f85dd2)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4690)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1be0)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd97c)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820094f7)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82074927)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff8207a6da)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff820b73cf)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc199)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faee7)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82144e85)
Location: include/linux/atomic/atomic-arch-fallback.h:544
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
