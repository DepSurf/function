# Function: <code>security_task_getsecid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b570)
Location: security/security.c:944
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter_user
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
**Symbols:**

```
ffffffff8133b570-ffffffff8133b5b6: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370af0)
Location: security/security.c:968
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
**Symbols:**

```
ffffffff81370af0-ffffffff81370b36: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387420)
Location: security/security.c:989
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
**Symbols:**

```
ffffffff81387420-ffffffff81387466: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c100)
Location: security/security.c:1626
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff8139c100-ffffffff8139c146: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1830)
Location: security/security.c:1588
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff813c1830-ffffffff813c187c: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2dc0)
Location: security/security.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff813f2dc0-ffffffff813f2e04: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e260)
Location: security/security.c:1700
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff8140e260-ffffffff8140e2a4: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ae10)
Location: security/security.c:1719
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff8143ae10-ffffffff8143ae56: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454c00)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff81454c00-ffffffff81454c44: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a85c0)
Location: security/security.c:1948
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_lsm
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff814a85c0-ffffffff814a862d: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5b50)
Location: security/security.c:1965
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_lsm
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff814c5b50-ffffffff814c5bbe: security_task_getsecid (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053fe38)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffff80001053fe38-ffff80001053fe90: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5ef8)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
c06f5ef8-c06f5f50: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006912b0)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
c0000000006912b0-c000000000691340: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d132)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
**Symbols:**

```
ffffffe00039d132-ffffffe00039d176: security_task_getsecid (STB_GLOBAL)
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
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d1e0)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff8144d1e0-ffffffff8144d224: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dc30)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff8143dc30-ffffffff8143dc74: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449280)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff81449280-ffffffff814492c4: security_task_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460650)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_task_context
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff81460650-ffffffff81460694: security_task_getsecid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *secid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
