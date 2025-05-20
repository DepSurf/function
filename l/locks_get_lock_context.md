# Function: <code>locks_get_lock_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff812604c0)
Location: fs/locks.c:206
Inline: True
Inline callers:
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:flock_lock_inode
Direct callers:
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812604c0-ffffffff81260539: locks_get_lock_context.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128b730)
Location: fs/locks.c:205
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8128b730-ffffffff8128b827: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a0530)
Location: fs/locks.c:215
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812a0530-ffffffff812a0627: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af360)
Location: fs/locks.c:215
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812af360-ffffffff812af467: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2de0)
Location: fs/locks.c:216
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812d2de0-ffffffff812d2eea: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fd6d0)
Location: fs/locks.c:216
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812fd6d0-ffffffff812fd7d4: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81312f50)
Location: fs/locks.c:247
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81312f50-ffffffff81313054: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133a750)
Location: fs/locks.c:248
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133a750-ffffffff8133a85a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81352c80)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81352c80-ffffffff81352d8a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139a3e0)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8139a3e0-ffffffff8139a4dc: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813abed0)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813abed0-ffffffff813abfba: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b3080)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813b3080-ffffffff813b316a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81402d70)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81402d70-ffffffff81402e57: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477ba0)
Location: fs/locks.c:173
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81477ba0-ffffffff81477c9b: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150a450)
Location: fs/locks.c:173
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8150a450-ffffffff8150a54b: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541be0)
Location: fs/locks.c:174
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81541be0-ffffffff81541cdb: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81577110)
Location: fs/locks.c:173
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81577110-ffffffff8157720b: locks_get_lock_context (STB_LOCAL)
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
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416078)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffff800010416078-ffff8000104161f4: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e2728)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c05e2728-c05e2880: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005238b0)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c0000000005238b0-c000000000523aa8: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc43c)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffe0002bc43c-ffffffe0002bc544: locks_get_lock_context (STB_LOCAL)
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
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b260)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8134b260-ffffffff8134b36a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133bf40)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133bf40-ffffffff8133c04a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81348d30)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81348d30-ffffffff81348e3a: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file_lock_context *locks_get_lock_context(struct inode *inode, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c150)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8135c150-ffffffff8135c265: locks_get_lock_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
