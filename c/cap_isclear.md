# Function: <code>cap_isclear</code>

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
In kernel/cred.c (ffffffff810a23de)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/audit.c (ffffffff811226d0)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
```
```
In security/commoncap.c (ffffffff8133a701)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
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
In kernel/cred.c (ffffffff810a5b44)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/audit.c (ffffffff8112a600)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
```
```
In security/commoncap.c (ffffffff8136fe56)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810ab7a4)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/audit.c (ffffffff81134320)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
```
```
In security/commoncap.c (ffffffff81386676)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810a83a6)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In security/commoncap.c (ffffffff8139b246)
Location: include/linux/capability.h:147
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810aeb26)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In security/commoncap.c (ffffffff813c0d19)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810b58a4)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In security/commoncap.c (ffffffff813f1c6c)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810bec1b)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/audit.c (ffffffff8115d995)
Location: include/linux/capability.h:148
Inline: True
```
```
In security/commoncap.c (ffffffff8140cf3c)
Location: include/linux/capability.h:148
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810c4b54)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8116ecc5)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff81439b0c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810cdc64)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8117ab45)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff8145397c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810d7b04)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8118d7a5)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff814a602c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810d2934)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8118a94e)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff814c3552)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810d455a)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8118b7fe)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff814c99c2)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810e773b)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff811b442e)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff815224e2)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff811e698e)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8122cace)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/auditsc.c (0)
Location: include/linux/capability.h:95
Inline: True
```
```
In fs/open.c (ffffffff814a7c46)
Location: include/linux/capability.h:95
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
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
In kernel/auditsc.c (0)
Location: include/linux/capability.h:95
Inline: True
```
```
In fs/open.c (ffffffff814d8ef7)
Location: include/linux/capability.h:95
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
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
In kernel/cred.c (ffff80001012d540)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffff8000101f0884)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffff80001053e9d0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (c037d33c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (c042fd80)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (c06f49c0)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (c0000000001762a4)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (c000000000263d40)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (c00000000068f10c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffe0000e1594)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffe0001643ac)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffe00039c098)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810c7fe4)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff81173165)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff8144bf5c)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810b6804)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff81166305)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff8143c9ac)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810c7534)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff81170f35)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff81447ffc)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
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
In kernel/cred.c (ffffffff810cfa04)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/auditsc.c (ffffffff8117e745)
Location: include/linux/capability.h:149
Inline: True
```
```
In security/commoncap.c (ffffffff8145f35b)
Location: include/linux/capability.h:149
Inline: True
Inline callers:
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
```
</details>
</li>
</ul>

## Differences
