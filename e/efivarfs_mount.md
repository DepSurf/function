# Function: <code>efivarfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff81321610)
Location: fs/efivarfs/super.c:227
Inline: False
```
**Symbols:**

```
ffffffff81321610-ffffffff8132162a: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff813569e0)
Location: fs/efivarfs/super.c:225
Inline: False
```
**Symbols:**

```
ffffffff813569e0-ffffffff813569fa: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff8136ce40)
Location: fs/efivarfs/super.c:230
Inline: False
```
**Symbols:**

```
ffffffff8136ce40-ffffffff8136ce5a: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff81381390)
Location: fs/efivarfs/super.c:229
Inline: False
```
**Symbols:**

```
ffffffff81381390-ffffffff813813aa: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff813a63a0)
Location: fs/efivarfs/super.c:229
Inline: False
```
**Symbols:**

```
ffffffff813a63a0-ffffffff813a63ba: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff813d56b0)
Location: fs/efivarfs/super.c:229
Inline: False
```
**Symbols:**

```
ffffffff813d56b0-ffffffff813d56ca: efivarfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *efivarfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff813efd00)
Location: fs/efivarfs/super.c:229
Inline: False
```
**Symbols:**

```
ffffffff813efd00-ffffffff813efd1a: efivarfs_mount (STB_LOCAL)
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
</ul>
