# Function: <code>get_task_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *get_task_comm(char *buf, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212700)
Location: fs/exec.c:1070
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:SyS_prctl
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
```
**Symbols:**

```
ffffffff81212700-ffffffff8121274b: get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *get_task_comm(char *buf, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812391e0)
Location: fs/exec.c:1217
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:SyS_prctl
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff812391e0-ffffffff8123922c: get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *get_task_comm(char *buf, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124be90)
Location: fs/exec.c:1224
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:SyS_prctl
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff8124be90-ffffffff8124bedc: get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *get_task_comm(char *buf, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81257fb0)
Location: fs/exec.c:1250
Inline: False
Direct callers:
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/sys.c:SyS_prctl
  - kernel/auditsc.c:audit_log_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - security/yama/yama_lsm.c:report_access
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81257fb0-ffffffff81257ffc: get_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
