# Function: <code>audit_log_string</code>

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
In kernel/audit.c (ffffffff811221de)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In kernel/auditfilter.c (ffffffff81123dfb)
Location: include/linux/audit.h:549
Inline: True
```
```
In kernel/auditsc.c (ffffffff81126735)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81129ab7)
Location: include/linux/audit.h:549
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff8112a831)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff8112aba8)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
```
```
In security/apparmor/audit.c (ffffffff81376a65)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81377b7a)
Location: include/linux/audit.h:549
Inline: True
```
```
In security/apparmor/file.c (ffffffff813879b4)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff813904ba)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff81396577)
Location: include/linux/audit.h:549
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff8112a10e)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In kernel/auditfilter.c (ffffffff8112bddb)
Location: include/linux/audit.h:552
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81131c67)
Location: include/linux/audit.h:552
Inline: True
```
```
In kernel/audit_fsnotify.c (ffffffff81132a10)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff81132da0)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
```
```
In security/apparmor/audit.c (ffffffff813af525)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff813b087a)
Location: include/linux/audit.h:552
Inline: True
```
```
In security/apparmor/file.c (ffffffff813c2474)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff813cba6a)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff813d22f7)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff81133e2e)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff813c66a5)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff813c79fa)
Location: include/linux/audit.h:552
Inline: True
```
```
In security/apparmor/file.c (ffffffff813d9914)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff813e30ea)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff813e9a17)
Location: include/linux/audit.h:552
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff811352fe)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff813dc535)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff813dd210)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff813eaad4)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff813f158a)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff813f5e17)
Location: include/linux/audit.h:582
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff8114204e)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81402fa5)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81403d6b)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff81412404)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814195aa)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff8141df17)
Location: include/linux/audit.h:584
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff811509fe)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81433f55)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81434e70)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff814447b4)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff8144b9da)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
```
In security/integrity/integrity_audit.c (ffffffff814501c7)
Location: include/linux/audit.h:595
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
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
In kernel/audit.c (ffffffff8115d6b2)
Location: include/linux/audit.h:594
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81450c55)
Location: include/linux/audit.h:594
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81451a60)
Location: include/linux/audit.h:594
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff81461689)
Location: include/linux/audit.h:594
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff8146894a)
Location: include/linux/audit.h:594
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff81169ddd)
Location: include/linux/audit.h:664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff8147e723)
Location: include/linux/audit.h:664
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff8147f470)
Location: include/linux/audit.h:664
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff8148e95a)
Location: include/linux/audit.h:664
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff81495989)
Location: include/linux/audit.h:664
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff81175c7d)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81498423)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81499170)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff814a881a)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814af8b9)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void audit_log_string(struct audit_buffer *ab, const char *buf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118841d)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
Direct callers:
  - kernel/audit.c:audit_log_d_path
```
```
In security/lsm_audit.c (ffffffff814dad6f)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In security/apparmor/audit.c (ffffffff814f05d3)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff814f1a2e)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff81505dfa)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff8150ecd9)
Location: include/linux/audit.h:693
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81188290-ffffffff811882ba: audit_log_string (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eac20)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffff80001058df70)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffff80001058ee40)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffff80001059f038)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffff8000105a6fe8)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (c042a890)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (c073ee1c)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (c073fca4)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (c074fd14)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (c0756fbc)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (c00000000025c070)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (c000000000700950)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (c000000000701e00)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (c000000000718cd8)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (c0000000007237c4)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffe00015f578)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffe0003dbfe2)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffe0003dcb62)
Location: include/linux/audit.h:657
Inline: True
```
```
In security/apparmor/file.c (ffffffe0003ea3be)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffe0003f08c6)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff8116e29d)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81490a03)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81491750)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff814a0dfa)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814a7e99)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff8116143d)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff81481423)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff81482170)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff8149181a)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814988b9)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff8116c06d)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff8148caa3)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff8148d7f0)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff8149ce9a)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814a3f39)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
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
In kernel/audit.c (ffffffff8117982d)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:audit_log_d_path
```
```
In security/apparmor/audit.c (ffffffff814a48e3)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/audit.c:audit_pre
```
```
In security/apparmor/ipc.c (ffffffff814a5700)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_signal_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
  - security/apparmor/ipc.c:audit_ptrace_mask
```
```
In security/apparmor/file.c (ffffffff814b543a)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/file.c:audit_file_mask
```
```
In security/apparmor/net.c (ffffffff814bc7c9)
Location: include/linux/audit.h:657
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
