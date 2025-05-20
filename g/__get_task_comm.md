# Function: <code>__get_task_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a200)
Location: fs/exec.c:1231
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:SyS_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8127a200-ffffffff8127a251: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a1930)
Location: fs/exec.c:1235
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:do_futex
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812a1930-ffffffff812a1981: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6ea0)
Location: fs/exec.c:1239
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812b6ea0-ffffffff812b6ef1: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d3c00)
Location: fs/exec.c:1240
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812d3c00-ffffffff812d3c50: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e5790)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812e5790-ffffffff812e57e0: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131d150)
Location: fs/exec.c:1306
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_tiocsserial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8131d150-ffffffff8131d1a0: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813286a0)
Location: fs/exec.c:1218
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_tiocsserial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff813286a0-ffffffff813286f0: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132e5d0)
Location: fs/exec.c:1210
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8132e5d0-ffffffff8132e620: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137bde0)
Location: fs/exec.c:1210
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8137bde0-ffffffff8137be30: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813f9cd0)
Location: fs/exec.c:1217
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/kthread.c:get_kthread_comm
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff813f9cd0-ffffffff813f9d28: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814835b0)
Location: fs/exec.c:1212
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/kthread.c:get_kthread_comm
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff814835b0-ffffffff81483608: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b81d0)
Location: fs/exec.c:1215
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/kthread.c:get_kthread_comm
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - net/wireless/wext-core.c:wireless_warn_cfg80211_wext
```
**Symbols:**

```
ffffffff814b81d0-ffffffff814b8228: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ea6e0)
Location: fs/exec.c:1230
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__do_sys_prctl
  - kernel/kthread.c:get_kthread_comm
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_message
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - net/wireless/wext-core.c:wireless_warn_cfg80211_wext
```
**Symbols:**

```
ffffffff814ea6e0-ffffffff814ea738: __get_task_comm (STB_GLOBAL)
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
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c560)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffff80001038c560-ffff80001038c600: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0573e30)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__se_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
c0573e30-c0573e8c: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000485460)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__se_sys_prctl
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
c000000000485460-c000000000485540: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025e09e)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__se_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffe00025e09e-ffffffe00025e128: __get_task_comm (STB_GLOBAL)
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
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ddd70)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812ddd70-ffffffff812dddc0: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ce9f0)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812ce9f0-ffffffff812cea40: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dbb80)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812dbb80-ffffffff812dbbd0: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *__get_task_comm(char *buf, size_t buf_size, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812eb930)
Location: fs/exec.c:1241
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/futex.c:futex_wake_op
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:proc_task_name
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff812eb930-ffffffff812eb97e: __get_task_comm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
