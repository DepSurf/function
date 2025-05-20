# Function: <code>prepare_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a2410)
Location: kernel/cred.c:243
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setfsgid
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:copy_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
**Symbols:**

```
ffffffff810a2410-ffffffff810a2508: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5b60)
Location: kernel/cred.c:243
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810a5b60-ffffffff810a5c4b: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab7c0)
Location: kernel/cred.c:243
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810ab7c0-ffffffff810ab8ab: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a83c0)
Location: kernel/cred.c:244
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810a83c0-ffffffff810a84ab: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810aeb40)
Location: kernel/cred.c:244
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810aeb40-ffffffff810aec43: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b58d0)
Location: kernel/cred.c:244
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810b58d0-ffffffff810b59bd: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be8f0)
Location: kernel/cred.c:246
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810be8f0-ffffffff810be9e3: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c4b80)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c4b80-ffffffff810c4ca0: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cdc90)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810cdc90-ffffffff810cddb0: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d76c0)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:__do_sys_setgroups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:access_override_creds
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810d76c0-ffffffff810d78c8: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d24c0)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:__do_sys_setgroups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:access_override_creds
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810d24c0-ffffffff810d26fb: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d40a0)
Location: kernel/cred.c:254
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:__do_sys_setgroups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff810d40a0-ffffffff810d4311: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e7220)
Location: kernel/cred.c:252
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:__do_sys_setgroups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff810e7220-ffffffff810e7491: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811014b0)
Location: kernel/cred.c:252
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:__do_sys_setgroups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff811014b0-ffffffff81101719: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126660)
Location: kernel/cred.c:252
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81126660-ffffffff811268c9: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133b10)
Location: kernel/cred.c:252
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:unshare_userns
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81133b10-ffffffff81133d79: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113ed40)
Location: kernel/cred.c:206
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:unshare_userns
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff8113ed40-ffffffff8113efe8: prepare_creds (STB_GLOBAL)
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
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cf10)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__arm64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffff80001012cf10-ffff80001012d010: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037d360)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
c037d360-c037d4cc: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175dc0)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
c000000000175dc0-c000000000175f40: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e1922)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffe0000e1922-ffffffe0000e19e6: prepare_creds (STB_GLOBAL)
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
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c8010)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c8010-ffffffff810c8130: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b6830)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810b6830-ffffffff810b6950: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7560)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c7560-ffffffff810c7680: prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cred *prepare_creds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cfa30)
Location: kernel/cred.c:250
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810cfa30-ffffffff810cfb50: prepare_creds (STB_GLOBAL)
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
