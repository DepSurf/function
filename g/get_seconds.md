# Function: <code>get_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f42a0)
Location: kernel/time/timekeeping.c:2140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:SyS_time
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/acct.c:do_acct_process
  - kernel/kexec_core.c:crash_save_vmcoreinfo
  - kernel/cpuset.c:fmeter_update
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - ipc/msg.c:newque
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/shm.c:shm_close
  - ipc/shm.c:newseg
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_control
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_write
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810f42a0-ffffffff810f42b2: get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb420)
Location: kernel/time/timekeeping.c:2145
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:SyS_time
  - kernel/acct.c:do_acct_process
  - kernel/kexec_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:newque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810fb420-ffffffff810fb432: get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe1e0)
Location: kernel/time/timekeeping.c:2157
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:SyS_time
  - kernel/acct.c:do_acct_process
  - kernel/kexec_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/fat/inode.c:fat_fill_inode
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:newque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810fe1e0-ffffffff810fe1f2: get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100540)
Location: kernel/time/timekeeping.c:2146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:SyS_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/fat/inode.c:fat_fill_inode
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:newque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81100540-ffffffff81100552: get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b340)
Location: kernel/time/timekeeping.c:2175
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:SyS_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/fat/inode.c:fat_fill_inode
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8110b340-ffffffff8110b352: get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117600)
Location: kernel/time/timekeeping.c:2128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - mm/shmem.c:shmem_get_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/fat/inode.c:fat_fill_inode
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81117600-ffffffff81117612: get_seconds (STB_GLOBAL)
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
In kernel/acct.c (ffffffff811411e4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff8117ce04)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff813c8cf2)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff8114c609)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff81189cc4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff813f3862)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff811582d9)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff81195bd4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff8140d742)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/acct.c (ffff8000101c7b74)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffff80001020dea4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffff8000104ee524)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (c040e690)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/tsacct.c (c044c980)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (c06ac124)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (c00000000022fd04)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (c00000000028c068)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (c00000000062d4ec)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffe0001479bc)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffe00016ed4a)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffe00035e868)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff811508f9)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff8118e1f4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff81405d22)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff81143ba9)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff81181317)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff813f67a2)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff8114e7a9)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff8118bfc4)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff814030a2)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
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
In kernel/acct.c (ffffffff8115b589)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/tsacct.c (ffffffff81199944)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/fat/inode.c (ffffffff81418d12)
Location: include/linux/timekeeping32.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
