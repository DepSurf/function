# Function: <code>abort_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810a2150)
Location: kernel/cred.c:499
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
```
**Symbols:**

```
ffffffff810a2150-ffffffff810a215b: abort_creds.part.5 (STB_LOCAL)
ffffffff810a2190-ffffffff810a21b2: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810a5c29)
Location: kernel/cred.c:499
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810a5900-ffffffff810a590b: abort_creds.part.5 (STB_LOCAL)
ffffffff810a5940-ffffffff810a5962: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810ab889)
Location: kernel/cred.c:499
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810ab560-ffffffff810ab56b: abort_creds.part.5 (STB_LOCAL)
ffffffff810ab5a0-ffffffff810ab5c2: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810a8489)
Location: kernel/cred.c:500
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810a8120-ffffffff810a812b: abort_creds.part.5 (STB_LOCAL)
ffffffff810a8170-ffffffff810a8192: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810aec21)
Location: kernel/cred.c:500
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810ae8a0-ffffffff810ae8ab: abort_creds.part.4 (STB_LOCAL)
ffffffff810ae8f0-ffffffff810ae912: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5670)
Location: kernel/cred.c:500
Inline: True
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810b5670-ffffffff810b568f: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be8c0)
Location: kernel/cred.c:502
Inline: True
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810be8c0-ffffffff810be8e4: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810c4c77)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810c48a0-ffffffff810c48ab: abort_creds.part.0 (STB_LOCAL)
ffffffff810c48f0-ffffffff810c4917: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810cdd87)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810cd9b0-ffffffff810cd9bb: abort_creds.part.0 (STB_LOCAL)
ffffffff810cda00-ffffffff810cda27: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7d74)
Location: kernel/cred.c:523
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810d7690-ffffffff810d76b3: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2be4)
Location: kernel/cred.c:523
Inline: True
Inline callers:
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810d2490-ffffffff810d24b3: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d4232)
Location: kernel/cred.c:535
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff810d4070-ffffffff810d4093: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e73b2)
Location: kernel/cred.c:533
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff810e71f0-ffffffff810e7213: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101644)
Location: kernel/cred.c:533
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81101470-ffffffff811014a3: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811267f4)
Location: kernel/cred.c:533
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81126610-ffffffff81126643: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133ca4)
Location: kernel/cred.c:533
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81133ac0-ffffffff81133af3: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113eef1)
Location: kernel/cred.c:469
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/groups.c:set_current_groups
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/apparmor/task.c:aa_set_current_hat
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff8113ea30-ffffffff8113ea67: abort_creds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012ce30)
Location: kernel/cred.c:520
Inline: True
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffff80001012ce30-ffff80001012cea4: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (c037d478)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
c037cefc-c037cf14: abort_creds.part.0 (STB_LOCAL)
c037cf7c-c037cfd8: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175d60)
Location: kernel/cred.c:520
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
c000000000175d60-c000000000175db8: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e18d4)
Location: kernel/cred.c:520
Inline: True
Direct callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffe0000e18d4-ffffffe0000e1922: abort_creds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810c8107)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810c7d30-ffffffff810c7d3b: abort_creds.part.0 (STB_LOCAL)
ffffffff810c7d80-ffffffff810c7da7: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810b6927)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810b6550-ffffffff810b655b: abort_creds.part.0 (STB_LOCAL)
ffffffff810b65a0-ffffffff810b65c7: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810c7657)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810c7280-ffffffff810c728b: abort_creds.part.0 (STB_LOCAL)
ffffffff810c72d0-ffffffff810c72f7: abort_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void abort_creds(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cred.c (ffffffff810cfb27)
Location: kernel/cred.c:520
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
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
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - fs/exec.c:free_bprm
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/selinux/hooks.c:selinux_setprocattr
  - security/apparmor/task.c:aa_set_current_hat
```
**Symbols:**

```
ffffffff810cf6f0-ffffffff810cf6fb: abort_creds.part.0 (STB_LOCAL)
ffffffff810cf7a0-ffffffff810cf7c7: abort_creds (STB_GLOBAL)
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
