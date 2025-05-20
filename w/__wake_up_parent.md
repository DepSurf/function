# Function: <code>__wake_up_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810844b0)
Location: kernel/exit.c:1460
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810844b0-ffffffff810844d8: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81087610)
Location: kernel/exit.c:1545
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81087610-ffffffff81087638: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108c570)
Location: kernel/exit.c:1535
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8108c570-ffffffff8108c598: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810896e0)
Location: kernel/exit.c:1491
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810896e0-ffffffff81089708: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81090460)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81090460-ffffffff81090488: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81093f40)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81093f40-ffffffff81093f68: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109c2c0)
Location: kernel/exit.c:1493
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8109c2c0-ffffffff8109c2e8: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a08e0)
Location: kernel/exit.c:1497
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a08e0-ffffffff810a0908: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6ec0)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a6ec0-ffffffff810a6ee8: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae610)
Location: kernel/exit.c:1417
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810ae610-ffffffff810ae633: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9c60)
Location: kernel/exit.c:1436
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a9c60-ffffffff810a9c83: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aac90)
Location: kernel/exit.c:1436
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810aac90-ffffffff810aacb3: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bc7b0)
Location: kernel/exit.c:1436
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810bc7b0-ffffffff810bc7d3: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d3540)
Location: kernel/exit.c:1440
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810d3540-ffffffff810d356f: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f21d0)
Location: kernel/exit.c:1534
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810f21d0-ffffffff810f21ff: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fe150)
Location: kernel/exit.c:1539
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810fe150-ffffffff810fe17f: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81106ea0)
Location: kernel/exit.c:1519
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81106ea0-ffffffff81106ecf: __wake_up_parent (STB_GLOBAL)
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
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fdd98)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffff8000100fdd98-ffff8000100fddd8: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035b008)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c035b008-c035b038: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000144f00)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c000000000144f00-c000000000144f4c: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c6502)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffe0000c6502-ffffffe0000c653e: __wake_up_parent (STB_GLOBAL)
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
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a07e0)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a07e0-ffffffff810a0808: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f200)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8108f200-ffffffff8108f228: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0790)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a0790-ffffffff810a07b8: __wake_up_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_parent(struct task_struct *p, struct task_struct *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8710)
Location: kernel/exit.c:1413
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - fs/exec.c:de_thread
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810a8710-ffffffff810a8738: __wake_up_parent (STB_GLOBAL)
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
