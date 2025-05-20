# Function: <code>vfs_parse_fs_param_source</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_parse_fs_param_source(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9030)
Location: fs/fs_context.c:94
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - fs/fs_context.c:legacy_parse_param
```
**Symbols:**

```
ffffffff813b9030-ffffffff813b90be: vfs_parse_fs_param_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_parse_fs_param_source(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143ea60)
Location: fs/fs_context.c:94
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/ramfs/inode.c:ramfs_parse_param
```
**Symbols:**

```
ffffffff8143ea60-ffffffff8143eaf5: vfs_parse_fs_param_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_parse_fs_param_source(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cd680)
Location: fs/fs_context.c:94
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/ramfs/inode.c:ramfs_parse_param
```
**Symbols:**

```
ffffffff814cd680-ffffffff814cd715: vfs_parse_fs_param_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_parse_fs_param_source(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81503850)
Location: fs/fs_context.c:94
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/ramfs/inode.c:ramfs_parse_param
```
**Symbols:**

```
ffffffff81503850-ffffffff815038e5: vfs_parse_fs_param_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_parse_fs_param_source(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815384a0)
Location: fs/fs_context.c:94
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/ramfs/inode.c:ramfs_parse_param
```
**Symbols:**

```
ffffffff815384a0-ffffffff81538535: vfs_parse_fs_param_source (STB_GLOBAL)
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
