# Function: <code>security_task_to_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e920)
Location: security/security.c:1016
Inline: False
Direct callers:
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8133e920-ffffffff8133e960: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373f40)
Location: security/security.c:1040
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff81373f40-ffffffff81373f80: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a870)
Location: security/security.c:1061
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8138a870-ffffffff8138a8b0: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139feb0)
Location: security/security.c:1779
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8139feb0-ffffffff8139fef0: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5af0)
Location: security/security.c:1741
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813c5af0-ffffffff813c5b36: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5980)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff813f5980-ffffffff813f59be: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410fb0)
Location: security/security.c:1773
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff81410fb0-ffffffff81410fee: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e800)
Location: security/security.c:1792
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8143e800-ffffffff8143e840: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814581f0)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff814581f0-ffffffff8145822e: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab080)
Location: security/security.c:2027
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff814ab080-ffffffff814ab0be: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8680)
Location: security/security.c:2044
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff814c8680-ffffffff814c86be: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cecc0)
Location: security/security.c:2107
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff814cecc0-ffffffff814cecfe: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527980)
Location: security/security.c:2115
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff81527980-ffffffff815279be: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc880)
Location: security/security.c:2121
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff815bc880-ffffffff815bc8c8: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668ac0)
Location: security/security.c:2197
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff81668ac0-ffffffff81668b08: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1090)
Location: security/security.c:3624
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff816a1090-ffffffff816a10d8: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd950)
Location: security/security.c:3659
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:proc_fdinfo_instantiate
```
**Symbols:**

```
ffffffff816dd950-ffffffff816dd998: security_task_to_inode (STB_GLOBAL)
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
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544018)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffff800010544018-ffff800010544070: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9f38)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
c06f9f38-c06f9f88: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006989a0)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
c0000000006989a0-c000000000698a30: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a02b2)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffe0003a02b2-ffffffe0003a02f2: security_task_to_inode (STB_GLOBAL)
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
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814507d0)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff814507d0-ffffffff8145080e: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441220)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff81441220-ffffffff8144125e: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c870)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff8144c870-ffffffff8144c8ae: security_task_to_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_task_to_inode(struct task_struct *p, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463c40)
Location: security/security.c:1831
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_update_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/fd.c:tid_fd_update_inode
```
**Symbols:**

```
ffffffff81463c40-ffffffff81463c7e: security_task_to_inode (STB_GLOBAL)
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
