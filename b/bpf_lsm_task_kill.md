# Function: <code>bpf_lsm_task_kill</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238f60)
Location: include/linux/lsm_hook_defs.h:212
Inline: False
```
**Symbols:**

```
ffffffff81238f60-ffffffff81238f6d: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d750)
Location: include/linux/lsm_hook_defs.h:222
Inline: False
```
**Symbols:**

```
ffffffff8123d750-ffffffff8123d75d: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278210)
Location: include/linux/lsm_hook_defs.h:222
Inline: False
```
**Symbols:**

```
ffffffff81278210-ffffffff8127821d: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8670)
Location: include/linux/lsm_hook_defs.h:220
Inline: False
```
**Symbols:**

```
ffffffff812c8670-ffffffff812c8681: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132eb40)
Location: include/linux/lsm_hook_defs.h:228
Inline: False
```
**Symbols:**

```
ffffffff8132eb40-ffffffff8132eb51: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135f7b0)
Location: include/linux/lsm_hook_defs.h:229
Inline: False
```
**Symbols:**

```
ffffffff8135f7b0-ffffffff8135f7c1: bpf_lsm_task_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_task_kill(struct task_struct *p, struct kernel_siginfo *info, int sig, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813885d0)
Location: include/linux/lsm_hook_defs.h:234
Inline: False
```
**Symbols:**

```
ffffffff813885d0-ffffffff813885e1: bpf_lsm_task_kill (STB_GLOBAL)
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
