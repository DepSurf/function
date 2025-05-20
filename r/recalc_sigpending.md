# Function: <code>recalc_sigpending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d160)
Location: kernel/signal.c:158
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:do_sigtimedwait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8108d160-ffffffff8108d1ab: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090320)
Location: kernel/signal.c:158
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81090320-ffffffff8109036b: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810952a0)
Location: kernel/signal.c:158
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810952a0-ffffffff810952e7: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810922d0)
Location: kernel/signal.c:164
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810922d0-ffffffff81092317: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099160)
Location: kernel/signal.c:166
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81099160-ffffffff810991a7: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cd00)
Location: kernel/signal.c:167
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8109cd00-ffffffff8109cd4f: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4c40)
Location: kernel/signal.c:172
Inline: True
Direct callers:
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a4c40-ffffffff810a4c8f: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9940)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a9940-ffffffff810a9995: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aff30)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810aff30-ffffffff810aff85: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b82d0)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - fs/io_uring.c:io_cqring_wait
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b82d0-ffffffff810b834e: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3580)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b3580-ffffffff810b35fe: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4bb0)
Location: kernel/signal.c:181
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b4bb0-ffffffff810b4c24: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6d80)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810c6d80-ffffffff810c6df4: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dea30)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810dea30-ffffffff810deac2: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ff0d0)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810ff0d0-ffffffff810ff15a: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110b0f0)
Location: kernel/signal.c:183
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8110b0f0-ffffffff8110b17a: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114670)
Location: kernel/signal.c:174
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81114670-ffffffff811146fa: recalc_sigpending (STB_GLOBAL)
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
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b3a0)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffff80001010b3a0-ffff80001010b41c: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363e4c)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c0363e4c-c0363ec4: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152210)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c000000000152210-c0000000001522b8: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd650)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffe0000cd650-ffffffe0000cd6c8: recalc_sigpending (STB_GLOBAL)
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
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa2a0)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810aa2a0-ffffffff810aa2f5: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098c50)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81098c50-ffffffff81098ca5: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9800)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a9800-ffffffff810a9855: recalc_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1b90)
Location: kernel/signal.c:182
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b1b90-ffffffff810b1be5: recalc_sigpending (STB_GLOBAL)
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
