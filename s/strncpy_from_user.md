# Function: <code>strncpy_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81419c10)
Location: lib/strncpy_from_user.c:99
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:SyS_delete_module
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81419c10-ffffffff81419d0b: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff814619e0)
Location: lib/strncpy_from_user.c:100
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:SyS_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff814619e0-ffffffff81461b23: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81480500)
Location: lib/strncpy_from_user.c:101
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:SyS_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81480500-ffffffff81480661: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff814897a0)
Location: lib/strncpy_from_user.c:101
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:SyS_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff814897a0-ffffffff81489909: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff814c58f0)
Location: lib/strncpy_from_user.c:102
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:SyS_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff814c58f0-ffffffff814c5a57: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff814f67d0)
Location: lib/strncpy_from_user.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:fetch_memory_string
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff814f67d0-ffffffff814f6948: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff8150abe0)
Location: lib/strncpy_from_user.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff8150abe0-ffffffff8150ad8f: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81539350)
Location: lib/strncpy_from_user.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81539350-ffffffff815394b7: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff8155a170)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff8155a170-ffffffff8155a2bd: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff815e3aa0)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff815e3aa0-ffffffff815e3bdb: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81607f20)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81607f20-ffffffff816080bd: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff815eac30)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/tty/vt/vt.c:con_font_op
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff815eac30-ffffffff815ead66: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81657130)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/tty/vt/vt.c:con_font_op
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81657130-ffffffff81657266: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff8176e970)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr_copy
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - io_uring/io_uring.c:__io_getxattr_prep
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/tty/vt/vt.c:con_font_op
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff8176e970-ffffffff8176eac7: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff8189e280)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr_copy
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - io_uring/xattr.c:__io_getxattr_prep
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/tty/vt/vt.c:con_font_op
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff8189e280-ffffffff8189e3d7: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff818e0840)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr_copy
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - io_uring/xattr.c:__io_getxattr_prep
  - drivers/tty/vt/vt.c:con_font_op
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff818e0840-ffffffff818e09b0: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81927380)
Location: lib/strncpy_from_user.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__do_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_user_nofault
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr_copy
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - io_uring/xattr.c:__io_getxattr_prep
  - drivers/tty/vt/vt.c:con_font_op
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81927380-ffffffff819274f0: strncpy_from_user (STB_GLOBAL)
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
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffff800010666c78)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__arm64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffff800010666c78-ffff800010666d54: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (c080f5c4)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__se_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
c080f5c4-c080f7ac: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (c00000000081c5b0)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__se_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
c00000000081c5b0-c00000000081c828: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffe000492a38)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__se_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffe000492a38-ffffffe000492bae: strncpy_from_user (STB_GLOBAL)
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
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81552750)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81552750-ffffffff8155289d: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff81542a30)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff81542a30-ffffffff81542b7d: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff8154e490)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff8154e490-ffffffff8154e5dd: strncpy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int strncpy_from_user(char *dst, const char *src, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffff815682e0)
Location: lib/strncpy_from_user.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - mm/maccess.c:strncpy_from_unsafe_user
  - fs/xattr.c:removexattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - drivers/tty/vt/vt.c:con_font_op
```
**Symbols:**

```
ffffffff815682e0-ffffffff8156842d: strncpy_from_user (STB_GLOBAL)
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
