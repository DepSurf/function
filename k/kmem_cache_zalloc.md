# Function: <code>kmem_cache_zalloc</code>

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
In kernel/fork.c (ffffffff8107fcd3)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff8108c894)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810a2616)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff810f13f6)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/user_namespace.c (ffffffff8111ef83)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8111f935)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff8113de95)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8113eeaf)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff811b2d18)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:create_kmalloc_cache
```
```
In mm/mmap.c (ffffffff811c6b75)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__install_special_mapping
```
```
In mm/ksm.c (ffffffff811e5ddf)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_enter
```
```
In mm/slub.c (ffffffff81f8ce7d)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/huge_memory.c (ffffffff811f7846)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - mm/huge_memory.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff8120e0db)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/exec.c (ffffffff8121408d)
Location: include/linux/slab.h:590
Inline: True
```
```
In fs/namespace.c (ffffffff8122c426)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffffffff81243336)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff8125ca00)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In fs/locks.c (ffffffff8125f736)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81270b76)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/kernfs/dir.c (ffffffff8128976d)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/page-io.c (ffffffff8129fac6)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/mballoc.c (ffffffff812d31e0)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/crypto.c (ffffffff812e5177)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_get_crypto_ctx
  - fs/ext4/crypto.c:ext4_init_crypto
