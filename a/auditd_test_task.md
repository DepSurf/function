# Function: <code>auditd_test_task</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133e90)
Location: kernel/audit.c:216
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_signal_info
```
**Symbols:**

```
ffffffff81133e90-ffffffff81133ec0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140c50)
Location: kernel/audit.c:216
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_signal_info
```
**Symbols:**

```
ffffffff81140c50-ffffffff81140c80: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f5c0)
Location: kernel/audit.c:229
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff8114f5c0-ffffffff8114f5f0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c2a0)
Location: kernel/audit.c:225
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff8115c2a0-ffffffff8115c2d0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b671)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff81168970-ffffffff811689a0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81177551)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff81174810-ffffffff81174840: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118a1c1)
Location: kernel/audit.c:213
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81186880-ffffffff811868b0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811874d7)
Location: kernel/audit.c:218
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81183b80-ffffffff81183bc0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188547)
Location: kernel/audit.c:218
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff81184ab0-ffffffff81184af0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0a67)
Location: kernel/audit.c:218
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff811acdd0-ffffffff811ace10: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2c6a)
Location: kernel/audit.c:220
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_filter_syscall
  - kernel/auditsc.c:audit_filter_uring
```
**Symbols:**

```
ffffffff811de9f0-ffffffff811dea40: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228b5a)
Location: kernel/audit.c:220
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff812245c0-ffffffff81224610: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123f15a)
Location: kernel/audit.c:220
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8123ab90-ffffffff8123abe0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258fca)
Location: kernel/audit.c:219
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81254a50-ffffffff81254aa0: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec558)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffff8000101e92c0-ffff8000101e9318: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042c1a8)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
c0429234-c0429278: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025dfc0)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
c00000000025a040-c00000000025a088: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe000160bea)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffe00015e0f2-ffffffe00015e12e: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116fb71)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff8116ce30-ffffffff8116ce60: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162d11)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff8115ffd0-ffffffff81160000: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d941)
Location: kernel/audit.c:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
Direct callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff8116ac00-ffffffff8116ac30: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int auditd_test_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811783d0)
Location: kernel/audit.c:212
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/auditsc.c:__audit_syscall_entry
```
**Symbols:**

```
ffffffff811783d0-ffffffff81178418: auditd_test_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
