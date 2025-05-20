# Function: <code>proc_pid_ksm_merging_pages</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_pid_ksm_merging_pages(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8149d640)
Location: fs/proc/base.c:3188
Inline: False
```
**Symbols:**

```
ffffffff8149d640-ffffffff8149d690: proc_pid_ksm_merging_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_pid_ksm_merging_pages(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815321e0)
Location: fs/proc/base.c:3190
Inline: False
```
**Symbols:**

```
ffffffff815321e0-ffffffff81532230: proc_pid_ksm_merging_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_pid_ksm_merging_pages(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156a340)
Location: fs/proc/base.c:3190
Inline: False
```
**Symbols:**

```
ffffffff8156a340-ffffffff8156a390: proc_pid_ksm_merging_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_pid_ksm_merging_pages(struct seq_file *m, struct pid_namespace *ns, struct pid *pid, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a29c0)
Location: fs/proc/base.c:3196
Inline: False
```
**Symbols:**

```
ffffffff815a29c0-ffffffff815a2a10: proc_pid_ksm_merging_pages (STB_LOCAL)
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
