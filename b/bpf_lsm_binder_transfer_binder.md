# Function: <code>bpf_lsm_binder_transfer_binder</code>

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
int bpf_lsm_binder_transfer_binder(struct task_struct *from, struct task_struct *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812387f0)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff812387f0-ffffffff812387fd: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(struct task_struct *from, struct task_struct *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123cfa0)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff8123cfa0-ffffffff8123cfad: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(const struct cred *from, const struct cred *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277a60)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff81277a60-ffffffff81277a6d: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(const struct cred *from, const struct cred *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7830)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff812c7830-ffffffff812c7841: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(const struct cred *from, const struct cred *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132d470)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff8132d470-ffffffff8132d481: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(const struct cred *from, const struct cred *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135e0b0)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff8135e0b0-ffffffff8135e0c1: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_binder_transfer_binder(const struct cred *from, const struct cred *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81386e80)
Location: include/linux/lsm_hook_defs.h:32
Inline: False
```
**Symbols:**

```
ffffffff81386e80-ffffffff81386e91: bpf_lsm_binder_transfer_binder (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
