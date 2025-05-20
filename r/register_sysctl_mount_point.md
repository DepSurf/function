# Function: <code>register_sysctl_mount_point</code>

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
struct ctl_table_header *register_sysctl_mount_point(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ad7c0)
Location: fs/proc/proc_sysctl.c:52
Inline: False
Direct callers:
  - fs/file_table.c:init_fs_stat_sysctls
```
**Symbols:**

```
ffffffff814ad7c0-ffffffff814ad7eb: register_sysctl_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_mount_point(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81543ca0)
Location: fs/proc/proc_sysctl.c:45
Inline: False
Direct callers:
  - fs/file_table.c:init_fs_stat_sysctls
```
**Symbols:**

```
ffffffff81543ca0-ffffffff81543ccb: register_sysctl_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_mount_point(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157bd80)
Location: fs/proc/proc_sysctl.c:44
Inline: False
Direct callers:
  - fs/file_table.c:init_fs_stat_sysctls
```
**Symbols:**

```
ffffffff8157bd80-ffffffff8157bdab: register_sysctl_mount_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_mount_point(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b4610)
Location: fs/proc/proc_sysctl.c:45
Inline: False
Direct callers:
  - fs/file_table.c:init_fs_stat_sysctls
```
**Symbols:**

```
ffffffff815b4610-ffffffff815b4642: register_sysctl_mount_point (STB_GLOBAL)
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
