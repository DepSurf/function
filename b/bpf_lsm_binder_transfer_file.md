# Function: <code>bpf_lsm_binder_transfer_file</code>

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
int bpf_lsm_binder_transfer_file(struct task_struct *from, struct task_struct *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238800)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff81238800-ffffffff8123880d: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(struct task_struct *from, struct task_struct *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123cfb0)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff8123cfb0-ffffffff8123cfbd: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(const struct cred *from, const struct cred *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277a70)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff81277a70-ffffffff81277a7d: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(const struct cred *from, const struct cred *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7850)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff812c7850-ffffffff812c7861: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(const struct cred *from, const struct cred *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132d4a0)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff8132d4a0-ffffffff8132d4b1: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(const struct cred *from, const struct cred *to, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135e0e0)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff8135e0e0-ffffffff8135e0f1: bpf_lsm_binder_transfer_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_file(const struct cred *from, const struct cred *to, const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81386eb0)
Location: include/linux/lsm_hook_defs.h:34
Inline: False
```
**Symbols:**

```
ffffffff81386eb0-ffffffff81386ec1: bpf_lsm_binder_transfer_file (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct task_struct *from</code> ➡️ <code>const struct cred *from</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct task_struct *to</code> ➡️ <code>const struct cred *to</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct file *file</code> ➡️ <code>const struct file *file</code>
</li>
</ul>
</details>
</li>
</ul>
