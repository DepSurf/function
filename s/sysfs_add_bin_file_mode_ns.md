# Function: <code>sysfs_add_bin_file_mode_ns</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_add_bin_file_mode_ns(struct kernfs_node *parent, const struct bin_attribute *battr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b7a10)
Location: fs/sysfs/file.c:304
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff814b7a10-ffffffff814b7af2: sysfs_add_bin_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_add_bin_file_mode_ns(struct kernfs_node *parent, const struct bin_attribute *battr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154eeb0)
Location: fs/sysfs/file.c:304
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff8154eeb0-ffffffff8154ef92: sysfs_add_bin_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_add_bin_file_mode_ns(struct kernfs_node *parent, const struct bin_attribute *battr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81586b80)
Location: fs/sysfs/file.c:304
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff81586b80-ffffffff81586c62: sysfs_add_bin_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_add_bin_file_mode_ns(struct kernfs_node *parent, const struct bin_attribute *battr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf6e0)
Location: fs/sysfs/file.c:317
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff815bf6e0-ffffffff815bf7c2: sysfs_add_bin_file_mode_ns (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
