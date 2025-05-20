# Function: <code>vfs_mkobj</code>

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
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9170)
Location: fs/namei.c:2900
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812a9170-ffffffff812a9309: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bef90)
Location: fs/namei.c:2919
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812bef90-ffffffff812bf129: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dbb90)
Location: fs/namei.c:2917
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812dbb90-ffffffff812dbd27: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ed6a0)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812ed6a0-ffffffff812ed837: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324a00)
Location: fs/namei.c:2812
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81324a00-ffffffff81324bdd: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813301f0)
Location: fs/namei.c:2810
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813301f0-ffffffff813303b2: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81336ab0)
Location: fs/namei.c:2919
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81336ab0-ffffffff81336c57: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384490)
Location: fs/namei.c:2988
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81384490-ffffffff8138464b: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402df0)
Location: fs/namei.c:3084
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81402df0-ffffffff81402fc1: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148d1e0)
Location: fs/namei.c:3122
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8148d1e0-ffffffff8148d3b1: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c27b0)
Location: fs/namei.c:3201
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff814c27b0-ffffffff814c299b: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f4c70)
Location: fs/namei.c:3209
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff814f4c70-ffffffff814f4e5b: vfs_mkobj (STB_GLOBAL)
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
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010396cd0)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff800010396cd0-ffff800010396e5c: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057c31c)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c057c31c-c057c4d0: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048f4f0)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c00000000048f4f0-c00000000048f728: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000264f92)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe000264f92-ffffffe0002650b6: vfs_mkobj (STB_GLOBAL)
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
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5c80)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e5c80-ffffffff812e5e17: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d68c0)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812d68c0-ffffffff812d6a57: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3a90)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812e3a90-ffffffff812e3c27: vfs_mkobj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry *dentry, umode_t mode, int (*f)(struct dentry *, umode_t, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3b60)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812f3b60-ffffffff812f3cf7: vfs_mkobj (STB_GLOBAL)
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
