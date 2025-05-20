# Function: <code>audit_log_n_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81121f50)
Location: kernel/audit.c:1550
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/auditsc.c:audit_log_exit
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff81121f50-ffffffff8112205b: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129ea0)
Location: kernel/audit.c:1561
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/audit_tree.c:kill_rules
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff81129ea0-ffffffff81129fad: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133bc0)
Location: kernel/audit.c:1700
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff81133bc0-ffffffff81133ccd: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135090)
Location: kernel/audit.c:1879
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff81135090-ffffffff811351a6: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141de0)
Location: kernel/audit.c:1887
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff81141de0-ffffffff81141ef6: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811507a0)
Location: kernel/audit.c:1940
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
**Symbols:**

```
ffffffff811507a0-ffffffff811508be: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d440)
Location: kernel/audit.c:1937
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8115d440-ffffffff8115d558: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169b80)
Location: kernel/audit.c:1937
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81169b80-ffffffff81169c8c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175a20)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81175a20-ffffffff81175b2c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188180)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81188180-ffffffff8118828c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185510)
Location: kernel/audit.c:2036
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81185510-ffffffff8118561c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186510)
Location: kernel/audit.c:2036
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81186510-ffffffff81186619: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ae900)
Location: kernel/audit.c:2075
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811ae900-ffffffff811aea09: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e08c0)
Location: kernel/audit.c:2057
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811e08c0-ffffffff811e09fb: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226670)
Location: kernel/audit.c:2055
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81226670-ffffffff812267ab: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123cc50)
Location: kernel/audit.c:2055
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff8123cc50-ffffffff8123cd89: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256b60)
Location: kernel/audit.c:2073
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81256b60-ffffffff81256c99: audit_log_n_string (STB_GLOBAL)
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
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ea8e8)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffff8000101ea8e8-ffff8000101eaa28: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a5e4)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c042a5e4-c042a6fc: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025bc60)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c00000000025bc60-c00000000025be5c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f290)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffe00015f290-ffffffe00015f3a4: audit_log_n_string (STB_GLOBAL)
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
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e040)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8116e040-ffffffff8116e14c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811611e0)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff811611e0-ffffffff811612ec: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116be10)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8116be10-ffffffff8116bf1c: audit_log_n_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer *ab, const char *string, size_t slen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811795d0)
Location: kernel/audit.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/file.c:audit_file_mask
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff811795d0-ffffffff811796dc: audit_log_n_string (STB_GLOBAL)
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
