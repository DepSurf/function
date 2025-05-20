# Function: <code>cgroup_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81117e80)
Location: kernel/cgroup.c:2066
Inline: False
```
**Symbols:**

```
ffffffff81117e80-ffffffff81118594: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111f830)
Location: kernel/cgroup.c:2073
Inline: False
```
**Symbols:**

```
ffffffff8111f830-ffffffff8112003b: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81127c80)
Location: kernel/cgroup.c:2083
Inline: False
```
**Symbols:**

```
ffffffff81127c80-ffffffff811284a5: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811255b0)
Location: kernel/cgroup/cgroup.c:1833
Inline: False
```
**Symbols:**

```
ffffffff811255b0-ffffffff81125914: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131870)
Location: kernel/cgroup/cgroup.c:2011
Inline: False
```
**Symbols:**

```
ffffffff81131870-ffffffff81131be5: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113ffa0)
Location: kernel/cgroup/cgroup.c:2029
Inline: False
```
**Symbols:**

```
ffffffff8113ffa0-ffffffff8114030f: cgroup_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *cgroup_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ba10)
Location: kernel/cgroup/cgroup.c:2070
Inline: False
```
**Symbols:**

```
ffffffff8114ba10-ffffffff8114bd7f: cgroup_mount (STB_LOCAL)
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
