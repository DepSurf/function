# Function: <code>fs_context_for_mount</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130ac50)
Location: fs/fs_context.c:306
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff8130ac50-ffffffff8130ac69: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dc30)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff8131dc30-ffffffff8131dc49: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813579f0)
Location: fs/fs_context.c:278
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813579f0-ffffffff81357a09: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813644e0)
Location: fs/fs_context.c:278
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813644e0-ffffffff813644f9: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136af40)
Location: fs/fs_context.c:278
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8136af40-ffffffff8136af59: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9c00)
Location: fs/fs_context.c:301
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813b9c00-ffffffff813b9c19: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f6b0)
Location: fs/fs_context.c:301
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8143f6b0-ffffffff8143f6d8: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce360)
Location: fs/fs_context.c:301
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff814ce360-ffffffff814ce388: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81504560)
Location: fs/fs_context.c:301
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81504560-ffffffff81504588: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81539220)
Location: fs/fs_context.c:329
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81539220-ffffffff81539248: fs_context_for_mount (STB_GLOBAL)
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
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5d48)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffff8000103d5d48-ffff8000103d5d88: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af2f8)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c05af2f8-c05af32c: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d9470)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c0000000004d9470-c0000000004d9494: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f5ea)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffe00028f5ea-ffffffe00028f622: fs_context_for_mount (STB_GLOBAL)
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
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81316210)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81316210-ffffffff81316229: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306e00)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81306e00-ffffffff81306e19: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81314000)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81314000-ffffffff81314019: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_context *fs_context_for_mount(struct file_system_type *fs_type, unsigned int sb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325850)
Location: fs/fs_context.c:304
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81325850-ffffffff81325869: fs_context_for_mount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
