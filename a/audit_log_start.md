# Function: <code>audit_log_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811215e0)
Location: kernel/audit.c:1358
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_config_change
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_name
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
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811215e0-ffffffff81121aa9: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129530)
Location: kernel/audit.c:1369
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81129530-ffffffff811299e5: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811332b0)
Location: kernel/audit.c:1501
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811332b0-ffffffff81133705: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134870)
Location: kernel/audit.c:1685
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81134870-ffffffff81134bf9: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811415b0)
Location: kernel/audit.c:1693
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811415b0-ffffffff81141947: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:1747
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811524af-ffffffff811524cc: audit_log_start.cold.26 (STB_LOCAL)
ffffffff8114ff40-ffffffff811502d0: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8115cc61)
Location: kernel/audit.c:1744
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8115f157-ffffffff8115f174: audit_log_start.cold.26 (STB_LOCAL)
ffffffff8115cc10-ffffffff8115cf82: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81169650)
Location: kernel/audit.c:1744
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81169310-ffffffff81169643: audit_log_start.part.0 (STB_LOCAL)
ffffffff8116b746-ffffffff8116b763: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff81169650-ffffffff811696a4: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811754f0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811751b0-ffffffff811754e3: audit_log_start.part.0 (STB_LOCAL)
ffffffff81177626-ffffffff81177643: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff811754f0-ffffffff81175544: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81187c2f)
Location: kernel/audit.c:1821
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81187440-ffffffff8118776f: audit_log_start.part.0 (STB_LOCAL)
ffffffff8118a29a-ffffffff8118a2b7: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff81187770-ffffffff811877c4: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81184f9f)
Location: kernel/audit.c:1832
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81184790-ffffffff81184ae0: audit_log_start.part.0 (STB_LOCAL)
ffffffff81be4920-ffffffff81be493d: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff81184ae0-ffffffff81184b34: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81185e2f)
Location: kernel/audit.c:1832
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81185570-ffffffff81185964: audit_log_start.part.0 (STB_LOCAL)
ffffffff81bd6781-ffffffff81bd679e: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff81185970-ffffffff811859c4: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811ae21f)
Location: kernel/audit.c:1869
Inline: True
Inline callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811ad960-ffffffff811add45: audit_log_start.part.0 (STB_LOCAL)
ffffffff81cb34d5-ffffffff81cb34f2: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff811add50-ffffffff811adda4: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:1856
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81e64309-ffffffff81e64326: audit_log_start.cold (STB_LOCAL)
ffffffff811df9c0-ffffffff811dfd6f: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812256d0)
Location: kernel/audit.c:1854
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff812256d0-ffffffff81225a94: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123bcc0)
Location: kernel/audit.c:1854
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8123bcc0-ffffffff8123c086: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81255b90)
Location: kernel/audit.c:1872
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81255b90-ffffffff81255f56: audit_log_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffff8000101e9f18)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffff8000101e9f18-ffff8000101ea2b0: audit_log_start.part.0 (STB_LOCAL)
ffff8000101ea2b0-ffff8000101ea328: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (c0429d18)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
c0429d18-c042a0a0: audit_log_start.part.0 (STB_LOCAL)
c042a0a0-c042a104: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (c00000000025afa0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
c00000000025afa0-c00000000025b43c: audit_log_start.part.0 (STB_LOCAL)
c00000000025b440-c00000000025b4e8: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffe00015ead0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffe00015ead0-ffffffe00015edaa: audit_log_start.part.0 (STB_LOCAL)
ffffffe00015edaa-ffffffe00015ee10: audit_log_start (STB_GLOBAL)
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
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116db10)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8116d7d0-ffffffff8116db03: audit_log_start.part.0 (STB_LOCAL)
ffffffff8116fc46-ffffffff8116fc63: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff8116db10-ffffffff8116db64: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81160cb0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81160970-ffffffff81160ca3: audit_log_start.part.0 (STB_LOCAL)
ffffffff81162de6-ffffffff81162e03: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff81160cb0-ffffffff81160d04: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116b8e0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8116b5a0-ffffffff8116b8d3: audit_log_start.part.0 (STB_LOCAL)
ffffffff8116da16-ffffffff8116da33: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff8116b8e0-ffffffff8116b934: audit_log_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct audit_buffer *audit_log_start(struct audit_context *ctx, gfp_t gfp_mask, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811790b0)
Location: kernel/audit.c:1746
Inline: True
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_common_recv_msg
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
  - drivers/tty/tty_audit.c:tty_audit_log
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81178d90-ffffffff811790a2: audit_log_start.part.0 (STB_LOCAL)
ffffffff8117b206-ffffffff8117b223: audit_log_start.part.0.cold (STB_LOCAL)
ffffffff811790b0-ffffffff81179104: audit_log_start (STB_GLOBAL)
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
