# Function: <code>atomic_add</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017c47)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019718)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045c8f)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/mm/gup.c (ffffffff810716f6)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ca1b9)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff810e659d)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/profile.c (ffffffff810ea376)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/bpf/core.c (ffffffff8117248d)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/events/core.c (ffffffff8117db1c)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff81197535)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/vmalloc.c (ffffffff811cd1e2)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In mm/huge_memory.c (ffffffff811f735b)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/aio.c (ffffffff8125b9e5)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8128a0ab)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In fs/ext4/super.c (ffffffff812be4ab)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812c0cab)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff812ce5d9)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In ipc/msg.c (ffffffff813264ed)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/blk-mq-tag.c (ffffffff813c6d0b)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In lib/genalloc.c (ffffffff8140724c)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/tty/tty_buffer.c (ffffffff814ea7b2)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devio.c (ffffffff81619653)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/usb/core/devices.c (ffffffff8161ec09)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff81693090)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff81700a4b)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817061c0)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff8170d626)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81732b96)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff8174a3e7)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_output.c (ffffffff8175d6a9)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_input.c (ffffffff8176bdc7)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81775f06)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782b0d)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81783612)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff817c048f)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff817c5d56)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0bd9)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/packet/af_packet.c (ffffffff81806fd7)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017922)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018d71)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045876)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/mm/gup.c (ffffffff81071b3f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ceb79)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff810ead19)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In kernel/profile.c (ffffffff810f10b2)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/bpf/core.c (ffffffff81180298)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/events/core.c (ffffffff8118ffbc)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811ab450)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/shmem.c (ffffffff811c055f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/huge_memory.c (ffffffff81217da6)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8121f380)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/aio.c (ffffffff812842d5)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff812b74d3)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
```
```
In fs/ext4/super.c (ffffffff812edb8c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812f0588)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81303d76)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/msg.c (ffffffff8135b129)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/blk-mq-tag.c (ffffffff8140af10)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In lib/genalloc.c (ffffffff8144efff)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/tty/tty_buffer.c (ffffffff8153b72c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devio.c (ffffffff81679813)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/usb/core/devices.c (ffffffff8167f479)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff816f3b4a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff81767409)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176e7be)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff81774c76)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff8179e4b6)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow.c (ffffffff817a0654)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b7307)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_output.c (ffffffff817caf69)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_input.c (ffffffff817da633)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_output.c (ffffffff817e2e96)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebd1c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc9a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0be0)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8182d035)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81832e66)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8186087e)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81878ef2)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017b32)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018f41)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810474bd)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/mm/gup.c (ffffffff810756b9)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In kernel/rcu/tree.c (ffffffff810f20e9)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In kernel/profile.c (ffffffff810f81a4)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/bpf/core.c (ffffffff8118c108)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/events/core.c (ffffffff8119ff2c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811bba27)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811d0b3f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/huge_memory.c (ffffffff8122a367)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812319f0)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (ffffffff81297f95)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff812ccce1)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
```
```
In fs/ext4/super.c (ffffffff81303b29)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff81306558)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81319d36)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/msg.c (ffffffff81371718)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In lib/genalloc.c (ffffffff8146d9bf)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In lib/sbitmap.c (ffffffff814824a8)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/tty/tty_buffer.c (ffffffff81567db6)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devio.c (ffffffff816a74f3)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/usb/core/devices.c (ffffffff816ad1b9)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff817251d3)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff81794429)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8179bc7e)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff817a1f76)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff817ccf16)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow.c (ffffffff817cf254)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e6da7)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_output.c (ffffffff817fabaf)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_input.c (ffffffff81808fc5)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_output.c (ffffffff81813546)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ca96)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818206aa)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8182197a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8185eb15)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff818648f7)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892c99)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818ad60f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015bf9)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810173cc)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104704a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In kernel/rcu/tree.c (ffffffff810f2980)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_percpu_data
```
```
In kernel/profile.c (ffffffff810fa1c5)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/bpf/core.c (ffffffff8118ffc3)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In kernel/events/core.c (ffffffff811a7b47)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811c3cdb)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811d90cf)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8120bab4)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81235f5a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8124264f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (ffffffff812a6985)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff812da314)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81311025)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff81320f04)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81338256)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff81384939)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In lib/genalloc.c (ffffffff8147309f)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b3dc)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff816c2389)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8173d151)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817836d9)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff817b2819)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b92f0)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff817c0018)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/core/filter.c (ffffffff817ec324)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow.c (ffffffff817ee5e4)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180675c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_fragment.c (ffffffff8181606a)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181b010)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_input.c (ffffffff81829288)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_output.c (ffffffff81833731)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d077)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840bba)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8184261e)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81862aef)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/unix/af_unix.c (ffffffff8188283c)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81888109)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff818b4daa)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b9274)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818d2bb6)
Location: arch/x86/include/asm/atomic.h:48
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015fa9)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81017bac)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104aaf6)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810de2d6)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff810fc72e)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_percpu_data
```
```
In kernel/profile.c (ffffffff81104b49)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811bb2b7)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811d8a7b)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811ee3af)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812250a5)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81254cb5)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8126248f)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (ffffffff812c9825)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff812feb74)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81332d79)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (ffffffff8134563a)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8135c736)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff813a8c4c)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff815dfdec)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff8172e159)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff817aed0f)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817f9a99)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff8182aa29)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c03)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81868104)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff8188542c)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_fragment.c (ffffffff818952fa)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff818ae2c5)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc823)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c032d)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2c1f)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81937b1a)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c1c3)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8195908b)
Location: arch/x86/include/asm/atomic.h:49
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016fb0)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101853a)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d460)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810e69b6)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81105e68)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_percpu_data
```
```
In kernel/profile.c (ffffffff8110f8c2)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811db1d3)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff811f9c0f)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff8120ecef)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81247662)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8126e819)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278c4f)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81286562)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (ffffffff812f2985)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8132c633)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81363fe6)
Location: include/asm-generic/atomic-instrumented.h:124
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
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138b160)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff813d8342)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81619071)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff8176cf65)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff81800668)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818430d9)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81878245)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c0b3)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff818b8276)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff818d8c52)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81903981)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912328)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e84)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995340)
Location: include/asm-generic/atomic-instrumented.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819b2df0)
Location: include/asm-generic/atomic-instrumented.h:124
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
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018d0a)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ab28)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810f1fb4)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811139f4)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8111afb2)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811eb513)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/page_alloc.c (ffffffff8120c2aa)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff81221581)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbc3)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812824b9)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128d315)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8128fd87)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81307605)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81343ab3)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137c288)
Location: include/asm-generic/atomic-instrumented.h:141
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
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a33d4)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff813f2fba)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff816361e1)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817915b5)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8182c745)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8186f0de)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81898725)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c913)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
```
```
In net/core/filter.c (ffffffff818decd6)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/netlink/af_netlink.c (ffffffff81905442)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81931b3e)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940b05)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194462b)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194d236)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb529)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbc26)
Location: include/asm-generic/atomic-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819e9d4e)
Location: include/asm-generic/atomic-instrumented.h:141
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a393)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbb4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810fa414)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8111d5e4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81125690)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81201f63)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff81230dac)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81272510)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81276d80)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e490)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2671)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812aaf4a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81328bf9)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8136bd23)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a2cfd)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ce077)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8141eb0e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a410)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817cfe65)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8186ec5c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818b33da)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff818e2ce0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e7918)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff8192cc16)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8195324b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8196685e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff8199523a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a50cd)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c1b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b19f1)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a124)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a71f)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a5832c)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad13)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e557)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff811061f4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81129b7f)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81131650)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff8120ee13)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff8123efd3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81281370)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81286860)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812add3e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b3b04)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bc8d0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8133b9a9)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81383ef3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813bbb5d)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e7b35)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8143895e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8168cb00)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff81800ce5)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818a0a39)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818e5cfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81914ec0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919cfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff8195ef16)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8198910e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8199d252)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd8a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbdcd)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df8bb)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8764)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60c5b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a712c0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a90abb)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e72f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051eba)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff81111224)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81138036)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff811407fe)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/events/core.c (ffffffff8124019b)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8126c848)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81287922)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b3847)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812b8e01)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e4871)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e941d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f1dfc)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8137564a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff813ce859)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81404030)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff81419310)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81430be3)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff81488bb1)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8173eb08)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/usb/core/devices.c (ffffffff818d13c5)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8197073c)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819b8faa)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819e7fe0)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb6e9)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a32236)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff81a620dd)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a76492)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81aba4e2)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd5d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad66f4)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b226b1)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b269ec)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b59b37)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f53)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8bcf0)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab705)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101edcf)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fda)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8110e3a4)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81133876)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8113cb55)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff8118496f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In kernel/events/core.c (ffffffff8124a6eb)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8127728f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81291762)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bf321)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812c4573)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef264)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f48cb)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fe37d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130441b)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff81383524)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff813bb95d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/kernfs/dir.c (ffffffff813e0489)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81417280)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
```
```
In fs/ext4/resize.c (ffffffff8142d3c9)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814499a6)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff814a61f8)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8175aa38)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81c26851)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819bb41a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819e7ab0)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb409)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a34576)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81a3f626)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6925f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81a7f202)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5922)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d5d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae2cd1)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b310b1)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b35567)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b6819a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a33)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b9b162)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbb95f)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102024e)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d0a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee34)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81134449)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8113df53)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811857a5)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In kernel/events/core.c (ffffffff8124e833)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff8127c2f7)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812975bd)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c43c5)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff812cb1f8)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5ed4)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fae4f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81305037)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130b4e0)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff8138c297)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff813c2a53)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/kernfs/dir.c (ffffffff813e6f0d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141de96)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144f326)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff814ac186)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff81716252)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173e8d8)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81c18cce)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8199fc2c)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff819cda80)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1919)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81a1b5e6)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81a4e6f7)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81a681e2)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b32)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3dcc)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acdc20)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1ede1)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b2315c)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b564d5)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d3d)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8ab5a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab56f)
Location: include/asm-generic/atomic-instrumented.h:61
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
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810226f8)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b20a)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In kernel/locking/qrwlock.c (ffffffff8112e6d4)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811611c5)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811adb86)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In kernel/events/core.c (ffffffff8128c6a3)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/shmem.c (ffffffff812ba4a8)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812d7f71)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In mm/page_alloc.c (ffffffff81308281)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813101f3)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813404b4)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81344c86)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134edc7)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135658b)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff813d9857)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff81412a7c)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff81438ab8)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8147064a)
Location: include/linux/atomic/atomic-instrumented.h:53
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
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2ea7)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff81504669)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff81793505)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf058)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81d2833e)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81a4c8ed)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81a7d290)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a814e9)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81acecc6)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81b07433)
Location: include/linux/atomic/atomic-instrumented.h:53
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
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81b21702)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d974)
Location: include/linux/atomic/atomic-instrumented.h:53
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
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b8245c)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8c5ee)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7301)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3dcb)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be8f2e)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81c1cb43)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e8fa)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81c56c75)
Location: include/linux/atomic/atomic-instrumented.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c77e98)
Location: include/linux/atomic/atomic-instrumented.h:53
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810261c1)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/qrwlock.c (ffffffff8114f900)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff81193faa)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/audit.c (ffffffff811dfaf3)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/events/core.c (ffffffff812e12b9)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff812f239f)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317a5a)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81338482)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8137ac88)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff813af44b)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff813b1f7b)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813baba1)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c599e)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813cf44f)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff814609b5)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8148961c)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff814b3b4b)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814f1aea)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152a32b)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In ipc/msg.c (ffffffff815962ef)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/xen/events/events_base.c (ffffffff818cc009)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb5ae)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81ef4399)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81b72c97)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81bbb08c)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81bec267)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf51b9)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/filter.c (ffffffff81c4c362)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81c8bd7c)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81ca9cc2)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcde2)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1295c)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1cc46)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7aba7)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81d815ba)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81db93fe)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb548)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81df605e)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1cf1d)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102baa1)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/qrwlock.c (ffffffff820d6c53)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811d1f7b)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff81225803)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/events/core.c (ffffffff81349819)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff8135a9af)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138aeec)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813afc8a)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813f87bc)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff8142f9db)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff81431aad)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143d048)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8144a3de)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8145471f)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff814f08f7)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8151cfd3)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff8154bd4e)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff8158c364)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8ccb)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In lib/sbitmap.c (ffffffff818a2d29)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d489)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54848)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81cf9fa8)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d0fa70)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81d6071c)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81d98ca7)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da36d9)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81e010e2)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81e482c9)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81e66cc2)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81ec19a2)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed879c)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee3d26)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f47b77)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81f4dedf)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81f8944e)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c634)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81fca5c8)
Location: include/linux/atomic/atomic-instrumented.h:54
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff444d)
Location: include/linux/atomic/atomic-instrumented.h:54
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102bacf)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/qrwlock.c (ffffffff82159fe3)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811e5fbb)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff8123bdf3)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81279a59)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff8137ac16)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff8138c3de)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd51a)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e7e2d)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8142b57e)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81465578)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff814676cf)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81472525)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8148036d)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148a50f)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/aio.c (ffffffff81527697)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff81555182)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/kernfs/dir.c (ffffffff81583a0e)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff815c2345)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600a8c)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In lib/sbitmap.c (ffffffff818e51fd)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81a6668c)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ee28)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/md/md.c (ffffffff81d696e2)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d78ec2)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb7c1)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81e07049)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122cd)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81e72ba2)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81ea3a8d)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a82)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ffb0)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378ac)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f43597)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa7677)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81fade0a)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81fe887f)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd084)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b3fc)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82070c75)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81031c2f)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In kernel/locking/qrwlock.c (ffffffff8223d863)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/profile.c (ffffffff811fbd0b)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/audit.c (ffffffff81255cc3)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ring_buffer.c (ffffffff81294539)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In kernel/events/core.c (ffffffff813a3e16)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
```
In mm/filemap.c (ffffffff813b9747)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e866e)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81412a9a)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/page_alloc.c (ffffffff8144f1f9)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff81464d68)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/kfence/core.c (ffffffff81494817)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8149895d)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a28b7)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ae45d)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b9dbf)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
```
```
In fs/aio.c (ffffffff8155c4d7)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/iomap/buffered-io.c (ffffffff8158b454)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In fs/kernfs/dir.c (ffffffff815bc4ee)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_show
```
```
In fs/ext4/mballoc.c (ffffffff81600148)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816397dc)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In block/blk-mq.c (ffffffff817c4cff)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In lib/sbitmap.c (ffffffff8192c1fd)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/xen/events/events_base.c (ffffffff81ab91bf)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81af18e8)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
```
```
In drivers/md/md.c (ffffffff81e20278)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81e30041)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84301)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81ec38b0)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf48d)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/filter.c (ffffffff81f32315)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/skmsg.c (ffffffff81f6638d)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/netlink/af_netlink.c (ffffffff81f85dd2)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4690)
Location: include/linux/atomic/atomic-instrumented.h:102
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
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd97c)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820094f7)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82074927)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff8207a6da)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/udp.c (ffffffff820b73cf)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc199)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faee7)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82144e85)
Location: include/linux/atomic/atomic-instrumented.h:102
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da7a40)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/smp.c (ffff80001009c238)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6dbc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In virt/kvm/kvm_main.c (ffff8000100b9f94)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_enable_nolock
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_fault
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100cafa8)
Location: include/asm-generic/atomic-instrumented.h:60
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
In kernel/fork.c (ffff8000100f434c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa27c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/exit.c (ffff8000100fd4c0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010107e38)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/umh.c (ffff80001011ac94)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cd54)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/nsproxy.c (ffff80001012b448)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (ffff80001012d080)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/kmod.c (ffff800010130674)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (ffff80001013114c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff800011444e68)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffff80001014c3f0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001014e9e8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffff800010152ca8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/sched/cpupri.c (ffff800010159f20)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffff80001015bf40)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010163144)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/locking/qrwlock.c (ffff80001016c8d8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff8000101700a8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffff800010176ccc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (ffff80001017868c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179c74)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188fc8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (ffff80001018a5e0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffff80001019171c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffff800010198dac)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/futex.c (ffff8000101ba088)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
```
In kernel/module.c (ffff8000101c4dcc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffff80001144add8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da3c8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de324)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/utsname.c (ffff8000101e5328)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e65cc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffff8000101e787c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffff8000101e94dc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/debug/debug_core.c (ffff8000101f9848)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/relay.c (ffff80001020b850)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/ring_buffer.c (ffff8000102184bc)
Location: include/asm-generic/atomic-instrumented.h:60
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
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (ffff80001022160c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/blktrace.c (ffff800010235cfc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In kernel/trace/fgraph.c (ffff80001023820c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_kdb.c (ffff800010254ff4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff800010260130)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/cpumap.c (ffff80001028888c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/offload.c (ffff800010289ff0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffff800010297924)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
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
  - kernel/events/core.c:perf_event_refresh
```
```
In kernel/events/uprobes.c (ffff8000102a8428)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a9f78)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/jump_label.c (ffff8000102ab598)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In mm/filemap.c (ffff8000102b0dd4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b77e4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd1f4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c3408)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102ca118)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d60f4)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mmu_context.c (ffff8000102dff78)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f2120)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa178)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffff8000102ffda4)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffff800010304f14)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030abf8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/page_alloc.c (ffff800010319034)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (ffff80001031ecfc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff800010320a98)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffff8000103219b4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327e80)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032c360)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffff800010335e84)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033d020)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffff800010341b5c)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff8000103530c0)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff800010365f24)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff800010372648)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (ffff800010375c50)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memfd.c (ffff80001037c5dc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dda4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffff800010385858)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffff800010386d40)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffff80001038c798)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
  - fs/exec.c:kernel_read_file
