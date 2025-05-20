# Function: <code>debugfs_create_mode_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353640)
Location: fs/debugfs/file.c:316
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff81353640-ffffffff81353675: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813698f0)
Location: fs/debugfs/file.c:313
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff813698f0-ffffffff81369925: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137df60)
Location: fs/debugfs/file.c:313
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff8137df60-ffffffff8137df95: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2bd0)
Location: fs/debugfs/file.c:355
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff813a2bd0-ffffffff813a2c05: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d1fb0)
Location: fs/debugfs/file.c:376
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff813d1fb0-ffffffff813d1fe5: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec6b0)
Location: fs/debugfs/file.c:378
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff813ec6b0-ffffffff813ec6e5: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814188e0)
Location: fs/debugfs/file.c:378
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff814188e0-ffffffff81418920: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814327a0)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff814327a0-ffffffff814327e0: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814830ba)
Location: fs/debugfs/file.c:392
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a074a)
Location: fs/debugfs/file.c:392
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6b8a)
Location: fs/debugfs/file.c:392
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fecea)
Location: fs/debugfs/file.c:396
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fc49)
Location: fs/debugfs/file.c:396
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636f59)
Location: fs/debugfs/file.c:412
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166eeb5)
Location: fs/debugfs/file.c:412
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a99b5)
Location: fs/debugfs/file.c:504
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
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
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010517ba0)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffff800010517ba0-ffff800010517c2c: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d2498)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
c06d2498-c06d24ec: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660d40)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
c000000000660d40-c000000000660dcc: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381164)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffe000381164-ffffffe0003811ca: debugfs_create_mode_unsafe (STB_LOCAL)
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
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142ad80)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff8142ad80-ffffffff8142adc0: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b800)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff8141b800-ffffffff8141b840: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81426f20)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff81426f20-ffffffff81426f60: debugfs_create_mode_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_mode_unsafe(const char *name, umode_t mode, struct dentry *parent, void *value, const struct file_operations *fops, const struct file_operations *fops_ro, const struct file_operations *fops_wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143dde0)
Location: fs/debugfs/file.c:381
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
```
**Symbols:**

```
ffffffff8143dde0-ffffffff8143de20: debugfs_create_mode_unsafe (STB_LOCAL)
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
