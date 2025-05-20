# Function: <code>arch_atomic_add</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016fb0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101853a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d460)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810e69b6)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81105e68)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_percpu_data
```
```
In kernel/profile.c (ffffffff8110f8c2)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811db1d3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811f9c0f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff8120ecef)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81247662)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8126e819)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278c4f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81286562)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (ffffffff812f2985)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8132c633)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81363fe6)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813736ea)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138b160)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff813d8342)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81619071)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff8176cf65)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff81800668)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818430d9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81878245)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c0b3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff818b8276)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff818d8c52)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81903981)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912328)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e84)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995340)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819b2df0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017730)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018d0a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ab28)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810f1fb4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811139f4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8111afb2)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811eb513)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff8120c2aa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff81221581)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbc3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812824b9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128d315)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8128fd87)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81307605)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81343ab3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137c288)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff8138badb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a33d4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff813f2fba)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff816361e1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817915b5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8182c745)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8186f0de)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81898725)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c913)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff818decd6)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff81905442)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81931b3e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940b05)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194462b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194d236)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb529)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbc26)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819e9d4e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018f1c)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a393)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbb4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810fa414)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8111d5e4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81125690)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81201f63)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff81230dac)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81272510)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81276d80)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e490)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2671)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812aaf4a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81328bf9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8136bd23)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a2cfd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813b6734)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ce077)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8141eb0e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a410)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817cfe65)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8186ec5c)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818b33da)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff818e2ce0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e7918)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff8192cc16)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8195324b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8196685e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff8199523a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a50cd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c1b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b19f1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a124)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a71f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a5832c)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101989d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad13)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e557)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff811061f4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81129b7f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81131650)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff8120ee13)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff8123efd3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81281370)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81286860)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812add3e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b3b04)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bc8d0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8133b9a9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81383ef3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813bbb5d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813cf64f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e7b35)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8143895e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8168cb00)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff81800ce5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818a0a39)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818e5cfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81914ec0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919cfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff8195ef16)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8198910e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8199d252)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd8a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbdcd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df8bb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8764)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60c5b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a712c0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a90abb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b056)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e72f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051eba)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff81111224)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81138036)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff811407fe)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/events/core.c (ffffffff8124019b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8126c848)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81287922)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b3847)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812b8e01)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e4871)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e941d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f1dfc)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8137564a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff813ce859)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81404030)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff81419310)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81430be3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff81488bb1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8173eb08)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/usb/core/devices.c (ffffffff818d13c5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8197073c)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819b8faa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819e7fe0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb6e9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a32236)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a620dd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a76492)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81aba4e2)
Location: arch/x86/include/asm/atomic.h:53
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
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5200)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd5d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad66f4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b226b1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b269ec)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b59b37)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f53)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8bcf0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab705)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b54d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101edcf)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fda)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8110e3a4)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81133876)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8113cb55)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff8118496f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In kernel/events/core.c (ffffffff8124a6eb)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8127728f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81291762)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bf321)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812c4573)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef264)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f48cb)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fe37d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130441b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff81383524)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff813bb95d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/kernfs/dir.c (ffffffff813e0489)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81417280)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff8142d3c9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814499a6)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff814a61f8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8175aa38)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81c26851)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819bb41a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819e7ab0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb409)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a34576)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81a3f626)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6925f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81a7f202)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5922)
Location: arch/x86/include/asm/atomic.h:51
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
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0eb0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d5d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae2cd1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b310b1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b35567)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b6819a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a33)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b9b162)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbb95f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101c90b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102024e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d0a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee34)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81134449)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8113df53)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811857a5)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In kernel/events/core.c (ffffffff8124e833)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8127c2f7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812975bd)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c43c5)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff812cb1f8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5ed4)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fae4f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81305037)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130b4e0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff8138c297)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff813c2a53)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/kernfs/dir.c (ffffffff813e6f0d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141de96)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff8143408e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144f326)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff814ac186)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff81716252)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173e8d8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81c18cce)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8199fc2c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819cda80)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1919)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a1b5e6)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81a4e6f7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/core/bpf_sk_storage.c (ffffffff81a519df)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81a681e2)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b32)
Location: arch/x86/include/asm/atomic.h:51
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
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbeb0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3dcc)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acdc20)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1ede1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b2315c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b564d5)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d3d)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8ab5a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab56f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101f9db)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810226f8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b20a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8112e6d4)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811611c5)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811adb86)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In kernel/events/core.c (ffffffff8128c6a3)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff812ba4a8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812d7f71)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In mm/page_alloc.c (ffffffff81308281)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813101f3)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813404b4)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81344c86)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134edc7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135658b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff813d9857)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff81412a7c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff81438ab8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8147064a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff81487ad0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2ea7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff81504669)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff81793505)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf058)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81d2833e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81a4c8ed)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81a7d290)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a814e9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81acecc6)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81b07433)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a51f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81b21702)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d974)
Location: arch/x86/include/asm/atomic.h:51
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
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78fb0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b8245c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8c5ee)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7301)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3dcb)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be8f2e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81c1cb43)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e8fa)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81c56c75)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c77e98)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810227ba)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810261c1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15a28)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8114f900)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff81193faa)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811dfaf3)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/events/core.c (ffffffff812e12b9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff812f239f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317a5a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81338482)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81370586)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8137ac88)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff813af44b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff813b1f7b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813baba1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c599e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813cf44f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff814609b5)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8148961c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff814b3b4b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814f1aea)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff8150b3c3)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152a32b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff815962ef)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff818cc009)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb5ae)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81ef4399)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81b72c97)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81bbb08c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81bec267)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf51b9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81c4c362)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81c8bd7c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90a8f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81ca9cc2)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcde2)
Location: arch/x86/include/asm/atomic.h:51
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
In net/ipv4/tcp_ipv4.c (ffffffff81d090a0)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1295c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1cc46)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7aba7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81d815ba)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81db93fe)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb548)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81df605e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1cf1d)
Location: arch/x86/include/asm/atomic.h:51
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810273ba)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102baa1)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd158)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff820d6c53)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811d1f7b)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff81225803)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/events/core.c (ffffffff81349819)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff8135a9af)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138aeec)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813afc8a)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff813ed518)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813f87bc)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff8142f9db)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff81431aad)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143d048)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8144a3de)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8145471f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff814f08f7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8151cfd3)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff8154bd4e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff8158c364)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff815a6044)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8ccb)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In lib/sbitmap.c (ffffffff818a2d29)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d489)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54848)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81cf9fa8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d0fa70)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81d6071c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81d98ca7)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da36d9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81e010e2)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81e482c9)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4bf1f)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81e66cc2)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ec19a2)
Location: arch/x86/include/asm/atomic.h:51
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
In net/ipv4/tcp_ipv4.c (ffffffff81ecdd80)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed879c)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee3d26)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f47b77)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81f4dedf)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81f8944e)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c634)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81fca5c8)
Location: arch/x86/include/asm/atomic.h:51
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff444d)
Location: arch/x86/include/asm/atomic.h:51
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027411)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102bacf)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eb68)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff82159fe3)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811e5fbb)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff8123bdf3)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81279a59)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff8137ac16)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff8138c3de)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd51a)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e7e2d)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8142b57e)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81465578)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff814676cf)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81472525)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8148036d)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148a50f)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff81527697)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff81555182)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff81583a0e)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff815c2345)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600a8c)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In lib/sbitmap.c (ffffffff818e51fd)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81a6668c)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ee28)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81d696e2)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d78ec2)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb7c1)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81e07049)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122cd)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81e72ba2)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81ea3a8d)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a82)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ffb0)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378ac)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f43597)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa7677)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81fade0a)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81fe887f)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd084)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b3fc)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82070c75)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81031c2f)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220b88)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8223d863)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811fbd0b)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff81255cc3)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81294539)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff813a3e16)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In kernel/context_tracking.c (ffffffff82224458)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_enter
```
```
In mm/filemap.c (ffffffff813b9747)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e866e)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81412a9a)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/page_alloc.c (ffffffff8144f1f9)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff81464d68)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81494817)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8149895d)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a28b7)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ae45d)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b9dbf)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff8155c4d7)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8158b454)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/kernfs/dir.c (ffffffff815bc4ee)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff81600148)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816397dc)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In block/blk-mq.c (ffffffff817c4cff)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In lib/sbitmap.c (ffffffff8192c1fd)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81ab91bf)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81af18e8)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81e20278)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81e30041)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84301)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81ec38b0)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf48d)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81f32315)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81f6638d)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81f85dd2)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4690)
Location: arch/x86/include/asm/atomic.h:31
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
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd97c)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820094f7)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82074927)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff8207a6da)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff820b73cf)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc199)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faee7)
Location: arch/x86/include/asm/atomic.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82144e85)
Location: arch/x86/include/asm/atomic.h:31
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void arch_atomic_add(int i, atomic_t *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da7a40)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/smp.c (ffff80001009c238)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6dbc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In virt/kvm/kvm_main.c (ffff8000100bf2b0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_fault
  - virt/kvm/kvm_main.c:kvm_create_vm
Direct callers:
  - virt/kvm/kvm_main.c:hardware_enable_nolock
```
```
In virt/kvm/arm/mmu.c (ffff8000100cafa8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_pud
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In kernel/fork.c (ffff8000100f4880)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffff8000100fa27c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/exit.c (ffff8000100fd4c0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010107e38)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/umh.c (ffff80001011ac94)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cd54)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/nsproxy.c (ffff80001012b448)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (ffff80001012d080)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/async.c (ffff80001012ebc0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/kmod.c (ffff800010130674)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (ffff80001013114c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff800010da1990)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
Direct callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffff80001014c3f0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001014e9e8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffff800010152ca8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/sched/cpupri.c (ffff800010159f20)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffff80001015bf40)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010163144)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/locking/qrwlock.c (ffff80001016c8d8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff8000101700a8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffff800010176ccc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (ffff80001017868c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179c74)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188fc8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (ffff80001018a5e0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffff80001019171c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffff800010198dac)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/futex.c (ffff8000101ba088)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
```
In kernel/module.c (ffff8000101c4dcc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4ec8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/cgroup/namespace.c (ffff8000101da3c8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de324)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/utsname.c (ffff8000101e5328)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e65cc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffff8000101e787c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffff8000101e94dc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/debug/debug_core.c (ffff8000101f9848)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/relay.c (ffff80001020b850)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/ring_buffer.c (ffff8000102184bc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_reader
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace.c (ffff80001022160c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/blktrace.c (ffff800010235cfc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In kernel/trace/fgraph.c (ffff80001023820c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_kdb.c (ffff800010254ff4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff800010260130)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/cpumap.c (ffff80001028888c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/offload.c (ffff800010289ff0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffff800010296dec)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_refresh
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/events/uprobes.c (ffff8000102a8428)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a9f78)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/jump_label.c (ffff8000102ab598)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In mm/filemap.c (ffff8000102b0dd4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b77e4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd1f4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c3408)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffff8000102c50d4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102ca118)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d60f4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102dda88)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mmu_context.c (ffff8000102dff78)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f2120)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa178)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffff8000102fe388)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffff8000102ffda4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304d54)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffff800010304f14)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030abf8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/page_alloc.c (ffff800010319034)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (ffff80001031ecfc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff800010320a98)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffff8000103219b4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327e80)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/frontswap.c (ffff80001032a98c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032c360)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffff800010335e84)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff80001033b650)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033d020)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffff800010341b5c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffff80001034e088)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff8000103530c0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010354a48)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035d57c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff800010365f24)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff800010372648)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (ffff800010375c50)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memfd.c (ffff80001037c5dc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dda4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffff800010385858)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffff800010386d40)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffff80001038c798)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
  - fs/exec.c:kernel_read_file
```
```
In fs/pipe.c (ffff80001038fd44)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dcache.c (ffff8000103a8760)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffff8000103aea0c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
```
```
In fs/file.c (ffff8000103b1d48)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffff8000103bad90)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
Direct callers:
  - fs/namespace.c:mnt_init
```
```
In fs/fs-writeback.c (ffff8000103c8008)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffff8000103d5a70)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/buffer.c (ffff8000103dbf14)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffff8000103e0e68)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffff8000103e4d28)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/proc_namespace.c (ffff8000103e7a18)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (ffff8000103ea4fc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103edee4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
```
In fs/userfaultfd.c (ffff8000103f6d9c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffff8000103faa74)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffff800010403020)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_timeout_fn
```
```
In fs/verity/enable.c (ffff800010411aa0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_script.c (ffff80001041d984)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (ffff80001041f9dc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010423158)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/mbcache.c (ffff800010425828)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffff80001042bf6c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042d27c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/quota/dquot.c (ffff80001043237c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffff800010439984)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In fs/proc/root.c (ffff80001043c974)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043ed5c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/proc_sysctl.c (ffff80001044b9d4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (ffff800010453d24)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_get
```
```
In fs/kernfs/file.c (ffff8000104552b8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/mount.c (ffff800010457a94)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/dir.c (ffff80001045bd50)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffff80001045d074)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffff80001045ea34)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffff800010460e08)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475b28)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff800010479608)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff8000104804e0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/mballoc.c (ffff80001048f8d4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In fs/ext4/mmp.c (ffff800010499034)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffff8000104a4188)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffff8000104a806c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c04f4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffff8000104c4e44)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffff8000104cca14)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffff8000104cf060)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d15b8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d8c60)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffff8000104e4cc8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffff8000104e8d64)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fd9f8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffff800010503b9c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
Direct callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In fs/fuse/file.c (ffff80001050c098)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In fs/fuse/inode.c (ffff80001051244c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffff80001051d5b0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffff80001051f5b4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffff80001052c248)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd10)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffff80001052e5ac)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (ffff800010533008)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (ffff8000105351dc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff80001053570c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff80001053667c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (ffff80001054e3e0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffff8000105569c4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffff80001056721c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/xfrm.c (ffff80001056bb74)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffff80001057d460)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffff80001057e6d8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff80001058055c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffff80001058423c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffff800010586720)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001146b144)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/domain.c (ffff800010594cd0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy_unpack.c (ffff800010598ab4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In block/bio.c (ffff8000105dd138)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (ffff8000105e0c04)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-map.c (ffff8000105e9834)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-mq.c (ffff8000105f0824)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4280)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-iocost.c (ffff8000106153f8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/iov_iter.c (ffff80001062dea8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/rhashtable.c (ffff800010636de8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/sbitmap.c (ffff80001066a164)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c08)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e7490)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff8000107010e4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708d10)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bd40)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/ats.c (ffff800010716668)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e94)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c27c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af44c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
```
In drivers/amba/bus.c (ffff8000107b943c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (ffff8000107bf7c4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (ffff8000107fd310)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d474)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b00c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/tty/tty_buffer.c (ffff80001085d24c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (ffff80001086a538)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a85f0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8f94)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
```
```
In drivers/char/virtio_console.c (ffff8000108b2ab4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d62ec)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd35c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (ffff8000108de184)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/base/core.c (ffff8000108e7384)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (ffff8000108ea818)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (ffff8000108f6e24)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffff8000108fd2cc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffff800010902c78)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (ffff800010905140)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
```
```
In drivers/base/power/domain.c (ffff8000109086ec)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
```
```
In drivers/block/loop.c (ffff800010922744)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e3e8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff800010940928)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952e10)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ca70)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c904)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (ffff80001096f9d0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffff800010976fcc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
```
In drivers/scsi/sg.c (ffff80001098f0d0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffff8000109dba5c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9b84)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a0041c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a08ea0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In drivers/usb/core/hub.c (ffff800010a19adc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffff800010a1e3b0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffff800010a20aa8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (ffff800010a259d8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/devio.c (ffff800010a2e9b0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/devices.c (ffff800010a34cf8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (ffff800010a35fc8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37344)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f0c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba0ec)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010ababc8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac3fe4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_update
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc8bc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffff800010aefe88)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_handle_request
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:rdev_size_store
```
```
In drivers/md/md-bitmap.c (ffff800010af8308)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010affdf0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:dm_issue_global_event
```
```
In drivers/md/dm-stripe.c (ffff800010b066e0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffff800010b0a298)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0ae68)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffff800010b0dc18)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14048)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a748)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b338)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b1f8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b8128c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/perf/arm-cci.c (ffff800010b91d78)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/ras/debugfs.c (ffff800010b9e520)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In net/core/sock.c (ffff800010badc74)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb7d90)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffff800010bbc8bc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/net_namespace.c (ffff800010bc1fd8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bcb48c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In net/core/neighbour.c (ffff800010be5fa8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffff800010bfdb14)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow_offload.c (ffff800010c0873c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffff800010c0eca8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/bpf_sk_storage.c (ffff800010c31a54)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_generic.c (ffff800010c3801c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c4360c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c47628)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4dba4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/route.c (ffff800010c58780)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_output.c (ffff800010c62408)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b9c8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cfdc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffff800010c751a4)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c7a518)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cd20)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93f88)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
```
```
In net/ipv4/raw.c (ffff800010c98874)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f588)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5948)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6698)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf628)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ping.c (ffff800010cc0dc8)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccdffc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e50)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde0ac)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/unix/af_unix.c (ffff800010cf409c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf84b0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffff800010d0110c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffff800010d1546c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/udp.c (ffff800010d276a0)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d2abcc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c74)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d400cc)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffff800010d45a60)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48c80)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52560)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffff800010d5b494)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68660)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a65c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ad3c)
Location: arch/arm64/include/asm/atomic.h:28
Inline: True
```
**Symbols:**

```
ffff8000100b74b0-ffff8000100b74cc: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff8000100f1720-ffff8000100f173c: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff800010134360-ffff80001013437c: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff8000101d0028-ffff8000101d0044: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff8000102179e8-ffff800010217a04: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff8000102950e0-ffff8000102950f8: arch_atomic_add (STB_LOCAL)
ffff8000103b4980-ffff8000103b499c: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff80001048e3e0-ffff80001048e3f8: arch_atomic_add (STB_LOCAL)
ffff8000104cd9d0-ffff8000104cd9ec: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff800010501880-ffff80001050189c: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff800010ae73f8-ffff800010ae7410: arch_atomic_add (STB_LOCAL)
ffff800010b1441c-ffff800010b14438: arch_atomic_add.constprop.0 (STB_LOCAL)
ffff800010c8b590-ffff800010c8b5a8: arch_atomic_add (STB_LOCAL)
ffff800010d37160-ffff800010d37178: arch_atomic_add (STB_LOCAL)
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101989d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad13)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e6b7)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810ff504)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112215f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81129e00)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81207433)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff81237623)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff812799c0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127eeb0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a631e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ac0e4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b4eb0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81333f89)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8137c4d3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b413d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813c7c2f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e0115)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff81430f3e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81652580)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817b90c5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818468b9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff818b4ec0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9cfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff818feee6)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff81928f7e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8193d0c2)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff8196bbfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bc3d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f72b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819885d4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a002eb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10950)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a3014b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018c6d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a3b3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db87)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6f4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81114814)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8111c690)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811fa043)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff8122a4b3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff8126b8b0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81270ce0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297dce)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129dc54)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a5ef3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81323e0a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8136cfa3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a4bcd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813b86af)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d0b95)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff814219be)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff816329c0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817aaaf5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8180df19)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff8186ee10)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c4a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff818b8d16)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2d2e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818f6bc2)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819256ea)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819356fd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391eb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81942094)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bd0ab)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd710)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819ed33b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101985d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101acd3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e507)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6c4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112004f)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81127b20)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81205203)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff812353c3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81277760)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127cc50)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a412e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9ef4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b2cc0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81331a59)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81379fa3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b199d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813c50bf)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dd48e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8142d0de)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81680940)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817f5b65)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff81895ee9)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818dab5a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81905ec0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190acfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff8194ff16)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a10e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8198e252)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819d63ca)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e640d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9efb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2da4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6ad6b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b3d0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a9bcfb)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019a9d)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101af13)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f947)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff811078f4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112c32e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81134194)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff8120ca03)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff812454d3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81287350)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8128c820)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b389e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ba174)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c30fd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81344879)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8138da73)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c64d1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff813da410)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f28ac)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff81444f7e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8169af90)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff8180fda5)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818b1de1)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818f767a)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81926ef0)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192bdfa)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/core/filter.c (ffffffff819718e6)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c63e)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b0af2)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819dffea)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f00cd)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d2b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fd2b4)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7737b)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87c10)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81aa64c3)
Location: arch/x86/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
