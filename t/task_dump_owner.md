# Function: <code>task_dump_owner</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, mode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ccf60)
Location: fs/proc/base.c:1694
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff812ccf60-ffffffff812cd022: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f1800)
Location: fs/proc/base.c:1695
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff812f1800-ffffffff812f18c1: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131e6c0)
Location: fs/proc/base.c:1661
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8131e6c0-ffffffff8131e79f: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813357b0)
Location: fs/proc/base.c:1675
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff813357b0-ffffffff8133588f: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135d820)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8135d820-ffffffff8135d914: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81375a80)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff81375a80-ffffffff81375b74: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813be530)
Location: fs/proc/base.c:1799
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff813be530-ffffffff813be62a: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d0280)
Location: fs/proc/base.c:1813
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff813d0280-ffffffff813d0376: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d71a0)
Location: fs/proc/base.c:1812
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff813d71a0-ffffffff813d7284: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814288e0)
Location: fs/proc/base.c:1818
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff814288e0-ffffffff814289c4: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a1be0)
Location: fs/proc/base.c:1817
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff814a1be0-ffffffff814a1ced: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81536c90)
Location: fs/proc/base.c:1818
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff81536c90-ffffffff81536d9d: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156ee70)
Location: fs/proc/base.c:1818
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff8156ee70-ffffffff8156ef7d: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a7830)
Location: fs/proc/base.c:1814
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff815a7830-ffffffff815a793d: task_dump_owner (STB_GLOBAL)
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
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010440db0)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffff800010440db0-ffff800010440efc: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c06067a8)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
c06067a8-c0606890: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000555ca0)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
c000000000555ca0-c000000000555e20: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d7e18)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffe0002d7e18-ffffffe0002d7f20: task_dump_owner (STB_GLOBAL)
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
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136e060)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8136e060-ffffffff8136e154: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135eaf0)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8135eaf0-ffffffff8135ebe4: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136bb30)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8136bb30-ffffffff8136bc24: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct *task, umode_t mode, kuid_t *ruid, kgid_t *rgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137f3d0)
Location: fs/proc/base.c:1688
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8137f3d0-ffffffff8137f4df: task_dump_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>mode_t mode</code> ➡️ <code>umode_t mode</code>
</li>
</ul>
</details>
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
