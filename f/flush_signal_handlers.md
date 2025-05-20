# Function: <code>flush_signal_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dce0)
Location: kernel/signal.c:479
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8108dce0-ffffffff8108dd2f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090d60)
Location: kernel/signal.c:479
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81090d60-ffffffff81090daf: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095ce0)
Location: kernel/signal.c:481
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81095ce0-ffffffff81095d2f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092c90)
Location: kernel/signal.c:487
Inline: False
Direct callers:
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81092c90-ffffffff81092cdf: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099b70)
Location: kernel/signal.c:489
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81099b70-ffffffff81099bbf: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109db40)
Location: kernel/signal.c:491
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8109db40-ffffffff8109db8f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5e50)
Location: kernel/signal.c:523
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a5e50-ffffffff810a5e9f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aab20)
Location: kernel/signal.c:533
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810aab20-ffffffff810aab6f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1120)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b1120-ffffffff810b116f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba7c0)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810ba7c0-ffffffff810ba80f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5a80)
Location: kernel/signal.c:539
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b5a80-ffffffff810b5acf: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7680)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b7680-ffffffff810b76cf: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c9ad0)
Location: kernel/signal.c:539
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810c9ad0-ffffffff810c9b1f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1520)
Location: kernel/signal.c:539
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810e1520-ffffffff810e157b: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811017d0)
Location: kernel/signal.c:539
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811017d0-ffffffff8110182b: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110d960)
Location: kernel/signal.c:540
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8110d960-ffffffff8110d9de: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811172a0)
Location: kernel/signal.c:531
Inline: False
Direct callers:
  - kernel/fork.c:copy_sighand
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:begin_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811172a0-ffffffff8111731e: flush_signal_handlers (STB_GLOBAL)
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
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010cce8)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffff80001010cce8-ffff80001010cd44: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364f68)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c0364f68-c0364fc8: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153c40)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c000000000153c40-c000000000153c8c: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce2b6)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffe0000ce2b6-ffffffe0000ce304: flush_signal_handlers (STB_GLOBAL)
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
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab490)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810ab490-ffffffff810ab4df: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099e30)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81099e30-ffffffff81099e7f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa9f0)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810aa9f0-ffffffff810aaa3f: flush_signal_handlers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct *t, int force_default);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2ad0)
Location: kernel/signal.c:538
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:setup_new_exec
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810b2ad0-ffffffff810b2b1f: flush_signal_handlers (STB_GLOBAL)
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
