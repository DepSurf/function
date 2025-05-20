# Function: <code>tid_fd_update_inode</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81322da0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81322da0-ffffffff81322e09: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81339ef0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81339ef0-ffffffff81339f59: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81362090)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81362090-ffffffff813620fa: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8137a2f0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8137a2f0-ffffffff8137a35a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813c3699)
Location: fs/proc/fd.c:101
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813c3450-ffffffff813c34ba: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813d56a9)
Location: fs/proc/fd.c:97
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813d54d0-ffffffff813d553a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813dc509)
Location: fs/proc/fd.c:97
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813dc320-ffffffff813dc38a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8142db49)
Location: fs/proc/fd.c:111
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8142d980-ffffffff8142d9ea: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff814a7505)
Location: fs/proc/fd.c:121
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff814a7310-ffffffff814a7387: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8153cbd5)
Location: fs/proc/fd.c:122
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8153c9b0-ffffffff8153ca27: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81574e95)
Location: fs/proc/fd.c:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81574c70-ffffffff81574ce7: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff815ad865)
Location: fs/proc/fd.c:125
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
Direct callers:
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff815ad640-ffffffff815ad6b7: tid_fd_update_inode (STB_LOCAL)
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
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffff8000104465a0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffff8000104465a0-ffff800010446620: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c060b708)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
c060b708-c060b770: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c00000000055c2c0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
c00000000055c2c0-c00000000055c3a8: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffe0002dc4e6)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffe0002dc4e6-ffffffe0002dc55c: tid_fd_update_inode (STB_LOCAL)
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
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813728d0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813728d0-ffffffff8137293a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813633a0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813633a0-ffffffff8136340a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813703a0)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813703a0-ffffffff8137040a: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tid_fd_update_inode(struct task_struct *task, struct inode *inode, fmode_t f_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81383d60)
Location: fs/proc/fd.c:101
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81383d60-ffffffff81383dca: tid_fd_update_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
