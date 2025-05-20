# Function: <code>bpf_lsm_msg_queue_msgrcv</code>

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
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239020)
Location: include/linux/lsm_hook_defs.h:230
Inline: False
```
**Symbols:**

```
ffffffff81239020-ffffffff8123902d: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d810)
Location: include/linux/lsm_hook_defs.h:240
Inline: False
```
**Symbols:**

```
ffffffff8123d810-ffffffff8123d81d: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812782d0)
Location: include/linux/lsm_hook_defs.h:240
Inline: False
```
**Symbols:**

```
ffffffff812782d0-ffffffff812782dd: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c87d0)
Location: include/linux/lsm_hook_defs.h:239
Inline: False
```
**Symbols:**

```
ffffffff812c87d0-ffffffff812c87e1: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132ed70)
Location: include/linux/lsm_hook_defs.h:247
Inline: False
```
**Symbols:**

```
ffffffff8132ed70-ffffffff8132ed81: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135f9e0)
Location: include/linux/lsm_hook_defs.h:248
Inline: False
```
**Symbols:**

```
ffffffff8135f9e0-ffffffff8135f9f1: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_msg_queue_msgrcv(struct kern_ipc_perm *perm, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81388800)
Location: include/linux/lsm_hook_defs.h:253
Inline: False
```
**Symbols:**

```
ffffffff81388800-ffffffff81388811: bpf_lsm_msg_queue_msgrcv (STB_GLOBAL)
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
