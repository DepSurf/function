# Function: <code>proc_pid_make_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127d640)
Location: fs/proc/base.c:1643
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8127d640-ffffffff8127d726: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812aa620)
Location: fs/proc/base.c:1659
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812aa620-ffffffff812aa702: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bff70)
Location: fs/proc/base.c:1677
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812bff70-ffffffff812c0051: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cd2c0)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812cd2c0-ffffffff812cd365: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f1b60)
Location: fs/proc/base.c:1747
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812f1b60-ffffffff812f1c05: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131e9a0)
Location: fs/proc/base.c:1719
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8131e9a0-ffffffff8131ea41: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81335a90)
Location: fs/proc/base.c:1733
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff81335a90-ffffffff81335b31: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135db20)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8135db20-ffffffff8135dbcb: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81375d80)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff81375d80-ffffffff81375e2b: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813be990)
Location: fs/proc/base.c:1870
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff813be990-ffffffff813bea92: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d0760)
Location: fs/proc/base.c:1884
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff813d0760-ffffffff813d0862: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d7660)
Location: fs/proc/base.c:1883
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff813d7660-ffffffff813d7762: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81428da0)
Location: fs/proc/base.c:1889
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff81428da0-ffffffff81428ea2: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a20a0)
Location: fs/proc/base.c:1888
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff814a20a0-ffffffff814a2165: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815371a0)
Location: fs/proc/base.c:1889
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff815371a0-ffffffff81537265: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156f390)
Location: fs/proc/base.c:1889
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8156f390-ffffffff8156f455: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a7d40)
Location: fs/proc/base.c:1883
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff815a7d40-ffffffff815a7de6: proc_pid_make_inode (STB_GLOBAL)
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
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010441138)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffff800010441138-ffff800010441200: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0606a94)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
c0606a94-c0606b8c: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000556160)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
c000000000556160-c000000000556264: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d80e6)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffe0002d80e6-ffffffe0002d8194: proc_pid_make_inode (STB_GLOBAL)
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
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136e360)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8136e360-ffffffff8136e40b: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135edf0)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8135edf0-ffffffff8135ee9b: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136be30)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8136be30-ffffffff8136bedb: proc_pid_make_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *proc_pid_make_inode(struct super_block *sb, struct task_struct *task, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137f6f0)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8137f6f0-ffffffff8137f79b: proc_pid_make_inode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
</details>
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
