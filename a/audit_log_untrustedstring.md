# Function: <code>audit_log_untrustedstring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81122110)
Location: kernel/audit.c:1624
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_task
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/net.c:audit_unix_addr
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81122110-ffffffff8112213d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a72b)
Location: kernel/audit.c:1635
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/net.c:audit_unix_addr
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8112a040-ffffffff8112a06d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8113444b)
Location: kernel/audit.c:1774
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/net.c:audit_unix_addr
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81133d60-ffffffff81133d8d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135240)
Location: kernel/audit.c:1953
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/net.c:audit_unix_addr
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string_op
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81135240-ffffffff8113526d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141f90)
Location: kernel/audit.c:1961
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/net.c:audit_unix_addr
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string_op
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81141f90-ffffffff81141fbd: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150950)
Location: kernel/audit.c:2014
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/ima/ima_policy.c:ima_log_string_op
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81150950-ffffffff8115097d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d5f0)
Location: kernel/audit.c:2011
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8115d5f0-ffffffff8115d61d: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169d10)
Location: kernel/audit.c:2011
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81169d10-ffffffff81169d3f: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175bb0)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81175bb0-ffffffff81175bdf: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188350)
Location: kernel/audit.c:2093
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81188350-ffffffff8118837f: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811856b0)
Location: kernel/audit.c:2110
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811856b0-ffffffff811856df: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811866a0)
Location: kernel/audit.c:2110
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811866a0-ffffffff811866cf: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aea90)
Location: kernel/audit.c:2149
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811aea90-ffffffff811aeabf: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0ac0)
Location: kernel/audit.c:2131
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811e0ac0-ffffffff811e0af9: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812268a0)
Location: kernel/audit.c:2129
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff812268a0-ffffffff812268d9: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ce80)
Location: kernel/audit.c:2129
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8123ce80-ffffffff8123ceb9: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256d90)
Location: kernel/audit.c:2147
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/task.c:audit_ns_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81256d90-ffffffff81256dc9: audit_log_untrustedstring (STB_GLOBAL)
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
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eab38)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffff8000101eab38-ffff8000101eab78: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a7c8)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
c042a7c8-c042a800: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025bf40)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
c00000000025bf40-c00000000025bf94: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f85c)
Location: kernel/audit.c:2013
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffe00015f48a-ffffffe00015f4c8: audit_log_untrustedstring (STB_GLOBAL)
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
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e1d0)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8116e1d0-ffffffff8116e1ff: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161370)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81161370-ffffffff8116139f: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116bfa0)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8116bfa0-ffffffff8116bfcf: audit_log_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer *ab, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179760)
Location: kernel/audit.c:2013
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/smack/smack_access.c:smack_log_callback
  - security/smack/smack_access.c:smack_log_callback
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/capability.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/policy_unpack.c:audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/apparmor/mount.c:audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81179760-ffffffff8117978f: audit_log_untrustedstring (STB_GLOBAL)
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
