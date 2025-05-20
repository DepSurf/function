# Function: <code>audit_get_sessionid</code>

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
In kernel/audit.c (ffffffff81122225)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81123da6)
Location: include/linux/audit.h:237
Inline: True
```
```
In kernel/auditsc.c (ffffffff81126b00)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff81129a8f)
Location: include/linux/audit.h:237
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8112a804)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:237
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff8134ac70)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/selinux/ss/services.c (ffffffff813598aa)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:237
Inline: True
```
```
In security/integrity/integrity_audit.c (ffffffff81396506)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff814ece98)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8171d8b2)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b149e)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff817b890e)
Location: include/linux/audit.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:237
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:237
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:237
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
In kernel/audit.c (ffffffff8112a155)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff8112bd86)
Location: include/linux/audit.h:340
Inline: True
```
```
In kernel/auditsc.c (ffffffff8112ec10)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff81131c3f)
Location: include/linux/audit.h:340
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff811329e3)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff81381436)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8138f84a)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In security/integrity/integrity_audit.c (ffffffff813d2286)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8153de84)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81786182)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181eb6e)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81825cce)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:340
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
In kernel/audit.c (ffffffff81133e75)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81135aa6)
Location: include/linux/audit.h:340
Inline: True
```
```
In kernel/auditsc.c (ffffffff81138950)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff8113b9ab)
Location: include/linux/audit.h:340
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8113c743)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff81397eb6)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff813a646a)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In security/integrity/integrity_audit.c (ffffffff813e99a6)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8156a4d4)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff817b3742)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff818503ee)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818575ce)
Location: include/linux/audit.h:340
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:340
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:340
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
In kernel/audit.c (ffffffff81135395)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81137079)
Location: include/linux/audit.h:338
Inline: True
```
```
In kernel/auditsc.c (ffffffff81139f80)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff8113d05b)
Location: include/linux/audit.h:338
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8113dde4)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:338
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff813ae388)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff813bcec3)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:338
Inline: True
```
```
In security/integrity/integrity_audit.c (ffffffff813f5da6)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8157eafe)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff817d20c3)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187413e)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff8187af5e)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:338
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:338
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:338
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:338
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
In kernel/audit.c (ffffffff81142095)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditfilter.c (ffffffff81143d79)
Location: include/linux/audit.h:330
Inline: True
```
```
In kernel/auditsc.c (ffffffff81146c40)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff81149e1b)
Location: include/linux/audit.h:330
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8114abb4)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (0)
Location: include/linux/audit.h:330
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff813d4444)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff813e3033)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (0)
Location: include/linux/audit.h:330
Inline: True
```
```
In security/integrity/integrity_audit.c (ffffffff8141dea6)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff815e366e)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8184c356)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f46ae)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818fbb3e)
Location: include/linux/audit.h:330
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/audit.h:330
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:330
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/audit.h:330
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/audit.h:330
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
In kernel/audit.c (ffffffff81150a5f)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff81155606)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/audit_watch.c (ffffffff8115881b)
Location: include/linux/audit.h:334
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8115960b)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/proc/base.c (ffffffff8131ca84)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81404a88)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8141379c)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814205f5)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8145016e)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8161c940)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8189918d)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aedd)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81952bcd)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9f11)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc699)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcf75)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdcf5)
Location: include/linux/audit.h:334
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
In kernel/audit.c (ffffffff8115d6ff)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff811629b6)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In fs/proc/base.c (ffffffff813337c4)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81420ae8)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8142fcc9)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8143c836)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8146d14e)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81639bc0)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff818bb62f)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d97d)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819857dd)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f11e1)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f38e9)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f41b5)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4e95)
Location: include/linux/audit.h:333
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
In kernel/audit.c (ffffffff8116b4af)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff8116e841)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8135b7d4)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8144e6de)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8145d675)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8146a43c)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8149a848)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8166dee5)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8190754f)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6dc4)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819ef604)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60491)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62d19)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63627)
Location: include/linux/audit.h:179
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64357)
Location: include/linux/audit.h:179
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
In kernel/audit.c (ffffffff8117738f)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff8117a6c1)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff81373c24)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81468506)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81477425)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8148421c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814b4a48)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81690555)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81939b36)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1dea4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a265c4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a970c1)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a998f9)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a1d7)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9aed7)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffff8118a0f1)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff8118d6e1)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff813bbd96)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814bc356)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814cc894)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814d7942)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff81513f98)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81742c95)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81a0f0d6)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0fdfb)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1715b)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92ef1)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95130)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95607)
Location: include/linux/audit.h:191
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b966d7)
Location: include/linux/audit.h:191
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
In kernel/audit.c (ffffffff81187401)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff8118a881)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff813cd956)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814d9e3b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814ea10c)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814f4ec2)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff815310f8)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff8175eb3e)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81c31421)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1cd1b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2552b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2b41)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4d90)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5257)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6347)
Location: include/linux/audit.h:209
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
In kernel/audit.c (ffffffff81188341)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff8118b731)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff813d48e6)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff814e12e2)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814f0d0c)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff814fbe32)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff81539528)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff8174297e)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81c23706)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0aa9b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1473b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91c65)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93eb9)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b943ae)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b954ce)
Location: include/linux/audit.h:209
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
In kernel/audit.c (ffffffff811b0861)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff811b4361)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff81426226)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8153a262)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8154b2dc)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff81556a99)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_netlabel_audit_set
```
```
In security/integrity/integrity_audit.c (ffffffff81597d56)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff817c33ce)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81d365a3)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce27b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd751b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e585)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c60659)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60b4e)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61cce)
Location: include/linux/audit.h:209
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
In kernel/audit.c (ffffffff811e2a3e)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff811e68a0)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8149f6b5)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff815d1c21)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff815e4067)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff815f3f20)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8163c542)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff818fff8f)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81f02d66)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d634b4)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6df54)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e0074e)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02ac6)
Location: include/linux/audit.h:213
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
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e042e4)
Location: include/linux/audit.h:213
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
In kernel/audit.c (ffffffff8122891e)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff8122c330)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff81534505)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8167fa51)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81693366)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff816a48b0)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff816f3d92)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81a599ff)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81dce352)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2e154)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a644)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd556e)
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd79c6)
Location: include/linux/audit.h:211
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
Location: include/linux/audit.h:211
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd92c4)
Location: include/linux/audit.h:211
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
In kernel/audit.c (ffffffff8123ef1e)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff812429f0)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8156c6c8)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff816b7b44)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff816cb888)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff816dcc00)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8172dec2)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81aa4037)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81e3ef50)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f904)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a064)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205120e)
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820536b6)
Location: include/linux/audit.h:210
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
Location: include/linux/audit.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054f94)
Location: include/linux/audit.h:210
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
In kernel/audit.c (ffffffff81258d8f)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditsc.c (ffffffff8125c970)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff815a4ec8)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff816f3427)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81708548)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff81719b4b)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8176e822)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/tty/tty_audit.c (ffffffff81af69f7)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81efd8ad)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ba94)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff820673c4)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821239cc)
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125ec2)
Location: include/linux/audit.h:209
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
Location: include/linux/audit.h:209
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212787f)
Location: include/linux/audit.h:209
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
In kernel/audit.c (ffff8000101ec338)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffff8000101ef83c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffff80001043dd94)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffff800010556bd8)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffff8000105670b4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffff8000105760e4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffff8000105acbc4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffff8000108632b0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffff800010bd58e4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd96f0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3850)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d667c0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/audit.h:178
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e30)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ab40)
Location: include/linux/audit.h:178
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
In kernel/audit.c (c042bf60)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (c042fc78)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (c06042d0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (c070ba04)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c071b644)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (c07290f0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (c075c478)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (c0968fb4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (c0cf0568)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (c0de4894)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c0ded1ec)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (c0e65db0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (c0e678f4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e683a8)
Location: include/linux/audit.h:178
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e690b8)
Location: include/linux/audit.h:178
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
In kernel/audit.c (c00000000025dd08)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (c000000000262464)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (c0000000005529e0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (c0000000006b40c8)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c0000000006ca400)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (c0000000006df9a4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (c00000000072b030)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (c000000000902064)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (c000000000cb4ef0)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb4bc)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c000000000e0739c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2864)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea6030)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6c54)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7f58)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffe000160a62)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffe00016353c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffe0002d588c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae76e)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffe0003bcecc)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffe0003c8eea)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffe0003f5222)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffe000539dec)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffe00075f284)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082ad72)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffe0008323fe)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a156)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c35c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089ca9a)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d5ae)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffff8116f9af)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff81172ce1)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8136c204)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81460ae6)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146fa05)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8147c7fc)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814ad028)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81655fd5)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff818d9b06)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd534)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5c54)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36451)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38c89)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39567)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a267)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffff81162b4f)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff81165e81)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8135cc94)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81451516)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81460425)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8146d21c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff8149da48)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81636365)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff81893946)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197a324)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81982a44)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3071)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f58a9)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f6187)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6e87)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffff8116d77f)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff81170ab1)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff81369cd4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff8145cb86)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146baa5)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8147889c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814a90c8)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff81684395)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8192ab36)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27fb4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a306d4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2301)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4b39)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5417)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6117)
Location: include/linux/audit.h:178
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
In kernel/audit.c (ffffffff8117af6f)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
```
```
In kernel/auditsc.c (ffffffff8117e2c1)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In fs/proc/base.c (ffffffff8137d5a4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_sessionid_read
```
```
In security/selinux/selinuxfs.c (ffffffff81474326)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81483245)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/smack/smackfs.c (ffffffff8149034c)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/integrity/integrity_audit.c (ffffffff814c1ad8)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In drivers/tty/tty_audit.c (ffffffff8169e9a7)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/core/dev.c (ffffffff8194c206)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a335e4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3bfd4)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae671)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0ea9)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab17b7)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab24b7)
Location: include/linux/audit.h:178
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
</ul>

## Differences
