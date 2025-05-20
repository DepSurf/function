# Function: <code>task_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81280af7)
Location: fs/proc/array.c:142
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812adb64)
Location: fs/proc/array.c:156
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812c3461)
Location: fs/proc/array.c:156
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812d06dd)
Location: fs/proc/array.c:160
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812f4f0f)
Location: fs/proc/array.c:157
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813222bd)
Location: fs/proc/array.c:152
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813393cd)
Location: fs/proc/array.c:152
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813603a0)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813603a0-ffffffff813608b9: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81378600)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81378600-ffffffff81378b19: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813c16f0)
Location: fs/proc/array.c:151
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813c16f0-ffffffff813c1bdf: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813d35e0)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813d35e0-ffffffff813d3ada: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813da410)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813da410-ffffffff813da90a: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff8142bb40)
Location: fs/proc/array.c:142
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8142bb40-ffffffff8142c060: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff814a57a0)
Location: fs/proc/array.c:144
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff814a57a0-ffffffff814a5cea: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff8153adb0)
Location: fs/proc/array.c:147
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8153adb0-ffffffff8153b2fa: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff815730c0)
Location: fs/proc/array.c:148
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff815730c0-ffffffff81573623: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff815ab880)
Location: fs/proc/array.c:148
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff815ab880-ffffffff815abde6: task_state (STB_LOCAL)
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
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffff800010444c90)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffff800010444c90-ffff800010445224: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (c0609884)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c0609884-c0609e80: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (c00000000055a060)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c00000000055a060-c00000000055a780: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffe0002dac6e)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffe0002dac6e-ffffffe0002db1e4: task_state (STB_LOCAL)
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
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81370be0)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81370be0-ffffffff813710f9: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81361670)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81361670-ffffffff81361b89: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff8136e6b0)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8136e6b0-ffffffff8136ebc9: task_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_state(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81382000)
Location: fs/proc/array.c:152
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81382000-ffffffff8138255d: task_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
