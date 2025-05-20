# Function: <code>rootfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002710)
Location: init/do_mounts.c:608
Inline: True
```
**Symbols:**

```
ffffffff81002710-ffffffff8100274f: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002770)
Location: init/do_mounts.c:616
Inline: True
```
**Symbols:**

```
ffffffff81002770-ffffffff810027af: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002790)
Location: init/do_mounts.c:616
Inline: True
```
**Symbols:**

```
ffffffff81002790-ffffffff810027cf: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002320)
Location: init/do_mounts.c:616
Inline: True
```
**Symbols:**

```
ffffffff81002320-ffffffff8100235f: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002350)
Location: init/do_mounts.c:615
Inline: True
```
**Symbols:**

```
ffffffff81002350-ffffffff8100238e: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002a60)
Location: init/do_mounts.c:615
Inline: True
```
**Symbols:**

```
ffffffff81002a60-ffffffff81002a9f: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ab0)
Location: init/do_mounts.c:637
Inline: True
```
**Symbols:**

```
ffffffff81002ab0-ffffffff81002aef: rootfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *rootfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002be0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff81002be0-ffffffff81002c0c: rootfs_mount (STB_LOCAL)
```
</details>
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
</ul>