```
```
In fs/pipe.c (ffff80001038fd44)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dcache.c (ffff8000103a8760)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffff8000103aea0c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
```
```
In fs/file.c (ffff8000103b1d48)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffff8000103bad90)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:mnt_init
```
```
In fs/fs-writeback.c (ffff8000103c8008)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffff8000103d5a70)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffff8000103e4d28)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (ffff8000103ea4fc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103edee4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
```
In fs/userfaultfd.c (ffff8000103f6d9c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffff8000103faa74)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffff800010403020)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_script.c (ffff80001041d984)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (ffff80001041f9dc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010423158)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/mbcache.c (ffff800010425828)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffff80001042bf6c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042d27c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/quota/dquot.c (ffff80001043237c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffff800010439984)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/proc/root.c (ffff80001043c974)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043ed5c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/proc_sysctl.c (ffff80001044b9d4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (ffff800010453d24)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_get
```
```
In fs/kernfs/file.c (ffff8000104552b8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/mount.c (ffff800010457a94)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/dir.c (ffff80001045bd50)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffff80001045d074)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffff80001045ea34)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffff800010460e08)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475b28)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff800010479608)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff8000104804e0)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
```
```
In fs/ext4/mmp.c (ffff800010499034)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffff8000104a4188)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffff8000104a806c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c04f4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffff8000104c4e44)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffff8000104cca14)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffff8000104cf060)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d15b8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d8c60)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffff8000104e4cc8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffff8000104e8d64)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fd9f8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffff800010501c78)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffff80001050c098)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In fs/fuse/inode.c (ffff80001051244c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffff80001051d5b0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffff80001051f5b4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffff80001052c248)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd10)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffff80001052e5ac)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (ffff800010533008)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (ffff8000105351dc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff80001053570c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff80001053667c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (ffff80001054e3e0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffff8000105569c4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffff80001056721c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/xfrm.c (ffff80001056bb74)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffff80001057d460)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffff80001057e6d8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff80001058055c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffff80001058423c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffff800010586720)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001146b144)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/domain.c (ffff800010594cd0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy_unpack.c (ffff800010598ab4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In block/bio.c (ffff8000105dd138)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (ffff8000105e0c04)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-map.c (ffff8000105e9834)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-mq.c (ffff8000105f0824)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4280)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-iocost.c (ffff8000106153f8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/iov_iter.c (ffff80001062dea8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/rhashtable.c (ffff800010636de8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/sbitmap.c (ffff80001066a164)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c08)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e7490)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff8000107010e4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708d10)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bd40)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/ats.c (ffff800010716668)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e94)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c27c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af44c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
```
In drivers/amba/bus.c (ffff8000107b943c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (ffff8000107bf7c4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (ffff8000107fd310)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d474)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b00c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/tty/tty_buffer.c (ffff80001085d24c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (ffff80001086a538)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a85f0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8f94)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
```
```
In drivers/char/virtio_console.c (ffff8000108b2ab4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d62ec)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd35c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (ffff8000108de184)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/base/core.c (ffff8000108e7384)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (ffff8000108ea818)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (ffff8000108f6e24)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffff8000108fd2cc)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (ffff800010905140)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
```
```
In drivers/base/power/domain.c (ffff8000109086ec)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
```
```
In drivers/block/loop.c (ffff800010922744)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e3e8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff800010940928)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952e10)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ca70)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c904)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (ffff80001096f9d0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffff800010976fcc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
```
In drivers/scsi/sg.c (ffff80001098f0d0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffff8000109dba5c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9b84)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a0041c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a08ea0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In drivers/usb/core/hub.c (ffff800010a19adc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffff800010a1e3b0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffff800010a20aa8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (ffff800010a259d8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/devio.c (ffff800010a2e9b0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/devices.c (ffff800010a34cf8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (ffff800010a35fc8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37344)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f0c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba0ec)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010ababc8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac3fe4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_update
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc8bc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffff8000114bae50)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffff800010af8308)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:dm_issue_global_event
```
```
In drivers/md/dm-stripe.c (ffff800010b066e0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffff800010b0a298)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0ae68)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffff800010b0dc18)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14048)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a748)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b338)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b1f8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b8128c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/perf/arm-cci.c (ffff800010b91d78)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/ras/debugfs.c (ffff800010b9e520)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In net/core/sock.c (ffff800010badc74)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/net_namespace.c (ffff800010bc1fd8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bcb48c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/neighbour.c (ffff800010be5fa8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffff800010bfdb14)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow_offload.c (ffff800010c0873c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffff800010c0eca8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/bpf_sk_storage.c (ffff800010c31a54)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_generic.c (ffff800010c3801c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c4360c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c47628)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4dba4)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b9c8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cfdc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffff800010c751a4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c7a518)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f084)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93f88)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
```
```
In net/ipv4/raw.c (ffff800010c98874)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f588)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6698)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf628)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ping.c (ffff800010cc0dc8)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccdffc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e50)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde0ac)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/unix/af_unix.c (ffff800010cf409c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf84b0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffff800010d0110c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffff800010d1546c)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d2abcc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d3968c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d400cc)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffff800010d45a60)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48c80)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52560)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffff800010d5b494)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a65c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ad3c)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
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
In arch/arm/kernel/smp.c (c0312ac4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
```
In kernel/fork.c (c03521c8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (c03583c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/exit.c (c035a634)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c0361e84)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/sys.c (c036af64)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/umh.c (c036f228)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c0370850)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/kthread.c (c037ad40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/nsproxy.c (c037ba08)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (c037d54c)
Location: arch/arm/include/asm/atomic.h:225
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
In kernel/async.c (c037e600)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/kmod.c (c037ff58)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (c0380470)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c151ef50)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/loadavg.c (c038eb70)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/clock.c (c151f124)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/fair.c (c0393b1c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/sched/rt.c (c039c784)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (c039f7a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/sched/cpupri.c (c03a6d28)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (c03a8888)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/rwsem.c (c03b5e7c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/process.c (c03bacd8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
```
```
In kernel/power/hibernate.c (c03bcfc8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/swap.c (c03c0c98)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/power/user.c (c03c34c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
```
In kernel/printk/printk_safe.c (c03c8860)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (c03c9e14)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/irq/manage.c (c03cb18c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c03d6f1c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (c03d8c78)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (c03df358)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/kcmp.c (c03e2e1c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/profile.c (c03e386c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/futex.c (c0403cfc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
```
In kernel/module.c (c040c0e4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (c041bb70)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/namespace.c (c041cc38)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/legacy_freezer.c (c041fcf4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/cgroup/cpuset.c (c04232ac)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/utsname.c (c0425bd4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c0426080)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (c0427c78)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (c042943c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/audit_tree.c (c043578c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/debug/debug_core.c (c0439b0c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/relay.c (c0449cbc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/tracepoint.c (c044d648)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/trace/ring_buffer.c (c045ab74)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
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
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
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
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
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
  - kernel/trace/ring_buffer.c:rb_check_list
  - kernel/trace/ring_buffer.c:rb_check_list
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (c04606f4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/blktrace.c (c0471a54)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In kernel/trace/fgraph.c (c0473b54)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_kdb.c (c0488260)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (c04939bc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/cpumap.c (c04b7e40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/offload.c (c04b9f5c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (c04becd0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c04c6db8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:_perf_event_refresh
```
```
In kernel/events/ring_buffer.c (c04d2400)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (c04d7364)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d7c20)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/filemap.c (c04dfb68)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (c04e441c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (c04e975c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c04ee128)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In mm/vmscan.c (c04f67b0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c04fe3e0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c0502610)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (c0504680)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/mmu_context.c (c05048a8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (c050b9c4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (c0513b8c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (c0513c30)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/gup.c (c0514a7c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c051b4a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/mlock.c (c051d378)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c051e1dc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (c0522fcc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (c05231fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/msync.c (c0524b90)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (c0526878)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:anon_vma_fork
```
```
In mm/vmalloc.c (c052c548)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In mm/page_alloc.c (c05345a4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (c1532db4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (c053827c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c053947c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c053a124)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c053f154)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/frontswap.c (c054114c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (c05426a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mmu_notifier.c (c0543434)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (c0547a34)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c054f680)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c0551b54)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_counter.c (c055315c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c055cc38)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zpool.c (c055f170)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (c0561f28)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (c0563b04)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memfd.c (c0566f34)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c056768c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (c056e650)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (c056f540)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (c057425c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
  - fs/exec.c:kernel_read_file
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (c05766c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/select.c (c0584b6c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/dcache.c (c05894a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (c058e88c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
```
```
In fs/file.c (c0591cc0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (c0598b40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:mnt_init
```
```
In fs/fs-writeback.c (c05a69d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (c05af434)
Location: arch/arm/include/asm/atomic.h:225
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
In fs/buffer.c (c05b527c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/block_dev.c (c05b80d4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (c05bcc08)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/proc_namespace.c (c05bf578)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (c05c1968)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fanotify/fanotify_user.c (c05c572c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (c05c751c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (c05cdcd0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (c05d1568)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:put_reqs_available
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (c05d7b30)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_timeout_fn
```
```
In fs/verity/enable.c (c05de164)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_script.c (c05e5fc8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (c05e7c80)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_elf_fdpic.c (c05ebe08)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
```
```
In fs/binfmt_flat.c (c05ed4fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_shared_library
```
```
In fs/mbcache.c (c05ee35c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (c05f385c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c05f6344)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/quota/dquot.c (c05fa2c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/root.c (c06029a8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c06056b8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/fd.c (c060bfb4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_sysctl.c (c0610624)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (c0616810)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_get
```
```
In fs/kernfs/file.c (c0616ce8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/mount.c (c0619824)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/dir.c (c061d020)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (c061de7c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (c061f4d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (c0621648)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c06373e4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c063abac)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0645804)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/mballoc.c (c0650110)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/ext4/mmp.c (c065a984)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (c0665ee8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (c066a278)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0683c30)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (c0688eec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (c06902dc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (c06920bc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c0693f40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c069ab48)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (c06a40a4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (c06a62d8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (c06baff8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (c06be638)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (c06c79d8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In fs/fuse/inode.c (c06cc13c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (c06d99b0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (c06dbb90)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/shm.c (c06e1bdc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4404)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5614)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (c06e6a04)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (c06ea8ec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (c06ec8cc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed184)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06edb58)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (c06fe008)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (c070b150)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (c071b790)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/xfrm.c (c071f51c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (c072f3e4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_update_stat
```
```
In security/tomoyo/condition.c (c0730bd0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c0732a48)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (c0735ce8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (c0738118)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c1543df8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/domain.c (c0745c2c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy_unpack.c (c0749cd8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In security/integrity/ima/ima_queue.c (c075d3e4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (c075feec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (c078a5d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (c0791634)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-ioc.c (c0795174)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In block/blk-map.c (c0795b28)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-mq.c (c079c950)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c079ff5c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (c07a2950)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (c07a5c88)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (c07b8758)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07ba864)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (c07be6a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/iov_iter.c (c07d4f10)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/percpu-refcount.c (c07db520)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/rhashtable.c (c07dcbc0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/crc-t10dif.c (c1548fdc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_init
```
```
In lib/genalloc.c (c07eac40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In lib/sbitmap.c (c0811dc0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef18)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fac0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0851c70)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_enable
```
```
In drivers/pci/pci.c (c08825cc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898ce8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/ats.c (c08a0790)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8004)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce8d8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/amba/bus.c (c08e5744)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (c08e8188)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (c091e9a0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (c092811c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/virtio/virtio_balloon.c (c0947508)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/tty/tty_io.c (c095d4c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/tty/tty_buffer.c (c0965054)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (c096f354)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a4df8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/tty/serial/kgdboc.c (c09a5530)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
```
```
In drivers/char/virtio_console.c (c09af154)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/exynos-iommu.c (c09ca0e8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
```
```
In drivers/connector/cn_queue.c (c09cc710)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (c09cd120)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In drivers/base/core.c (c09d5990)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (c09d88ec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (c09e28a4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (c09e8198)
Location: arch/arm/include/asm/atomic.h:225
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
In drivers/base/power/main.c (c09ed0b0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (c09edd20)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_wakeup
```
```
In drivers/base/power/domain.c (c09f0004)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
```
```
In drivers/block/loop.c (c0a07d58)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/mfd/twl6030-irq.c (c0a26810)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (c0a296cc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
```
```
In drivers/dma-buf/dma-buf.c (c0a3bbfc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/dma-buf/udmabuf.c (c0a41e74)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (c0a44c40)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (c0a498d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sg.c (c0a60a0c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (c0ac5764)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acae5c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ppp/ppp_generic.c (c0add7cc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (c0af1d90)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (c0af5c4c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (c0af7094)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (c0afb7b4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/devio.c (c0b046a4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/devices.c (c0b084fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (c0b094dc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (c0b09a2c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (c0b63378)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-base.c (c0b92ae4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b997fc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99f10)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (c0babf38)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (c15c1158)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_new_event
```
```
In drivers/md/md-bitmap.c (c0bdb79c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c0bdf9dc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:dm_issue_global_event
```
```
In drivers/md/dm-stripe.c (c0be4990)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (c0be8748)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (c0be8e00)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (c0bebe24)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1ea8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpuidle/coupled.c (c0c05418)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
```
```
In drivers/mmc/core/sdio.c (c0c15144)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (c0c15b68)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/host/sdhci.c (c0c25cf0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344b4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/remoteproc/remoteproc_core.c (c0c6482c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/perf/arm-cci.c (c0c7b668)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/ras/debugfs.c (c0c80570)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In sound/core/pcm_native.c (c0c93230)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data
  - sound/core/pcm_native.c:snd_pcm_mmap_data_fault
  - sound/core/pcm_native.c:snd_pcm_mmap_data_open
```
```
In net/core/sock.c (c0ccae94)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/skbuff.c (c0cd4984)
Location: arch/arm/include/asm/atomic.h:225
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
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (c0cd7dd8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/scm.c (c0cda31c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/net_namespace.c (c0cdd4e8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/sysctl_net_core.c (c0ce11b4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0ced05c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
```
```
In net/core/neighbour.c (c0cfec24)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (c0d19dc0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__sk_filter_charge
```
```
In net/core/flow_offload.c (c0d2192c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/net-sysfs.c (c0d23824)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/skmsg.c (c0d27228)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/gro_cells.c (c0d47a5c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/bpf_sk_storage.c (c0d47d74)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:omem_charge
```
```
In net/sched/sch_generic.c (c0d4aa54)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In net/sched/cls_api.c (c0d51448)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (c0d578f0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (c0d5cc4c)
Location: arch/arm/include/asm/atomic.h:225
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
In net/ipv4/route.c (c0d66770)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_fragment.c (c0d6e8f8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (c0d73500)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/inet_timewait_sock.c (c0d7aa60)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7b5d4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (c0d7e878)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c0d87f24)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:clean_acked_data_enable
```
```
In net/ipv4/tcp_ipv4.c (c0d9dfc0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (c0da27d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
```
```
In net/ipv4/raw.c (c0da66e8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In net/ipv4/udp.c (c0daa118)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/icmp.c (c0db18d0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/fib_frontend.c (c0dc130c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (c0dc221c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In net/ipv4/inet_fragment.c (c0dca72c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ping.c (c0dcbd10)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ip_tunnel_core.c (c0dce0bc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
```
In net/ipv4/ipmr.c (c0dd9134)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (c0dddd3c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/xfrm_policy.c (c0de8258)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/xfrm/xfrm_device.c (c0df64ec)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c0dfb390)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
```
```
In net/unix/garbage.c (c0dfb4f4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (c0e03be4)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (c0e08c54)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (c0e1b11c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ndisc.c (c0e25238)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e2b024)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2eb60)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30a10)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e33954)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c0e37684)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3c218)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (c0e3ca78)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6_flowlabel.c (c0e42ba0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (c0e486c0)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/xfrm6_policy.c (c0e49f10)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/seg6_hmac.c (c0e533a8)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (c0e58684)
Location: arch/arm/include/asm/atomic.h:225
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
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66dcc)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68c28)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e6928c)
Location: arch/arm/include/asm/atomic.h:225
Inline: True
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
In kernel/rcu/tree.c (c0000000001ecca4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (c0000000001f8c50)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (c0000000003460b0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (c00000000038f0ac)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (c0000000003eba68)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (c0000000003f64c8)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c000000000433160)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043bad0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c000000000449138)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000045aec4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/aio.c (c000000000502d78)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/io_uring.c (c000000000510b5c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/kernfs/dir.c (c00000000056b824)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005baad0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/resize.c (c0000000005d5a20)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005f6d7c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (c000000000668fb4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (c0000000008fc424)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (c000000000af26cc)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (c000000000bd3884)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c000000000c40458)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (c000000000c829b0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86730)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (c000000000c95308)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (c000000000ceb5f4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (c000000000d2aaac)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/netlink/af_netlink.c (c000000000d48b38)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/ip_output.c (c000000000d693f0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_input.c (c000000000d88d9c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_output.c (c000000000d8f6c4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9dd50)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (c000000000da369c)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da6670)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000daf5b4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In net/ipv4/udp_offload.c (c000000000db36b4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (c000000000e167c8)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (c000000000e20eac)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In net/ipv6/udp.c (c000000000e565e4)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cdcc)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c000000000e94de0)
Location: arch/powerpc/include/asm/atomic.h:99
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In arch/riscv/kernel/smpboot.c (ffffffe0000035ae)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:smp_callin
```
```
In kernel/fork.c (ffffffe0000c14c4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffe0000047c6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/exit.c (ffffffe0000c56ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffe0000cba08)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_link
```
```
In kernel/user.c (ffffffe0000ccf26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
```
In kernel/signal.c (ffffffe0000cd520)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffe0000d44ac)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/umh.c (ffffffe0000d51dc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffe0000d73de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/pid.c (ffffffe0000dcd1a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffe0000df370)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffe0000e02bc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (ffffffe0000e17f8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
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
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/async.c (ffffffe0000e275e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/smpboot.c (ffffffe0000e2f80)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In kernel/kmod.c (ffffffe0000e3b86)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (ffffffe0000e407e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/groups.c:set_current_groups
```
```
In kernel/sched/core.c (ffffffe000006d76)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/clock.c (ffffffe000006e36)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/fair.c (ffffffe0000f5978)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffe0000f77fa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb742)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/cpupri.c (ffffffe0000ff9e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffffffe000100faa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/autogroup.c (ffffffe00010384c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffe000109818)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffe00010a9c0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffe00010c276)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/process.c (ffffffe00010d9f6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffffffe000111be8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (ffffffe0001130cc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In kernel/irq/manage.c (ffffffe0001151ca)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffe00011e006)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (ffffffe00011f2fc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffe000124a3c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_barrier_func
```
```
In kernel/kcmp.c (ffffffe000128a1a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/profile.c (ffffffe00012977a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/posix-timers.c (ffffffe0001362ba)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372b2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffe00013fb80)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffe000145616)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffe0001516c6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffe00015294a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000152fec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155578)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/cgroup/cpuset.c (ffffffe00015990a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
```
```
In kernel/utsname.c (ffffffe00015aeee)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015b38e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffe00015c72c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffe00015f940)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffe000162314)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffe000166d9e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffe000169112)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffe0001696ae)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (ffffffe00016bcf2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffe00016c8fa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/tracepoint.c (ffffffe00016f80e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/trace/ring_buffer.c (ffffffe000177fdc)
Location: arch/riscv/include/asm/atomic.h:76
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
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (ffffffe00017ab36)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000189110)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/blktrace.c (ffffffe00018c6bc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_subbuf_start_callback
```
```
In kernel/trace/fgraph.c (ffffffe00018f1ce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/bpf/syscall.c (ffffffe0001a0526)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/bpf/btf.c (ffffffe0001baea6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/cpumap.c (ffffffe0001bca1c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/offload.c (ffffffe0001bdfc0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/bpf/cgroup.c (ffffffe0001c250e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffe0001d07ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
  - kernel/events/core.c:perf_event_refresh
```
```
In kernel/padata.c (ffffffe0001d3404)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/filemap.c (ffffffe0001d66d8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffe0001dbab8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001dffc8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffe0001e42b8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e9284)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffe0001f19ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffe0001f5976)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_init
```
```
In mm/mmu_context.c (ffffffe0001f7782)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffe00020489a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In mm/memory.c (ffffffe0002084a0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffe00020cfcc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffe00020d37e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffe000210f68)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffe0002110d2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000214908)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/page_alloc.c (ffffffe00021ee64)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In mm/page_io.c (ffffffe00022209a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffe000222bb4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffe000227b94)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/frontswap.c (ffffffe000229400)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (ffffffe00022af92)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffe000231fc8)
Location: arch/riscv/include/asm/atomic.h:76
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
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mmu_notifier.c (ffffffe000232602)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffe000235fb6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f082)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe00024481c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/zpool.c (ffffffe00024b728)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In mm/zsmalloc.c (ffffffe00024e3de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memfd.c (ffffffe00025296e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffe00025385e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffe00025850a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffe000259546)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffe00025d7f0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffe000260262)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/fcntl.c (ffffffe000268606)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/dcache.c (ffffffe00026ddea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffffffe0002737f2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
```
```
In fs/file.c (ffffffe000275f02)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffe00027ac60)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:mnt_init
```
```
In fs/fs-writeback.c (ffffffe000286a40)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffffffe00028f4f8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/buffer.c (ffffffe000294412)
Location: arch/riscv/include/asm/atomic.h:76
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
In fs/block_dev.c (ffffffe000298d66)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffe00029a8e4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/proc_namespace.c (ffffffe00029c868)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffe00029d8d8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffe00029f038)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a1142)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a267c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffe0002a3ec8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffe0002a66b6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/userfaultfd.c (ffffffe0002a8f6a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffe0002a9084)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffffffe0002b133e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_timeout_fn
```
```
In fs/crypto/keysetup.c (ffffffe0002b7ed0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b829e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/verity/enable.c (ffffffe0002b9c6c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_script.c (ffffffe0002c033a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (ffffffe0002c256a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_flat.c (ffffffe0002c3882)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_shared_library
```
```
In fs/mbcache.c (ffffffe0002c3e2a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffe0002c52c4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8216)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffe0002c98f8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/quota/dquot.c (ffffffe0002ce5c6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/root.c (ffffffe0002d4ad0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffe0002d8f5e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/generic.c (ffffffe0002da0e4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In fs/proc/array.c (ffffffe0002dabbe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0d72)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/proc/proc_net.c (ffffffe0002e1d62)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/kernfs/dir.c (ffffffe0002e546a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
```
```
In fs/kernfs/file.c (ffffffe0002e6654)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/mount.c (ffffffe0002e8db4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/dir.c (ffffffe0002ec21c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffffffe0002ed31a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/configfs/item.c (ffffffe0002edde0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/devpts/inode.c (ffffffe0002ee690)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffffffe0002f018a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe000301520)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffe000303eae)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030c72a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/mballoc.c (ffffffe000313f14)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
```
```
In fs/ext4/mmp.c (ffffffe00031cbc2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffe000325642)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffe0003284e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033c3d4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffe00033f6a6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffe000345382)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffe000346bc8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffe00034874e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034e65a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffe000357fe6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffe000359972)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/keystore.c (ffffffe000367e0e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036c0b6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffffffe00036ef18)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffe000378f70)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffe00037c42e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffe0003845ce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffe000386188)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffe00038a306)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffe00038be26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffe00038e6e8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (ffffffe00038eb4e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffe00038fcae)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffe000390fd6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffe000392798)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (ffffffe00039515a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffe0003953ea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffe00039611a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (ffffffe0003a3790)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae124)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffffffe0003bcf92)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/xfrm.c (ffffffe0003c085c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffffffe0003ce958)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffffffe0003cf7a6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffe0003d1246)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffffffe0003d42da)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d60b8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0000261ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d9bf4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffe0003dc4e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffe0003dc9ea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffe0003e262c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffe0003e46e4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5852)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffe0003e6764)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0000268ce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffe0003e9ff8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffe0003eb3d0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebcce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffe0003ed16e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffe0003f061c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffe0003f290c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffe0003f3648)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In crypto/api.c (ffffffe0003fdccc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffe0003feb48)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
```
```
In crypto/algboss.c (ffffffe000409a28)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In crypto/asymmetric_keys/restrict.c (ffffffe000419456)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In block/bio.c (ffffffe00042032a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (ffffffe00042206e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-map.c (ffffffe000429c6c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-mq.c (ffffffe00042f656)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe000432362)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/bsg.c (ffffffe00044372a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/blk-iocost.c (ffffffe00044c972)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
```
```
In lib/iov_iter.c (ffffffe00045dabe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/rhashtable.c (ffffffe0004643e4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/crc-t10dif.c (ffffffe00002a2ee)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_init
```
```
In lib/cpu_rmap.c (ffffffe00048f03e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/sbitmap.c (ffffffe000494476)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_add_wait_queue
```
```
In drivers/pinctrl/core.c (ffffffe000499990)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/pci/pci.c (ffffffe0004bdc26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfd6e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d6246)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8708)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/ats.c (ffffffe0004df52a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4866)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_open
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9c26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/clk/clk.c (ffffffe00050b0f0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (ffffffe000516fb0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fc50)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/reset/core.c (ffffffe00052bc5a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffe00052d756)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_buffer.c (ffffffe0005361ac)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/tty_port.c (ffffffe0005369f0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffe000537790)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffe0008c8db2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffe0005389c4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffe000539276)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c3ea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053e4ea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/char/virtio_console.c (ffffffe000567174)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/hw_random/core.c (ffffffe00056796c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffe000573c72)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffe000574122)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffe0005745b8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe000576bda)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/base/core.c (ffffffe00057baba)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffe00057e62e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (ffffffe000587950)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffffffe00058cb6a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/domain.c (ffffffe00058d810)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
```
```
In drivers/base/firmware_loader/main.c (ffffffe00059219c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffe0005a072a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b1ee0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3b92)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffe0005c0268)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/bus.c (ffffffe0005c2972)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3e34)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cada6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffe0005d1630)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d36d4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d402a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4618)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d48cc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5822)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d687e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d717c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (ffffffe0005d99a6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dd96c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5fe6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffe0005f1128)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffe0005f29dc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffe0005f757c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624a26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffe000628e80)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cada)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/core/hub.c (ffffffe00063e626)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffe00063fa56)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffffffe000643b8a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffe000646800)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/driver.c (ffffffe0006474be)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/file.c (ffffffe00064a9dc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffe00064ec96)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/devices.c (ffffffe0006525fe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (ffffffe0006534fe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000653d0c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a3964)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9440)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be9e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf332)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-notifier.c (ffffffe0006c4146)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8954)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffffffe0000a281a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb078)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffe0006f1372)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-table.c (ffffffe0006f2134)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffe0006f4dc2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffffffe0006f839c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8964)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffffffe0006fae1c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe0007007e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/opp/core.c (ffffffe000702238)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/opp/of.c (ffffffe0007047f6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/mmc/core/sdio.c (ffffffe00071218c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe000712b60)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00071e1e8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/ras/debugfs.c (ffffffe0007369ba)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In drivers/nvmem/core.c (ffffffe00073715a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/socket.c (ffffffe0007388d8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffe00073ce16)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/skbuff.c (ffffffe00074461c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
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
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffe00074aed2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffe00074c668)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffe00074e194)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/sysctl_net_core.c (ffffffe000752378)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe00075c9ea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_inc_ingress_queue
```
```
In net/core/neighbour.c (ffffffe00076b202)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/rtnetlink.c (ffffffe000773ffe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_send
```
```
In net/core/filter.c (ffffffe00077d238)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow_offload.c (ffffffe000786562)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/net-sysfs.c (ffffffe000786960)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/page_pool.c (ffffffe00078a376)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/skmsg.c (ffffffe00078add8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/netpoll.c (ffffffe00078ca6c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/devlink.c (ffffffe0007a3c72)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a724e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_generic.c (ffffffe0007a97ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In net/sched/sch_api.c (ffffffe0007af272)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffe0007b0bb2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffe0007b4c2c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffe0007bb9ac)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0006)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffe0007c0f4e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7a24)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffe0007cc914)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007ce092)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d141e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d5a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffe0007d4a00)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffe0007de182)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:clean_acked_data_enable
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6334)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9bdc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef0da)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f3714)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f486a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffe0007f69fc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f8dc4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd27e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffe0007feff4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffe000803e38)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/igmp.c (ffffffe000808412)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_frontend.c (ffffffe00080d212)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffffffe00080de06)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffe000812c64)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe00081534c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffe00081600c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817d02)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
```
In net/ipv4/nexthop.c (ffffffe00081901e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00082027a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c86)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000826166)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b592)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffe0008305ec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffe000839d66)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffe00083cf70)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/anycast.c (ffffffe000842666)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffe000844294)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffe00084b080)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/ipv6/route.c (ffffffe000043284)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffe00085f6fa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00086092a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffe000862782)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000867c02)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086b236)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffe000871842)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008767c8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087bb26)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffe000880ae0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881f80)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffe0008854d8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe000887024)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889f90)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffe00088ee3a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b9c8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089d2b4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d722)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4d8a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa2c2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffe0008ac100)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad842)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In lib/klist.c (ffffffe0008b35de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffe0008b3bc2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffe0008b565a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101989d)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad13)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e6b7)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810ff504)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112215f)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81129e00)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81207433)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff81237623)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff812799c0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127eeb0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a631e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ac0e4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b4eb0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81333f89)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8137c4d3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b413d)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e0115)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff81430f3e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81652580)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817b90c5)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818468b9)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff818b4ec0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9cfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff818feee6)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff81928f7e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8193d0c2)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff8196bbfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bc3d)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f72b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819885d4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a002eb)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10950)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a3014b)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a3b3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db87)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6f4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81114814)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff8111c690)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff811fa043)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff8122a4b3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff8126b8b0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81270ce0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297dce)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129dc54)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a5ef3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81323e0a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8136cfa3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a4bcd)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d0b95)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff814219be)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff816329c0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817aaaf5)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff8180df19)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In net/core/sock.c (ffffffff8186ee10)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c4a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff818b8d16)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2d2e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818f6bc2)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819256ea)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819356fd)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391eb)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81942094)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bd0ab)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd710)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819ed33b)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101acd3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e507)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6c4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112004f)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81127b20)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff81205203)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff812353c3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81277760)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127cc50)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a412e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9ef4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b2cc0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81331a59)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff81379fa3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b199d)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dd48e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff8142d0de)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff81680940)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff817f5b65)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff81895ee9)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818dab5a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81905ec0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190acfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff8194ff16)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a10e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8198e252)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819d63ca)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e640d)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9efb)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2da4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6ad6b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b3d0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a9bcfb)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101af13)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f947)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/locking/qrwlock.c (ffffffff811078f4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff8112c32e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffffffff81134194)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/events/core.c (ffffffff8120ca03)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_event_refresh
```
```
In mm/shmem.c (ffffffff812454d3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81287350)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8128c820)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b389e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ba174)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c30fd)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81344879)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
```
```
In fs/kernfs/dir.c (ffffffff8138da73)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c64d1)
Location: include/asm-generic/atomic-instrumented.h:60
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
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f28ac)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/msg.c (ffffffff81444f7e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_buffer.c (ffffffff8169af90)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
```
In drivers/usb/core/devices.c (ffffffff8180fda5)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/md/md.c (ffffffff818b1de1)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818f767a)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/sock.c (ffffffff81926ef0)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192bdfa)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/core/filter.c (ffffffff819718e6)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c63e)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:selem_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b0af2)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp_input.c (ffffffff819dffea)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f00cd)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d2b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fd2b4)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7737b)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87c10)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81aa64c3)
Location: include/asm-generic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
