# Function: <code>audit_get_loginuid</code>

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
In kernel/audit.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In kernel/auditsc.c (ffffffff81128e02)
Location: include/linux/audit.h:232
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
```
```
In kernel/audit_watch.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:232
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:232
Inline: True
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
In kernel/audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113169b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:335
Inline: True
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
In kernel/audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113b41b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:335
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:335
Inline: True
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
In kernel/audit.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113caed)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:333
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:333
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
In kernel/audit.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In kernel/auditsc.c (ffffffff8114986d)
Location: include/linux/audit.h:325
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:325
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:325
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
In kernel/audit.c (ffffffff81150a7c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81154093)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81155606)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff8115882a)
Location: include/linux/audit.h:329
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff81159618)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (ffffffff8131d15e)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81404a96)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8141379c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814205ef)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff81450172)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8161c91c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff818991b8)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aeca)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81952bba)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9f02)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc67e)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcf59)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdcd9)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8115d71c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81160e4c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811629b6)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In fs/proc/base.c (ffffffff81333a1e)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81420af6)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8142fcc9)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8143c827)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8146d152)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81639b9c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff818bb65a)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d96a)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819857ca)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f11d2)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f38ce)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4199)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4e79)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8116b6c3)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff8116d551)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8116e836)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8135ba3e)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8144e6ec)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8145d68d)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8146a42d)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8149a84c)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8166decc)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81907579)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6daa)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819ef5ea)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60482)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62cfe)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63609)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64339)
Location: include/linux/audit.h:174
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff811775a3)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff811793f1)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117a6b6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff81373e8e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81468514)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8147743d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8148420d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814b4a4c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8169053c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81939b60)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1de8a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a265aa)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a970b2)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a998de)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a1b9)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9aeb9)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8118a215)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8118c44e)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118d6d6)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff813bc050)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814bc364)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814cc8ac)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814d7939)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff81513f9c)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81742c7c)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81a0f100)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0fde1)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17141)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92ee2)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95118)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b955e9)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b966b9)
Location: include/linux/audit.h:186
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8118753a)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8118965f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118a876)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff813cdc20)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814d9e49)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814ea10f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814f4eb9)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff815310fc)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff8175eb25)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81c3144b)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1cd01)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25511)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2b32)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4d78)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5239)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6329)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff811885aa)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8118a4d0)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118b726)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff813d4bb0)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814e12f0)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814f0d0f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814fbe29)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff8153952c)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81742965)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81c23730)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0aa81)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14721)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91c56)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93ea2)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94391)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b954b1)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff811b0aca)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811b2fb4)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811b4356)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff814264f0)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8153a270)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8154b2df)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff81556a90)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff81597d6f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff817c33b5)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81d365cd)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce261)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7501)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e576)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c60642)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60b31)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61cb1)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff811e2cda)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811e5418)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811e68a0)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8149fbff)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff815d1c2f)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff815e407f)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff815f3f20)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8163c55b)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff818fff5b)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81f02d92)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d63498)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6df38)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e0074e)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02ac6)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03064)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e042e4)
Location: include/linux/audit.h:208
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff81228bca)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8122b498)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8122c330)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff81534a9f)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8167fa5f)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8169337e)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff816a48b0)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff816f3dab)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81a599cb)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81dce37e)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2e138)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a628)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd556e)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd79c6)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7fc4)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd92c4)
Location: include/linux/audit.h:206
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8123f1ca)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff81241ab8)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff812429f0)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8156cc62)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff816b7b52)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff816cb8a0)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff816dcc00)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8172dedb)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81aa3ffb)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81e3ef7c)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f8e8)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a048)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205120e)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820536b6)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053cb4)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054f94)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8125903a)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8125b8d8)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8125c970)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff815a5462)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff816f3435)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81708560)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff81719b4b)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8176e83b)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81af69bb)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81efd8d9)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ba78)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff820673a8)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821239cc)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125ec2)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212649f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212787f)
Location: include/linux/audit.h:204
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
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
In kernel/audit.c (ffff8000101ec5c0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffff8000101ee750)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffff8000101ef83c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffff80001043e1fc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffff800010556bd4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffff8000105670b0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffff8000105760d8)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffff8000105acbc0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffff8000108632a4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffff800010bd58b4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd96dc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce383c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d6668c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d691e0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e08)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ab18)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (c042c224)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (c042e754)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c042fc78)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (c06049f4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (c070b9f0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c071b640)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (c07290ec)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (c075c464)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (c0968f78)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (c0cf052c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (c0de486c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c0ded1c4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (c0e65cfc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c0e678e8)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e6839c)
Location: include/linux/audit.h:173
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e690ac)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (c00000000025e040)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (c000000000261480)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c000000000262464)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (c000000000552ef8)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (c0000000006b40c0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c0000000006ca3f8)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (c0000000006df9a0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (c00000000072b028)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (c000000000902050)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (c000000000cb4ebc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb4a0)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c000000000e07380)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2850)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea6014)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6c2c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7f30)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffe000160c30)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffe000162828)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffe00016353c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffe0002d59d6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae766)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffe0003bcec4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffe0003c8ee6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffe0003f5222)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffe000539dfa)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffe00075f284)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082ad5e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffe0008323ea)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a144)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c340)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089ca86)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d59a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
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
In kernel/audit.c (ffffffff8116fbc3)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81171a11)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81172cd6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8136c46e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81460af4)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146fa1d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8147c7ed)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814ad02c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81655fbc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff818d9b30)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd51a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5c3a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36442)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38c6e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39549)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a249)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff81162d63)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81164bb1)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81165e76)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8135cefe)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81451524)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146043d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8146d20d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8149da4c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8163634c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81893970)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197a30a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81982a2a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3062)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f588e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f6169)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6e69)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8116d993)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff8116f7e1)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81170aa6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff81369f3e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8145cb94)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146babd)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8147888d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814a90cc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8168437c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8192ab60)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27f9a)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a306ba)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa22f2)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4b1e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa53f9)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa60f9)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In kernel/audit.c (ffffffff8117b17c)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff8117cfda)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117e2b6)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
```
In fs/proc/base.c (ffffffff8137d80e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81474334)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8148325d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8149033d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814c1adc)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8169e98d)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8194c230)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a335ca)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3bfba)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae662)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0e8e)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1799)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2499)
Location: include/linux/audit.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
</ul>

## Differences
