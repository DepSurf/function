# Function: <code>audit_log_n_untrustedstring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811220c0)
Location: kernel/audit.c:1607
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff811220c0-ffffffff8112210f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129ff0)
Location: kernel/audit.c:1618
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81129ff0-ffffffff8112a03f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133d10)
Location: kernel/audit.c:1757
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81133d10-ffffffff81133d5f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811351f0)
Location: kernel/audit.c:1936
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff811351f0-ffffffff8113523f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141f40)
Location: kernel/audit.c:1944
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81141f40-ffffffff81141f8f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150900)
Location: kernel/audit.c:1997
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81150900-ffffffff8115094f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d5a0)
Location: kernel/audit.c:1994
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8115d5a0-ffffffff8115d5ef: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169cd0)
Location: kernel/audit.c:1994
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81169cd0-ffffffff81169d10: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175b70)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81175b70-ffffffff81175bb0: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188300)
Location: kernel/audit.c:2076
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_proctitle
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81188300-ffffffff8118834f: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185660)
Location: kernel/audit.c:2093
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_proctitle
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81185660-ffffffff811856af: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186660)
Location: kernel/audit.c:2093
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
```
**Symbols:**

```
ffffffff81186660-ffffffff811866a0: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aea50)
Location: kernel/audit.c:2132
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff811aea50-ffffffff811aea90: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0a50)
Location: kernel/audit.c:2114
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff811e0a50-ffffffff811e0ab8: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226820)
Location: kernel/audit.c:2112
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81226820-ffffffff81226888: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ce00)
Location: kernel/audit.c:2112
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff8123ce00-ffffffff8123ce68: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256d10)
Location: kernel/audit.c:2130
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_proctitle
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81256d10-ffffffff81256d78: audit_log_n_untrustedstring (STB_GLOBAL)
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
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eaa98)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffff8000101eaa98-ffff8000101eab38: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a760)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
```
**Symbols:**

```
c042a760-c042a7c8: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025bed0)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
c00000000025bed0-c00000000025bf34: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f406)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_key
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffe00015f406-ffffffe00015f48a: audit_log_n_untrustedstring (STB_GLOBAL)
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
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e190)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff8116e190-ffffffff8116e1d0: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161330)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81161330-ffffffff81161370: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116bf60)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff8116bf60-ffffffff8116bfa0: audit_log_n_untrustedstring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_n_untrustedstring(struct audit_buffer *ab, const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179720)
Location: kernel/audit.c:1996
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_untrustedstring
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81179720-ffffffff81179760: audit_log_n_untrustedstring (STB_GLOBAL)
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
