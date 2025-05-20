# Function: <code>mount_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f9c0)
Location: fs/super.c:954
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff8120f9c0-ffffffff8120fa7e: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812367f0)
Location: fs/super.c:968
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff812367f0-ffffffff812368c9: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812494a0)
Location: fs/super.c:1014
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff812494a0-ffffffff81249579: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254da0)
Location: fs/super.c:1017
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff81254da0-ffffffff81254e9d: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276f30)
Location: fs/super.c:1017
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff81276f30-ffffffff8127702f: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129d930)
Location: fs/super.c:1072
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff8129d930-ffffffff8129da0c: mount_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *mount_ns(struct file_system_type *fs_type, int flags, void *data, void *ns, struct user_namespace *user_ns, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b28f0)
Location: fs/super.c:1057
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
  - ipc/mqueue.c:mqueue_mount
```
**Symbols:**

```
ffffffff812b28f0-ffffffff812b29cc: mount_ns (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ns</code>
</li>
<li>
<b>Param added. </b>
<code>struct user_namespace *user_ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>fs_type, flags, data, fill_super</code> ➡️ <code>fs_type, flags, data, ns, user_ns, fill_super</code>
</li>
</ul>
</details>
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
</ul>
