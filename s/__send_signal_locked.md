# Function: <code>__send_signal_locked</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1078
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff810e0a20-ffffffff810e0ec9: __send_signal_locked (STB_LOCAL)
ffffffff81e5404f-ffffffff81e54105: __send_signal_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1079
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff81100c10-ffffffff811010ae: __send_signal_locked (STB_LOCAL)
ffffffff82056108-ffffffff820561be: __send_signal_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1083
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff8110cd10-ffffffff8110d20a: __send_signal_locked (STB_LOCAL)
ffffffff820d4698-ffffffff820d4745: __send_signal_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo *info, struct task_struct *t, enum pid_type type, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1073
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_pid_usb_asyncio
```
**Symbols:**

```
ffffffff811166f0-ffffffff81116bea: __send_signal_locked (STB_LOCAL)
ffffffff821af591-ffffffff821af63e: __send_signal_locked.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
