# Function: <code>debugfs_create_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e4c0)
Location: fs/debugfs/file.c:45
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_bool
```
**Symbols:**

```
ffffffff8131e4c0-ffffffff8131e4f9: debugfs_create_mode (STB_LOCAL)
```
</details>
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
</ul>