```
```
In fs/jbd2/transaction.c (ffffffff812e7147)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff812f2fa7)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff81300d2c)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff813031a5)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81309ad4)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
```
```
In security/keys/key.c (ffffffff8132ff6f)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/selinux/avc.c (ffffffff81340466)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/hooks.c (ffffffff81345176)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_file_alloc_security
```
```
In security/selinux/ss/avtab.c (ffffffff8134f138)
Location: include/linux/slab.h:590
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813601a6)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:new_inode_smack
```
```
In block/bsg.c (ffffffff813d6377)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In lib/idr.c (ffffffff813e9e55)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8149c222)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff814a23d7)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814a91d2)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814a9e72)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi.c (ffffffff815a635c)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae799)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81648c74)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8169fe3a)
Location: include/linux/slab.h:590
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81710ee2)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff817a2029)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff817a8f68)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv6/ip6_fib.c (ffffffff817da9a4)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff817f9cb3)
Location: include/linux/slab.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/fork.c (ffffffff81081a14)
Location: include/linux/slab.h:624
Inline: True
```
```
In kernel/user.c (ffffffff8108f904)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810a5d46)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff810f8476)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/user_namespace.c (ffffffff81126ee3)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81127885)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff811464a5)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811474e7)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff81fb3bc5)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/mmap.c (ffffffff811e26a8)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffff812059e6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81fb6bf6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8121c996)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff81234b0b)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/exec.c (ffffffff8123adef)
Location: include/linux/slab.h:624
Inline: True
```
```
In fs/namespace.c (ffffffff81254bb6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffffffff8126b406)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff81285a88)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In fs/crypto/crypto.c (ffffffff81288558)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_get_ctx
```
```
In fs/locks.c (ffffffff8128b836)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8129cfa6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/kernfs/dir.c (ffffffff812b6c2d)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/page-io.c (ffffffff812ce386)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/mballoc.c (ffffffff813038da)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/jbd2/transaction.c (ffffffff81314cb3)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81320977)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff81334f8c)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff81337125)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8133ee42)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In security/keys/key.c (ffffffff81364cac)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/selinux/avc.c (ffffffff81375b16)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/hooks.c (ffffffff8137c066)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
```
```
In security/selinux/ss/avtab.c (ffffffff81385158)
Location: include/linux/slab.h:624
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81396716)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:new_inode_smack
```
```
In block/bsg.c (ffffffff8141c367)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In lib/idr.c (ffffffff81430235)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff814eb2a2)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff814f1704)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814f8468)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814f911c)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi.c (ffffffff815fe5f6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81606a01)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f299)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a9734)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8170123a)
Location: include/linux/slab.h:624
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81778822)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fcf7)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff818174bc)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff818496ba)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/ip6mr.c (ffffffff8186a46b)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81086402)
Location: include/linux/slab.h:624
Inline: True
```
```
In kernel/user.c (ffffffff81094884)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810ab9a6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81105e06)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/user_namespace.c (ffffffff81130a08)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113154b)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff811502e5)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81151387)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff81ff0582)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/mmap.c (ffffffff811f2678)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffff812179f6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81ff3605)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8122ef96)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812476bb)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/exec.c (ffffffff8124db93)
Location: include/linux/slab.h:624
Inline: True
```
```
In fs/namespace.c (ffffffff81268116)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffffffff8127e556)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff81299bde)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff8129dcdd)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/crypto.c:fscrypt_get_ctx
```
```
In fs/locks.c (ffffffff812a0636)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812b2906)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/kernfs/dir.c (ffffffff812cc3bd)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/page-io.c (ffffffff812e4176)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/mballoc.c (ffffffff8131989a)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/jbd2/transaction.c (ffffffff8132ac77)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81336827)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8134ad5c)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8134cef5)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81354bd2)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In security/keys/key.c (ffffffff8137b4cc)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/selinux/avc.c (ffffffff8138c446)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/hooks.c (ffffffff81392b36)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
```
```
In security/selinux/ss/avtab.c (ffffffff8139bbe8)
Location: include/linux/slab.h:624
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813acea6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:new_inode_smack
```
```
In block/bsg.c (ffffffff814378a5)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In lib/idr.c (ffffffff8144c465)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - lib/idr.c:idr_preload
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8150db2a)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81514165)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8151ae76)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8151bb33)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi.c (ffffffff8162dbf6)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff8163618e)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd359)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d7874)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81732f9a)
Location: include/linux/slab.h:624
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817a587b)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81841247)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81848d2c)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b52d)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/ip6mr.c (ffffffff8189d2bb)
Location: include/linux/slab.h:624
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810831d7)
Location: include/linux/slab.h:654
Inline: True
```
```
In kernel/user.c (ffffffff81091984)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810a8586)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81107edc)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8113204c)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81132ae5)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff81152905)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81153980)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff820d2994)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/mmap.c (ffffffff811fd618)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffff812235e6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff820d5d9d)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8123a7d6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff81252ecb)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/exec.c (ffffffff81259bc2)
Location: include/linux/slab.h:654
Inline: True
```
```
In fs/namespace.c (ffffffff812755c6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffffffff8128c226)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff812a7935)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff812ac77f)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/locks.c (ffffffff812af476)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812bfef6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/kernfs/dir.c (ffffffff812d9a0d)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff812dee53)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81310c0c)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff8131ddb6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff8133ff80)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8134b4db)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8135f8ec)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff81361a62)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81369785)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In security/keys/key.c (ffffffff8138f0ba)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/selinux/avc.c (ffffffff813a2246)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff813b0ffa)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/avtab.c (ffffffff813b2338)
Location: include/linux/slab.h:654
Inline: True
```
```
In block/bsg.c (ffffffff81445065)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8151e1d6)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81524901)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8152b691)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8152c347)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649f3c)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d13af)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ebc8f)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8174bd8a)
Location: include/linux/slab.h:654
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c3ae2)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81862ac3)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff8186a505)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0e7c)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/ip6mr.c (ffffffff818c37df)
Location: include/linux/slab.h:654
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81089b75)
Location: include/linux/slab.h:676
Inline: True
```
```
In kernel/user.c (ffffffff81098814)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810aed26)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8111308c)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8113edcb)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113f8f2)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff8115f135)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81160180)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff826db3ba)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/mmap.c (ffffffff81215bb8)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffff8123ec26)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff826de9e5)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8125a066)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff81274fcb)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/exec.c (ffffffff8127bde4)
Location: include/linux/slab.h:676
Inline: True
```
```
In fs/namespace.c (ffffffff81297e86)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/buffer.c (ffffffff812aed96)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff812caec5)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff812cff93)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/locks.c (ffffffff812d2ef6)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812e3876)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/kernfs/dir.c (ffffffff812fe2b5)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff813037c3)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81335aad)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813423c6)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff81364590)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8136fb0b)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff813845ac)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff81386732)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8138e365)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In security/keys/key.c (ffffffff813b459d)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff813c4c3f)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/security.c:lsm_early_inode
```
```
In security/selinux/avc.c (ffffffff813c8046)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff813d70ea)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff813d7718)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff813d8478)
Location: include/linux/slab.h:676
Inline: True
```
```
In block/bsg.c (ffffffff81471b32)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8156f7a2)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8157a54a)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815856ef)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81586b27)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b308c)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173da1f)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8175847f)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff817be10a)
Location: include/linux/slab.h:676
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183d5a2)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2bf0)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff818eca74)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff81921eb6)
Location: include/linux/slab.h:676
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81946a85)
Location: include/linux/slab.h:676
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff8108b5f5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In kernel/user.c (ffffffff8109bf51)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810b5b65)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8111f7f0)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8114d70f)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e253)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/delayacct.c (ffffffff8116e0e5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8116f0b8)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff8270586a)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/ksm.c (ffffffff812623d5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff82708f24)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8127dd94)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff8129b88b)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812bde15)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff812c29fe)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff812d68c5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff812f53b3)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff812fa331)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/locks.c (ffffffff812fd7e5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff813102a5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8132038a)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81327ff5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/dir.c (ffffffff8132c2c0)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81332405)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81363cab)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff81370255)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff81392d50)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8139e01c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff813b3397)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff813b556c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff813bcb85)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In security/keys/key.c (ffffffff813e4d3e)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/selinux/avc.c (ffffffff813f76a5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/hooks.c (ffffffff813fbef2)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
```
```
In security/selinux/ss/ebitmap.c (ffffffff81407732)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff81407d88)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81408ab4)
Location: include/linux/slab.h:695
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814193c5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:new_inode_smack
```
```
In block/bsg.c (ffffffff814a6047)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/bsg.c:bsg_write
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815a647d)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815b163e)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815bc8b6)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815bdcd0)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ef29c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e3a3)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81797974)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81806364)
Location: include/linux/slab.h:695
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81887e35)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff819393e7)
Location: include/linux/slab.h:695
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819427fa)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a235)
Location: include/linux/slab.h:695
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199efec)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810945d7)
Location: include/linux/slab.h:730
Inline: True
```
```
In kernel/user.c (ffffffff810a4151)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810bedd5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8112afc0)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8115a3cf)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115af33)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff811673c1)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff8117bb25)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8117cbb8)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828bcfb1)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/ksm.c (ffffffff81276c55)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828c01c9)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff81292474)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812b0795)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812d29e5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff812d7c9e)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff812ebd45)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff8130a4a3)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff8130f681)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keyinfo.c (ffffffff81311277)
Location: include/linux/slab.h:730
Inline: True
```
```
In fs/locks.c (ffffffff81313065)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81327235)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8133746a)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff8133f1d5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/dir.c (ffffffff81343cb0)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81349845)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff8137bf4d)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813886e5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813aba59)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813b6d8c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff813cc877)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff813cea8c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff813d61f5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff813d9625)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In security/keys/key.c (ffffffff813ff54e)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8141038f)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff814130a5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff81423282)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff814238d9)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81424d74)
Location: include/linux/slab.h:730
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815bf1c2)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815ca77e)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815d5cfc)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815d711b)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4a32)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bdeb4)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff818324f4)
Location: include/linux/slab.h:730
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a8945)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81968fd2)
Location: include/linux/slab.h:730
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819728ca)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff819b02a5)
Location: include/linux/slab.h:730
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d5b0c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81098d4d)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8e31)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810c4e75)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81136039)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff81166a9d)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811675e3)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81174118)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff81188945)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81189a6d)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828d4599)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff8126b056)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812924c5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828d954e)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812ace63)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812cd0d5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812efbb5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff812f61b2)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff8130d465)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff8132c6e9)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff81336b35)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keyinfo.c (ffffffff81338797)
Location: include/linux/slab.h:736
Inline: True
```
```
In fs/locks.c (ffffffff8133a865)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8134edd5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8135f590)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81367505)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff8136a793)
Location: include/linux/slab.h:736
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8136bf24)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81371645)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813a609f)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813b27c5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813d5c71)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813e148c)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff813f73d7)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff813f9a4e)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81400a65)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff814051c5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8142bc4f)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8143dabf)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff81440b45)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff81450e0d)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff81451439)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81452915)
Location: include/linux/slab.h:736
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8146469a)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff81468ef4)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f0e1e)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815fbf2d)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8160769f)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81608aff)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3c72)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fd03f)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81874d08)
Location: include/linux/slab.h:736
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f3f75)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf99c)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc36c)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e3e5)
Location: include/linux/slab.h:736
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a44bc5)
Location: include/linux/slab.h:736
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff8109f309)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810af401)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810cdf75)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff811420d9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8117295d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811734a3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8117ff88)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff81194885)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811959a7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828dca28)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff81279f83)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812a2245)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828e19a1)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812bda63)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812deaf5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff81301685)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff81307d7e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81320435)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff8133f539)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff8134a6b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffff8134dbf0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81350c50)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff81352d95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff813670d5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff813777f0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff8137f785)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff81382973)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813840f4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81389a95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813bef0f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813cb815)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813efca8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813fb4dc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff814112a7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8141391e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8141a955)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff8141f315)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8144599f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8145750f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff8145a455)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff8146abed)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff8146b219)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff8146c6b5)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8147e46a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff81482cd4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816122ac)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8161d3d7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81628b3a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81629fa4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff816ddbf0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814a54)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182de8f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff818a6b18)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81925f35)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0652c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1335c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff81a55045)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b7b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810a4c3d)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810b7111)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810d7d35)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81150a38)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff811847bd)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81184f85)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81192f7a)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff811a98b5)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811a9ce9)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In mm/slab_common.c (ffffffff82cfa553)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff812aa791)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812d6955)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:get_next_rmap_item
```
```
In mm/slub.c (ffffffff82cfef60)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812f3263)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff81315945)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8133a745)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff8134121e)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81359495)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff81379089)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff81393b61)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81397660)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8139dccd)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813ae945)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff813c0660)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff813c98d5)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff813cd095)
Location: include/linux/slab.h:657
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813ce394)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff813d4ca5)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff8140afdd)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff81417a25)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff8143d497)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81448c9b)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8145ee8e)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff81461abe)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff814693f5)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff8146e7f8)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/keys/key.c (ffffffff81496cff)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff814aa34f)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff814ad9d5)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff814bf046)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff814bf78f)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff814c0f05)
Location: include/linux/slab.h:657
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814d3706)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff814d8b34)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be7d9)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c9960)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d53e3)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d6783)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff817948ac)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5cef)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819026cf)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81976915)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_build_path_uevent
```
```
In net/core/net_namespace.c (ffffffff819f9ef0)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81af61e8)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81b03899)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16b55)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ede3)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b7668f)
Location: include/linux/slab.h:657
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810a034d)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810b22d1)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810d2ba5)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8114ccb8)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8118180d)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811820f5)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811900ea)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff811a6ed5)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811a7309)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In kernel/events/core.c (ffffffff81244f18)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
```
```
In mm/slab_common.c (ffffffff82fe7259)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/vmalloc.c (ffffffff812b5e56)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812e2495)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:get_next_rmap_item
```
```
In mm/slub.c (ffffffff82feb91e)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812fe9c3)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff81320ea5)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff81346355)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff8134d2ae)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81367255)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff8137b172)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff81386dd9)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff813a505f)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff813a90d0)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff813af67d)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813bff35)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff813d24b0)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff813db545)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff813decc5)
Location: include/linux/slab.h:670
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813dffc4)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff813e69c5)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff8141e436)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff8142b525)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff81459817)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8146583b)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8147ab2e)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8147d62e)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81484875)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff81488f78)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/keys/key.c (ffffffff814b476f)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff814c795f)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff814cb455)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dca66)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff814dd2a8)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff814df140)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_duplicate
```
```
In security/smack/smack_lsm.c (ffffffff814f08c6)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff814f60a4)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816dc347)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816e7986)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816f339f)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816f472e)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff817c01fc)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818ef7ff)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190af9f)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8197b633)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_build_path_uevent
```
```
In net/core/net_namespace.c (ffffffff819f9a70)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81b03058)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81b11a0e)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24d35)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5da63)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b85454)
Location: include/linux/slab.h:670
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810a110d)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810b3911)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810d47d5)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8114f0c6)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8118294d)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183245)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8119141a)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff811a7a15)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811a7e49)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In kernel/events/core.c (ffffffff8124a15b)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
```
```
In mm/slab_common.c (ffffffff831f1991)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/vmalloc.c (ffffffff812bb549)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812e9c25)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (ffffffff831f631b)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff81305633)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff81317741)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff81326fa5)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8134c765)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff81353eae)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff8136dc55)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff81382f2a)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff8138dbb9)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff813ac14f)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff813b00d5)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff813b693d)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813c6dd5)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff813d92b1)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff813e2475)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff813e59e5)
Location: include/linux/slab.h:674
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e6b74)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff813ed745)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81424db5)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff81432075)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff8145f0d7)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8146afeb)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8148056e)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff814831ae)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8148a325)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff8148e87a)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/keys/key.c (ffffffff814ba526)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff814cdf8f)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff814d1a85)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e33a6)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff814e3c18)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff814e5385)
Location: include/linux/slab.h:674
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f7846)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff814fcd72)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be21f)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c9849)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d515e)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d65cc)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff817a336c)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d2f1f)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ed29f)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8195f8a8)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff819dfc25)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeeabf)
Location: include/linux/slab.h:674
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b002bd)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12955)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bd8a)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b73fc4)
Location: include/linux/slab.h:674
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810b252d)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810c5ab1)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810e79b5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81173283)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff811aa91d)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab2f5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811ba2da)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff811d1391)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811d1979)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In kernel/events/core.c (ffffffff812830af)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
```
```
In mm/slab_common.c (ffffffff832d7302)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/vmalloc.c (ffffffff812fdb7a)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff81331b55)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (ffffffff832dc95b)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8134f493)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff81363da1)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff81374565)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8139a5e5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff813a22fe)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff813bc955)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff813d01bf)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff813db3a9)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff813fba6f)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff813ffcc5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8140663d)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff81417085)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8142a9e1)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81433f85)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff814375b5)
Location: include/linux/slab.h:709
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81438714)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff8143fcb5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81478b8d)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff814858e5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff814b4597)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff814c190b)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff814d7e0e)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff814da92e)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff814e1b25)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff814e62ea)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/keys/key.c (ffffffff81512d56)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff81526d3f)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff8152a805)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153c766)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff8153d038)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff8153ea75)
Location: include/linux/slab.h:709
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815523e6)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff81557ab2)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff817354ae)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81740beb)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8174cb85)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8174e138)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff8182cc50)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196d9bf)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819899bf)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81a05205)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff81a90025)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81baee8f)
Location: include/linux/slab.h:709
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc23ad)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd67f5)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81c130c6)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e873)
Location: include/linux/slab.h:709
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810c7a4c)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810dd0b1)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff81101c55)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff811a65aa)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff811dbf88)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dca56)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811ed66a)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff81205ab2)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81207126)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/events/core.c (ffffffff812d77ac)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
```
```
In mm/slab_common.c (ffffffff8348bf26)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/vmalloc.c (ffffffff81364b23)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff813a2ce1)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (ffffffff83492308)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff813c76f1)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff813e0b41)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff813f3555)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8141d305)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff81425e8e)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81442de5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff814588fa)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff81463916)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff8146ee21)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff81473a95)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8147b13d)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/quota/dquot.c (ffffffff8148ec65)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff814a3fc8)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff814adfe5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff814b222f)
Location: include/linux/slab.h:721
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff814b3210)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff814ba3c5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff814fb334)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff81508d85)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff8153de62)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8154c308)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8156547e)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff81568298)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8156fd05)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff81574e78)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/keys/key.c (ffffffff815a5169)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff815bb814)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff815c01d5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d40e5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff815d4a93)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff815d6575)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
```
```
In security/smack/smack_lsm.c (ffffffff815ebe46)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff815f219c)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff818664ee)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81872584)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8187f298)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff818809ab)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff8196df12)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac7f9f)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae75e4)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81b6cf64)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff81c05e45)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81d421ce)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d57194)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d0c5)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81dae5d8)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd023)
Location: include/linux/slab.h:721
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810e4e7c)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff810fd3d1)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff81126e45)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff811e614a)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff812217e8)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff812223b6)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81233c3a)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff8124dc42)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8124f496)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/events/core.c (ffffffff81338e62)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_pmu_context
```
```
In mm/slab_common.c (ffffffff83ebcfb5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/vmalloc.c (ffffffff813e0680)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff81422941)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (ffffffff83ec5ee5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff8144b6e1)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff814677d1)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff8147c305)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff814a9655)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff814b275e)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff814d1ef5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff814e742a)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff814f3bd6)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff815003cd)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff81505a95)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8150dcbd)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/quota/dquot.c (ffffffff815227b5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff815393d8)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff815445a5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff81548dad)
Location: include/linux/slab.h:708
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81549e80)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81551c25)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81595ad4)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff815a38f5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff815dc712)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff815ec128)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8160865e)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8160bb18)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81614c05)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff81619515)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8164ef59)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff81667604)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff8166c705)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff816821c4)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff81682c03)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81684875)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
```
```
In security/smack/smack_lsm.c (ffffffff8169baa6)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff816a297c)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In security/apparmor/audit.c (ffffffff816c1ad5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff819a49f3)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819b342a)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff819c3168)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff819c4ea5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff81ad8852)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c522ef)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c73504)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81d090e4)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff81db5745)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0b00e)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f20832)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38535)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e0e5)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff81fae4ab)
Location: include/linux/slab.h:708
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810f051c)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff81109401)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff811342e5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff811fa789)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff81237c98)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff812389e7)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8124a92a)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff81264fc2)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81266846)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5858)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/events/core.c (ffffffff8136a212)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_pmu_context
```
```
In mm/slab_common.c (ffffffff813d3d5d)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
```
```
In mm/vmalloc.c (ffffffff81415439)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff81457821)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (ffffffff836eafc5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff81480f71)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff8149cf89)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff814b18a5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
```
In fs/namespace.c (ffffffff814de5a5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff814e77ae)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff815087f5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff8151f24b)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff8152a9a6)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff81537be8)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff8153cd65)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8154549d)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/quota/dquot.c (ffffffff8155a905)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff81571618)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff8157c1a5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff8158097d)
Location: include/linux/slab.h:691
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81581aa0)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81589965)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/extents_status.c (ffffffff815a1259)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff815cc4c9)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff815da385)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff816141b2)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81623c08)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff816404a1)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff816439f8)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff8164cc85)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff81651665)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff816877c2)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8169fc24)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff816a4a25)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba344)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff816bad83)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff816bcbe5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
```
```
In security/smack/smack_lsm.c (ffffffff816d4586)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff816db79c)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In security/apparmor/audit.c (ffffffff816fa645)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff819eb6c3)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819fa32a)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a508)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a0c2a5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff81b26947)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb98af)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cdaaf3)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81d72264)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff81e25d15)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6abd6)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f81052)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f25)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81fde2f6)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff8200f92b)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810f987c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
```
```
In kernel/user.c (ffffffff81112d94)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff8113f2e5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff81210979)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff81251798)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff812526b7)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8126483a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/delayacct.c (ffffffff8127ede2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81280741)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/trace_events_user.c (ffffffff812e209a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/events/core.c (ffffffff813935a1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_pmu_context
```
```
In mm/slab_common.c (ffffffff813fe9fd)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
```
```
In mm/vmalloc.c (ffffffff81441ef9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/slub.c (ffffffff8391a245)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/ksm.c (ffffffff814922f1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (ffffffff814aff61)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/zsmalloc.c (ffffffff814cc749)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/file_table.c (ffffffff814e3055)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
```
In fs/namespace.c (ffffffff81511035)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff8151b63e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff8153d6a5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/eventpoll.c (ffffffff8155385b)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff8155f876)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keysetup.c (ffffffff8156ccf8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/verity/open.c (ffffffff815721c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8157a9fd)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/backing-file.c (ffffffff8158183b)
Location: include/linux/slab.h:699
Inline: True
```
```
In fs/quota/dquot.c (ffffffff815910c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff815a9fc8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff815b4ab5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff815b940d)
Location: include/linux/slab.h:699
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff815ba540)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff815c2585)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/extents_status.c (ffffffff815d9fb8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff81604f59)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff81612b45)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
```
```
In fs/jbd2/transaction.c (ffffffff8164cfa2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8165cca8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff81679a51)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8167cf88)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff816861b5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
```
```
In fs/fuse/dev.c (ffffffff8168ac75)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff816c3cd2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff816dc514)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff816e1485)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f6dd4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff816f7774)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff816f9715)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
```
```
In security/smack/smack_lsm.c (ffffffff81710a2c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff81717f1c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In security/apparmor/audit.c (ffffffff81737255)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81a36483)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81a4517a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a554a8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a57275)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff81b7d587)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6e61f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8fb23)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff81e29334)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
```
In net/core/net_namespace.c (ffffffff81ee3c75)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff82031286)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff820476d2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_state.c (ffffffff82065295)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff820abe76)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ip6mr.c (ffffffff820de8bb)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In virt/kvm/arm/arm.c (ffff8000100c6204)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_create
```
```
In kernel/fork.c (ffff8000100f3a3c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffff80001010a548)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffff80001012d634)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffff8000101ac1f4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffff8000101e68e8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffff8000101e77ec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffff8000101f5244)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffff80001020c95c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffff80001020da38)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffff80001145557c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffff800010311298)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffff800010341a8c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffff80001145ac68)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffff80001035ef3c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffff800010385238)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffff8000103b3d94)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffff8000103bb840)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffff8000103d7f20)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffff8000103feac4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffff80001040aed8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffff80001040eefc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffff800010412c80)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffff80001041480c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffff80001042e718)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffff800010443484)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffff80001044cf40)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffff800010450e2c)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffff8000104526a0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffff80001045a580)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffff800010495bf8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffff8000104a392c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffff8000104c95e4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffff8000104d8b74)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffff8000104f257c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffff8000104f4e18)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffff8000104fc6b0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffff8000105015a0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffff80001052eae0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffff8000105430c8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffff800010546c90)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffff80001055990c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffff800010559f78)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffff80001055b600)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffff80001056f2f0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffff8000105747dc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffff80001078c1a0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffff800010793d24)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffff80001079d5e0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffff80001079e5b4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffff8000108ce1c4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dc14)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6bc20)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffff800010afbd40)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffff800010bc1f80)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf374)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010ccd8ec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffff800010d18c58)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d45334)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (c0352410)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c0363538)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (c037d760)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (c03f65a0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (c0426fdc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c0427bc8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (c04353dc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (c044b300)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (c044c614)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (c1530524)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (c052abec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (c054797c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
```
```
In mm/slub.c (c15338e4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In fs/file_table.c (c056e0f8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (c0592c90)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (c0599054)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (c05b1d18)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (c05d09dc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
```
```
In fs/crypto/crypto.c (c05d8060)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (c05dba28)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (c05df058)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (c05e12f8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (c05f7f10)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (c06087c4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (c061169c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (c0613de4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/inode.c:__kernfs_iattrs
```
```
In fs/kernfs/dir.c (c0614bf8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (c061b6f4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (c06577d0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (c066575c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (c068d034)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (c069aa6c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (c06aff94)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (c06b26ac)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (c06b9ce4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (c06be398)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (c06e6e98)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (c06f9064)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (c06fc630)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (c070e194)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (c070e820)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (c070fe20)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (c0722d1c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (c0727974)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/iommu/omap-iommu.c (c09c3c98)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/exynos-iommu.c (c1597704)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1fd0c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (c0b3c670)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (c0bdc274)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (c0cdd484)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (c0dcaca4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd89a8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (c0e1e52c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:node_alloc
```
```
In net/ipv6/ip6mr.c (c0e47eec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (c000000000139ab8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c000000000151540)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (c000000000176620)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (c00000000020fe0c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (c000000000257068)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c0000000002580c4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (c00000000026a760)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (c00000000028a5c0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (c00000000028bd50)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (c00000000137e1ec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (c0000000003e2180)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (c00000000041f184)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/slub.c (c000000001384e8c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (c000000000449a14)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (c00000000047b1c8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (c0000000004afaf4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (c0000000004b8c70)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (c0000000004dd050)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (c00000000050852c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (c000000000517900)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (c00000000051c5e4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (c000000000520904)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (c000000000523ad0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (c0000000005401bc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (c000000000558b30)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (c000000000564704)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (c000000000569268)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (c00000000056a798)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (c000000000574a54)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (c0000000005bf8d8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (c0000000005d0850)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (c00000000060275c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (c000000000613b9c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (c000000000632184)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (c0000000006356a8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (c00000000063f5ac)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (c000000000645c74)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (c00000000067b370)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (c000000000696d58)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (c00000000069d624)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (c0000000006b7b00)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (c0000000006b838c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (c0000000006ba87c)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d5080)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (c0000000006dd3d0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15428)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3b960)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (c000000000be9c48)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (c000000000c9bd6c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (c000000000dd9fac)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea2f8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (c000000000e466c0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:node_alloc
```
```
In net/ipv6/ip6mr.c (c000000000e7ae48)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffe0000c0308)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffe0000ccf86)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffe0000e1a6e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffe000136142)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffe00015c194)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffe00015cca4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffe0001682c8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffe00016dc70)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffe00016eb1e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffe00001461e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffe000218ec8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffe000235eea)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
```
```
In mm/slub.c (ffffffe000018d58)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In fs/file_table.c (ffffffe000258026)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffe000277610)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffe00027d380)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffe000291c08)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffe0002abafc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
```
```
In fs/crypto/crypto.c (ffffffe0002b4c04)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffe0002b7c7e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffe0002ba8d0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffe0002bc558)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffe0002cb0ba)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffe0002d9ba0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffe0002e1f90)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffe0002e3d36)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffe0002e51c2)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffe0002eb922)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffe00031a7de)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffe00032513e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffe000342ab4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffe00034e552)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffe000361cba)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffe000363ede)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffe00036ad8c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffe00036ec38)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffe00039036a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffe00039f71c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffe0003a22ce)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffe0003b096c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffe0003b1078)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffe0003b22ba)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c522c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffe0003c78ca)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a67c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000683e94)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffe0006ecf12)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074efd0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffe000815182)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe00081fdd2)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d5be)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:node_alloc
```
```
In net/ipv6/ip6mr.c (ffffffe00088063e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81098c29)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a9771)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810c82f5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8113a889)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8116af7d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bac3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff811785a8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff8118cea5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8118dfc7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828c58dc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff812725d3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff8129a825)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828ca855)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812b6043)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812d70d5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812f9c65)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff8130035e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81318a15)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff81337b19)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff81342c95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffff813461d0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81349230)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8134b375)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8135f6b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8136fdd0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81377d65)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff8137af53)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8137c6d4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81382075)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813b74ef)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813c3df5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813e8288)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f3abc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff81409887)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8140befe)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81412f35)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff814178f5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8143df7f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8144faef)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff81452a35)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff814631cd)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff814637f9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81464c95)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81476a4a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff8147b2b4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f25f8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815f91a7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81600485)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816010f8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff816a3640)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cce34)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e626f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8184c998)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c5f35)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff819a62cc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b2b5c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff819f46d5)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ae45)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81087679)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff8109812b)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810b6b15)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8112d2d9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8115e17d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ecc3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8116b748)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff8117ff85)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff811810d7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828be001)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff81264543)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff8128c3e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828c2f7a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812a7233)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812c7d55)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812ea885)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff812f0f7e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff81309605)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff81328849)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff81333975)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffff81336eb0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81339f10)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8133c055)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81350355)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff81360860)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81368835)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff8136ba23)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8136d1a4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81372b05)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813a7f7f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813b4875)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813d8d08)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813e453c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff813fa307)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff813fc97e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff814039b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff81408375)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8142e9ef)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8144053f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff81443485)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff81453bfd)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff81454229)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff814556c5)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8146746a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff8146bcd4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815ddb86)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815e46e1)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815eb94c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815ec5b3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff81681030)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/md/dm-uevent.c (ffffffff81813fb8)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187fe75)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fd8c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f18c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1495)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d7c05)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff81098bd9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8cd1)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810c7835)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff811385a9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff81168d4d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81169893)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81176378)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff8118ac75)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff8118bd97)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828d865c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff81270373)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff81298635)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828dd5d5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812b3e53)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812d4ee5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812f7a55)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff812fe14e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff813164e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff813355e9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff81340765)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffff81343ca0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81346d00)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff81348e45)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8135d185)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff8136d8a0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff81375835)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff81378a23)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8137a1a4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff8137fb45)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813b4d4f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813c1285)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813e5608)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f0e3c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff81406c07)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8140927e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff814102b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff81413a95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff8143a11f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff8144bb8f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff8144ead5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff8145f26d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff8145f899)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81460d35)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81472aea)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff81477354)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8160658c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816116b7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8161ce1a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8161e284)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff816d18b0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818098d4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81822d0f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff8189bfc8)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81916f35)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10b6c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d3fc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5f155)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a858c5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
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
In kernel/fork.c (ffffffff810a07fd)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b0dbd)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/cred.c (ffffffff810cfd15)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/time/posix-timers.c (ffffffff8114515a)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/user_namespace.c (ffffffff8117643d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81176fb3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81183c4c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/delayacct.c (ffffffff811985e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
```
In kernel/taskstats.c (ffffffff81199714)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/slab_common.c (ffffffff828dda7d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
```
```
In mm/vmalloc.c (ffffffff8127fda9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/ksm.c (ffffffff812a83b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff828e29ec)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
```
```
In mm/khugepaged.c (ffffffff812c42e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/file_table.c (ffffffff812e5d45)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff81308d95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/seq_file.c (ffffffff8130f48e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/seq_file.c:seq_open
```
```
In fs/buffer.c (ffffffff813282a5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
```
```
In fs/aio.c (ffffffff813485f9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff81353a65)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In fs/crypto/keysetup.c (ffffffff81356f80)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/verity/open.c (ffffffff81359fe0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/locks.c (ffffffff8135c275)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81370b25)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_alloc
```
```
In fs/proc/generic.c (ffffffff813811d3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff813892e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/kernfs/inode.c (ffffffff8138c4d3)
Location: include/linux/slab.h:678
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8138d214)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/configfs/dir.c (ffffffff81393095)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/ext4/mballoc.c (ffffffff813c9971)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/page-io.c (ffffffff813d63e5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/jbd2/transaction.c (ffffffff813faaac)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81406998)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/ecryptfs/file.c (ffffffff8141c8c7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/main.c (ffffffff8141ef3e)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/keystore.c (ffffffff81425f25)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
```
In fs/fuse/dev.c (ffffffff8142a915)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/keys/key.c (ffffffff81451244)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
```
```
In security/security.c (ffffffff81462f5f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
```
```
In security/selinux/avc.c (ffffffff81465eb5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
```
```
In security/selinux/ss/ebitmap.c (ffffffff81476a7d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/hashtab.c (ffffffff8147709d)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_insert
```
```
In security/selinux/ss/avtab.c (ffffffff81478535)
Location: include/linux/slab.h:678
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148a3da)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smackfs.c (ffffffff8148ee04)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8162043c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8162b567)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81636cca)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81638134)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/iommu/iova.c (ffffffff816ebe70)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818239e4)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183e42f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/md/dm-uevent.c (ffffffff818b8188)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81938145)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b42c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a28569)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b605)
Location: include/linux/slab.h:678
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a92332)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
</details>
</li>
</ul>

## Differences
