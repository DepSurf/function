# Function: <code>ptrace_parent</code>

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
In fs/proc/array.c (ffffffff81280b28)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81344d5f)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff81360642)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8137a5a9)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
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
In fs/proc/array.c (ffffffff812adba0)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81379897)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff81396bb2)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff813b3569)
Location: include/linux/ptrace.h:112
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
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
In fs/proc/array.c (ffffffff812c34a5)
Location: include/linux/ptrace.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81390306)
Location: include/linux/ptrace.h:114
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff813ad342)
Location: include/linux/ptrace.h:114
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff813ca779)
Location: include/linux/ptrace.h:114
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff813e87b6)
Location: include/linux/ptrace.h:114
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In fs/proc/array.c (ffffffff812d0726)
Location: include/linux/ptrace.h:116
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813a9919)
Location: include/linux/ptrace.h:116
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff813c5aa3)
Location: include/linux/ptrace.h:116
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff813dffee)
Location: include/linux/ptrace.h:116
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff813f4956)
Location: include/linux/ptrace.h:116
Inline: True
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
In fs/proc/array.c (ffffffff812f4f58)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813cf8ac)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff813ebd91)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff81406777)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff8141cd96)
Location: include/linux/ptrace.h:117
Inline: True
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
In fs/proc/array.c (ffffffff813222fd)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813fc4a0)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff8141c712)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8143729f)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff8144f060)
Location: include/linux/ptrace.h:117
Inline: True
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
In fs/proc/array.c (ffffffff8133940d)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81418be7)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff814393e3)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff81454b1f)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff8146c0ca)
Location: include/linux/ptrace.h:117
Inline: True
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
In fs/proc/array.c (ffffffff8136040b)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff81446a07)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff81467142)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff814824ce)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff814990c9)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff8137866b)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff8146059f)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff81480efc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8149c08e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff814b2ff9)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff813c174c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff814b2f3c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff814d64b3)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff814f42fe)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff81511ba5)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
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
In fs/proc/array.c (ffffffff813d363c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff814d23bc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff814f4197)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff81511449)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff8152e9fb)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
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
In fs/proc/array.c (ffffffff813da46c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff814d84c8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff814fb11e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff81517db9)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff815352c6)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff8142bb9c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff81530cbb)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff81555d8e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff81575db9)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff815937e0)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff814a5800)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff815c5f8b)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff815efbef)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff816134a2)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff81635acb)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In fs/proc/array.c (ffffffff8153ae10)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff81672b76)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff8169ff4f)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff816c6119)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff816ec7db)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In fs/proc/array.c (ffffffff8157311d)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff816ab073)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff816d87e2)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff816feee9)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff81726c0b)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In fs/proc/array.c (ffffffff815ab8dd)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff816e8095)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
```
```
In security/smack/smack_lsm.c (ffffffff81714fb5)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
```
```
In security/apparmor/domain.c (ffffffff8173c479)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff81767e5b)
Location: include/linux/ptrace.h:117
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In fs/proc/array.c (ffff800010444cf8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffff80001054dcf8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffff8000105726e8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffff800010591bb4)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffff8000105aa89c)
Location: include/linux/ptrace.h:124
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
In fs/proc/array.c (c06098ec)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (c06fe42c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:ptrace_parent_sid
```
```
In security/smack/smack_lsm.c (c0725978)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (c07427d0)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (c075a81c)
Location: include/linux/ptrace.h:124
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
In fs/proc/array.c (c00000000055a0f8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (c0000000006ac810)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (c0000000006da4c4)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (c000000000705afc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (c00000000072872c)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffe0002dacb6)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffe0003a7ccc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffe0003c4076)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffe0003df3e8)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffe0003f378a)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff81370c4b)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff81458b7f)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff814794dc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8149466e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff814ab5d9)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff813616db)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff814495af)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff81469efc)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8148508e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff8149bff9)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff8136e71b)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff81454c1f)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_set_creds
```
```
In security/smack/smack_lsm.c (ffffffff8147557c)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff8149070e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff814a7679)
Location: include/linux/ptrace.h:124
Inline: True
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
In fs/proc/array.c (ffffffff81382073)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/selinux/hooks.c (ffffffff8146a4fa)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:ptrace_parent_sid
```
```
In security/smack/smack_lsm.c (ffffffff8148cf6e)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
```
```
In security/apparmor/domain.c (ffffffff814a8632)
Location: include/linux/ptrace.h:124
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/yama/yama_lsm.c (ffffffff814bffcb)
Location: include/linux/ptrace.h:124
Inline: True
```
</details>
</li>
</ul>

## Differences
