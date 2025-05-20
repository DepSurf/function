# Function: <code>commit_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a21c0)
Location: kernel/cred.c:422
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setfsgid
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:key_change_session_keyring
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
ffffffff810a21c0-ffffffff810a2406: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5970)
Location: kernel/cred.c:422
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
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
ffffffff810a5970-ffffffff810a5b5a: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab5d0)
Location: kernel/cred.c:422
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
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
ffffffff810ab5d0-ffffffff810ab7ba: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a81a0)
Location: kernel/cred.c:423
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
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
ffffffff810a81a0-ffffffff810a83bc: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ae920)
Location: kernel/cred.c:423
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/capability.c:SyS_capset
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
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
ffffffff810ae920-ffffffff810aeb3c: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5690)
Location: kernel/cred.c:423
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810b5690-ffffffff810b58c1: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be9f0)
Location: kernel/cred.c:425
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810be9f0-ffffffff810bec3c: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c4920)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c4920-ffffffff810c4b75: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cda30)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810cda30-ffffffff810cdc85: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d78d0)
Location: kernel/cred.c:437
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:__do_sys_setgroups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810d78d0-ffffffff810d7b25: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2700)
Location: kernel/cred.c:437
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:__do_sys_setgroups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810d2700-ffffffff810d2955: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d4320)
Location: kernel/cred.c:449
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:__do_sys_setgroups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
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
ffffffff810d4320-ffffffff810d4579: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e74a0)
Location: kernel/cred.c:447
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:__do_sys_setgroups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
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
ffffffff810e74a0-ffffffff810e775a: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101720)
Location: kernel/cred.c:447
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:__do_sys_setgroups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81101720-ffffffff811019ee: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811268e0)
Location: kernel/cred.c:447
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:set_current_groups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff811268e0-ffffffff81126ba8: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133d90)
Location: kernel/cred.c:447
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:set_current_groups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81133d90-ffffffff8113404c: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113ea80)
Location: kernel/cred.c:392
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/groups.c:set_current_groups
  - fs/exec.c:begin_new_exec
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff8113ea80-ffffffff8113ed29: commit_creds (STB_GLOBAL)
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
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012d1f0)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__arm64_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
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
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffff80001012d1f0-ffff80001012d55c: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037d048)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
c037d048-c037d360: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175f40)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
c000000000175f40-c0000000001762cc: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e13a2)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffe0000e13a2-ffffffe0000e15b6: commit_creds (STB_GLOBAL)
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
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7db0)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c7db0-ffffffff810c8005: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b65d0)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810b65d0-ffffffff810b6825: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7300)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810c7300-ffffffff810c7555: commit_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int commit_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cf7d0)
Location: kernel/cred.c:434
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:install_exec_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/selinux/hooks.c:selinux_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
**Symbols:**

```
ffffffff810cf7d0-ffffffff810cfa25: commit_creds (STB_GLOBAL)
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
