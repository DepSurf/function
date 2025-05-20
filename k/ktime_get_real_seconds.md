# Function: <code>ktime_get_real_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:852
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff810fc6f0-ffffffff810fc702: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:881
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff810ff610-ffffffff810ff622: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811004b0)
Location: kernel/time/timekeeping.c:913
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_idq
  - fs/quota/dquot.c:check_idq
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff811004b0-ffffffff811004c2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b2b0)
Location: kernel/time/timekeeping.c:917
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8110b2b0-ffffffff8110b2c2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:918
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81118370-ffffffff81118382: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:925
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_time
  - kernel/time/time.c:__ia32_compat_sys_time
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81123990-ffffffff811239a2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112cde0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff8112cde0-ffffffff8112cdf2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81138db0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81138db0-ffffffff81138dc2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147d10)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/coredump.c:format_corename
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
```
**Symbols:**

```
ffffffff81147d10-ffffffff81147d22: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144140)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/coredump.c:format_corename
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:save_error_info
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
```
**Symbols:**

```
ffffffff81144140-ffffffff81144152: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811452d0)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:save_error_info
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff811452d0-ffffffff811452e2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81168b30)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:save_error_info
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81168b30-ffffffff81168b42: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119c690)
Location: kernel/time/timekeeping.c:1020
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff8119c690-ffffffff8119c6a6: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811db070)
Location: kernel/time/timekeeping.c:1020
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff811db070-ffffffff811db086: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811ef5d0)
Location: kernel/time/timekeeping.c:1020
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_update_time
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff811ef5d0-ffffffff811ef5e6: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81205710)
Location: kernel/time/timekeeping.c:1020
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_journal_commit_callback
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_update_time
  - drivers/md/md.c:md_set_array_info
  - drivers/md/md.c:md_set_array_info
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81205710-ffffffff81205726: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffff8000101a3fd0-ffff8000101a3ff0: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ec8cc)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/acct.c:fill_ac
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/coredump.c:format_corename
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/fat/inode.c:fat_fill_inode
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
c03ec8cc-c03ec948: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000203fc0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - arch/powerpc/kernel/nvram_64.c:oops_to_nvram
  - arch/powerpc/kernel/nvram_64.c:oops_to_nvram
  - arch/powerpc/kernel/nvram_64.c:nvram_pstore_write
  - arch/powerpc/platforms/pseries/nvram.c:clobbering_unread_rtas_event
  - arch/powerpc/platforms/pseries/nvram.c:nvram_write_error_log
  - arch/powerpc/platforms/pseries/nvram.c:nvram_write_error_log
  - kernel/time/time.c:__se_sys_time32
  - kernel/time/time.c:__se_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
c000000000203fc0-c000000000203fdc: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:__save_error_info
  - fs/fat/inode.c:fat_fill_inode
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffe000130b9c-ffffffe000130bbe: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131560)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81131560-ffffffff81131572: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123fc0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81123fc0-ffffffff81123fd2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f280)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff8112f280-ffffffff8112f292: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113bca0)
Location: kernel/time/timekeeping.c:932
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
  - kernel/time/time.c:__ia32_sys_time
  - kernel/time/time.c:__x64_sys_time
  - kernel/acct.c:do_acct_process
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/tsacct.c:bacct_add_tsk
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
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
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:newary
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_alloc
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/permission.c:key_validate
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/common.c:tomoyo_update_stat
  - drivers/acpi/apei/erst.c:erst_writer
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff8113bca0-ffffffff8113bcb2: ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
