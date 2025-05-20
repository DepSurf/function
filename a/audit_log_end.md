# Function: <code>audit_log_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811210e0)
Location: kernel/audit.c:1960
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_config_change
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_seccomp
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff811210e0-ffffffff8112126f: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129020)
Location: kernel/audit.c:1981
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81129020-ffffffff811291af: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81132e40)
Location: kernel/audit.c:2120
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81132e40-ffffffff81132f21: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134400)
Location: kernel/audit.c:2287
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81134400-ffffffff811344fb: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811411c0)
Location: kernel/audit.c:2295
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff811411c0-ffffffff811412bb: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114fb50)
Location: kernel/audit.c:2337
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8114fb50-ffffffff8114fc4a: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c830)
Location: kernel/audit.c:2334
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8115c830-ffffffff8115c927: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81168f10)
Location: kernel/audit.c:2299
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81168f10-ffffffff8116900c: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81174db0)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81174db0-ffffffff81174eac: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186fb0)
Location: kernel/audit.c:2453
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_proctitle
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/bpf/syscall.c:bpf_prog_load
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81186fb0-ffffffff811870ae: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184320)
Location: kernel/audit.c:2470
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_proctitle
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/bpf/syscall.c:bpf_prog_load
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81184320-ffffffff8118441e: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811850f0)
Location: kernel/audit.c:2470
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - kernel/bpf/syscall.c:bpf_prog_load
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff811850f0-ffffffff811851ee: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ad4e0)
Location: kernel/audit.c:2509
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff811ad4e0-ffffffff811ad5de: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811e014c)
Location: kernel/audit.c:2574
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff811df1f0-ffffffff811df34e: audit_log_end.part.0 (STB_LOCAL)
ffffffff811df350-ffffffff811df372: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81225ebc)
Location: kernel/audit.c:2572
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81224e90-ffffffff81224fe8: audit_log_end.part.0 (STB_LOCAL)
ffffffff81225000-ffffffff81225022: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8123c49c)
Location: kernel/audit.c:2572
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8123b460-ffffffff8123b5b8: audit_log_end.part.0 (STB_LOCAL)
ffffffff8123b5d0-ffffffff8123b5f2: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8125637c)
Location: kernel/audit.c:2594
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_proctitle
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81255320-ffffffff81255478: audit_log_end.part.0 (STB_LOCAL)
ffffffff81255490-ffffffff812554b2: audit_log_end (STB_GLOBAL)
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
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e9a78)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffff8000101e9a78-ffff8000101e9be0: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0429918)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c0429918-c0429a18: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025aa10)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c00000000025aa10-c00000000025ab8c: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e766)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffe00015e766-ffffffe00015e878: audit_log_end (STB_GLOBAL)
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
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d3d0)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8116d3d0-ffffffff8116d4cc: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81160570)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81160570-ffffffff8116066c: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b1a0)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8116b1a0-ffffffff8116b29c: audit_log_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178990)
Location: kernel/audit.c:2301
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/lsm_audit.c:common_lsm_audit
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81178990-ffffffff81178a8c: audit_log_end (STB_GLOBAL)
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
