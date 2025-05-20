# Function: <code>proc_task_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_task_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127bb70)
Location: fs/proc/base.c:3372
Inline: False
```
**Symbols:**

```
ffffffff8127bb70-ffffffff8127bbd2: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_task_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a8860)
Location: fs/proc/base.c:3501
Inline: False
```
**Symbols:**

```
ffffffff812a8860-ffffffff812a88c2: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_task_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812be140)
Location: fs/proc/base.c:3534
Inline: False
```
**Symbols:**

```
ffffffff812be140-ffffffff812be1a2: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cb910)
Location: fs/proc/base.c:3664
Inline: False
```
**Symbols:**

```
ffffffff812cb910-ffffffff812cb976: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f00f0)
Location: fs/proc/base.c:3665
Inline: False
```
**Symbols:**

```
ffffffff812f00f0-ffffffff812f0156: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131d0a0)
Location: fs/proc/base.c:3572
Inline: False
```
**Symbols:**

```
ffffffff8131d0a0-ffffffff8131d106: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81334380)
Location: fs/proc/base.c:3666
Inline: False
```
**Symbols:**

```
ffffffff81334380-ffffffff813343e6: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135c830)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff8135c830-ffffffff8135c89d: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81374dd0)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff81374dd0-ffffffff81374e3d: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bc9c0)
Location: fs/proc/base.c:3783
Inline: False
```
**Symbols:**

```
ffffffff813bc9c0-ffffffff813bca45: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813ce470)
Location: fs/proc/base.c:3803
Inline: False
```
**Symbols:**

```
ffffffff813ce470-ffffffff813ce4f5: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_task_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d50f0)
Location: fs/proc/base.c:3816
Inline: False
```
**Symbols:**

```
ffffffff813d50f0-ffffffff813d517c: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_task_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81426a30)
Location: fs/proc/base.c:3822
Inline: False
```
**Symbols:**

```
ffffffff81426a30-ffffffff81426abc: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_task_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a03c0)
Location: fs/proc/base.c:3878
Inline: False
```
**Symbols:**

```
ffffffff814a03c0-ffffffff814a045e: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_task_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815352e0)
Location: fs/proc/base.c:3895
Inline: False
```
**Symbols:**

```
ffffffff815352e0-ffffffff8153537e: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_task_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156d4b0)
Location: fs/proc/base.c:3898
Inline: False
```
**Symbols:**

```
ffffffff8156d4b0-ffffffff8156d54e: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_task_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a5e20)
Location: fs/proc/base.c:3902
Inline: False
```
**Symbols:**

```
ffffffff815a5e20-ffffffff815a5ece: proc_task_getattr (STB_LOCAL)
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
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043e5e8)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffff80001043e5e8-ffff80001043e684: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0605298)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
c0605298-c0605318: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000554130)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
c000000000554130-c00000000055421c: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d4e46)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffe0002d4e46-ffffffe0002d4ed2: proc_task_getattr (STB_LOCAL)
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
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136d3b0)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff8136d3b0-ffffffff8136d41d: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135de40)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff8135de40-ffffffff8135dead: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136ae80)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff8136ae80-ffffffff8136aeed: proc_task_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_task_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137e890)
Location: fs/proc/base.c:3702
Inline: False
```
**Symbols:**

```
ffffffff8137e890-ffffffff8137e8fd: proc_task_getattr (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt, dentry, stat</code> ➡️ <code>path, stat, request_mask, query_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>path, stat, request_mask, query_flags</code> ➡️ <code>mnt_userns, path, stat, request_mask, query_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
