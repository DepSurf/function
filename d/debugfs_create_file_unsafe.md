# Function: <code>debugfs_create_file_unsafe</code>

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
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352ad0)
Location: fs/debugfs/inode.c:399
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
```
**Symbols:**

```
ffffffff81352ad0-ffffffff81352afb: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368d80)
Location: fs/debugfs/inode.c:399
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff81368d80-ffffffff81368dab: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137d410)
Location: fs/debugfs/inode.c:433
Inline: False
Direct callers:
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff8137d410-ffffffff8137d43b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a2320)
Location: fs/debugfs/inode.c:436
Inline: False
Direct callers:
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff813a2320-ffffffff813a234b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d1580)
Location: fs/debugfs/inode.c:459
Inline: False
Direct callers:
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff813d1580-ffffffff813d15ab: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813ebe20)
Location: fs/debugfs/inode.c:460
Inline: False
Direct callers:
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff813ebe20-ffffffff813ebe4b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81417f10)
Location: fs/debugfs/inode.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff81417f10-ffffffff81417f3b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81431dd0)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff81431dd0-ffffffff81431dfb: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814816f0)
Location: fs/debugfs/inode.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814816f0-ffffffff8148171b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149f240)
Location: fs/debugfs/inode.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8149f240-ffffffff8149f26b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a5220)
Location: fs/debugfs/inode.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814a5220-ffffffff814a524b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fd370)
Location: fs/debugfs/inode.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814fd370-ffffffff814fd39b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158dbe0)
Location: fs/debugfs/inode.c:498
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8158dbe0-ffffffff8158dc1d: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81634340)
Location: fs/debugfs/inode.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff81634340-ffffffff8163437d: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166c650)
Location: fs/debugfs/inode.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - crypto/jitterentropy-testing.c:jent_testing_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8166c650-ffffffff8166c68d: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a6ed0)
Location: fs/debugfs/inode.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_str
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_bool
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_atomic_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_size_t
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x64
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x32
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x16
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_x8
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_ulong
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u64
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u32
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u16
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - fs/debugfs/file.c:debugfs_create_u8
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff816a6ed0-ffffffff816a6f0d: debugfs_create_file_unsafe (STB_GLOBAL)
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
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010516be0)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffff800010516be0-ffff800010516c54: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d194c)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
c06d194c-c06d1994: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065fc20)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/powerpc/kernel/dawr.c:dawr_force_setup
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/kernel/eeh_cache.c:eeh_cache_debugfs_init
  - arch/powerpc/mm/book3s64/hash_utils.c:__machine_initcall_pseries_hash64_debugfs
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
c00000000065fc20-c00000000065fc5c: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe000380274)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe000380274-ffffffe0003802d0: debugfs_create_file_unsafe (STB_GLOBAL)
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
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8142a3b0)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff8142a3b0-ffffffff8142a3db: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8141ae30)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff8141ae30-ffffffff8141ae5b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81426550)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff81426550-ffffffff8142657b: debugfs_create_file_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_file_unsafe(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143d410)
Location: fs/debugfs/inode.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - kernel/panic.c:register_warn_debugfs
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - fs/debugfs/file.c:debugfs_create_mode_unsafe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
```
**Symbols:**

```
ffffffff8143d410-ffffffff8143d43b: debugfs_create_file_unsafe (STB_GLOBAL)
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
