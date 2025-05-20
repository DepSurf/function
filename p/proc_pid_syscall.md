# Function: <code>proc_pid_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127b0e0)
Location: fs/proc/base.c:659
Inline: True
```
**Symbols:**

```
ffffffff8127b0e0-ffffffff8127b1e7: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a7be0)
Location: fs/proc/base.c:656
Inline: True
```
**Symbols:**

```
ffffffff812a7be0-ffffffff812a7cee: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bd4c0)
Location: fs/proc/base.c:642
Inline: True
```
**Symbols:**

```
ffffffff812bd4c0-ffffffff812bd5ce: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ca460)
Location: fs/proc/base.c:619
Inline: True
```
**Symbols:**

```
ffffffff812ca460-ffffffff812ca552: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812eecf0)
Location: fs/proc/base.c:619
Inline: True
```
**Symbols:**

```
ffffffff812eecf0-ffffffff812eede2: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131bc00)
Location: fs/proc/base.c:596
Inline: True
```
**Symbols:**

```
ffffffff8131bc00-ffffffff8131bcf2: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81332d90)
Location: fs/proc/base.c:616
Inline: True
```
**Symbols:**

```
ffffffff81332d90-ffffffff81332e82: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ad10)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff8135ad10-ffffffff8135aded: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81372f20)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff81372f20-ffffffff81372ffd: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813bb190)
Location: fs/proc/base.c:630
Inline: True
```
**Symbols:**

```
ffffffff813bb190-ffffffff813bb253: proc_pid_syscall.part.0 (STB_LOCAL)
ffffffff813bb6b0-ffffffff813bb71d: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813ccd20)
Location: fs/proc/base.c:639
Inline: True
```
**Symbols:**

```
ffffffff813ccd20-ffffffff813ccde3: proc_pid_syscall.part.0 (STB_LOCAL)
ffffffff813cd240-ffffffff813cd2ad: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d41b0)
Location: fs/proc/base.c:636
Inline: True
```
**Symbols:**

```
ffffffff813d41b0-ffffffff813d42cc: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814258c0)
Location: fs/proc/base.c:640
Inline: True
```
**Symbols:**

```
ffffffff814258c0-ffffffff814259dc: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8149eca0)
Location: fs/proc/base.c:639
Inline: False
```
**Symbols:**

```
ffffffff8149eca0-ffffffff8149ede2: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81533a10)
Location: fs/proc/base.c:640
Inline: False
```
**Symbols:**

```
ffffffff81533a10-ffffffff81533b52: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156bc00)
Location: fs/proc/base.c:641
Inline: False
```
**Symbols:**

```
ffffffff8156bc00-ffffffff8156bd42: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a4370)
Location: fs/proc/base.c:641
Inline: False
```
**Symbols:**

```
ffffffff815a4370-ffffffff815a44b2: proc_pid_syscall (STB_LOCAL)
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
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043d440)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffff80001043d440-ffff80001043d538: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0603548)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
c0603548-c0603664: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0000000005518d0)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
c0000000005518d0-c000000000551a10: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d6782)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffe0002d6782-ffffffe0002d6858: proc_pid_syscall (STB_LOCAL)
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
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136b500)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff8136b500-ffffffff8136b5dd: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135bf90)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff8135bf90-ffffffff8135c06d: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81368fd0)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff81368fd0-ffffffff813690ad: proc_pid_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int proc_pid_syscall(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137c840)
Location: fs/proc/base.c:628
Inline: True
```
**Symbols:**

```
ffffffff8137c840-ffffffff8137c91d: proc_pid_syscall (STB_LOCAL)
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
