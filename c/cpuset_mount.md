# Function: <code>cpuset_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111b1d0)
Location: kernel/cpuset.c:304
Inline: False
```
**Symbols:**

```
ffffffff8111b1d0-ffffffff8111b2bd: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff811230b0)
Location: kernel/cpuset.c:304
Inline: False
```
**Symbols:**

```
ffffffff811230b0-ffffffff8112319d: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112b050)
Location: kernel/cpuset.c:304
Inline: False
```
**Symbols:**

```
ffffffff8112b050-ffffffff8112b13d: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112c7d0)
Location: kernel/cgroup/cpuset.c:307
Inline: False
```
**Symbols:**

```
ffffffff8112c7d0-ffffffff8112c8bd: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81139600)
Location: kernel/cgroup/cpuset.c:318
Inline: False
```
**Symbols:**

```
ffffffff81139600-ffffffff811396f3: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81147de0)
Location: kernel/cgroup/cpuset.c:318
Inline: False
```
**Symbols:**

```
ffffffff81147de0-ffffffff81147ed3: cpuset_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *cpuset_mount(struct file_system_type *fs_type, int flags, const char *unused_dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811539c0)
Location: kernel/cgroup/cpuset.c:375
Inline: False
```
**Symbols:**

```
ffffffff811539c0-ffffffff81153ab3: cpuset_mount (STB_LOCAL)
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
