# Function: <code>cgroup1_mount</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *cgroup1_mount(struct file_system_type *fs_type, int flags, void *data, long unsigned int magic, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a820)
Location: kernel/cgroup/cgroup-v1.c:1061
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8112a820-ffffffff8112acc5: cgroup1_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *cgroup1_mount(struct file_system_type *fs_type, int flags, void *data, long unsigned int magic, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811375b0)
Location: kernel/cgroup/cgroup-v1.c:1120
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff811375b0-ffffffff81137a5b: cgroup1_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *cgroup1_mount(struct file_system_type *fs_type, int flags, void *data, long unsigned int magic, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1108
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81146357-ffffffff81146368: cgroup1_mount.cold.24 (STB_LOCAL)
ffffffff81145e60-ffffffff811462ee: cgroup1_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *cgroup1_mount(struct file_system_type *fs_type, int flags, void *data, long unsigned int magic, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1115
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81151efb-ffffffff81151f0c: cgroup1_mount.cold.24 (STB_LOCAL)
ffffffff81151a20-ffffffff81151e92: cgroup1_mount (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
