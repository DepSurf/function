# Function: <code>kernfs_find_and_get_node_by_id</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf170)
Location: fs/kernfs/dir.c:709
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813cf170-ffffffff813cf1ed: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0da0)
Location: fs/kernfs/dir.c:708
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813e0da0-ffffffff813e0e1d: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e78d0)
Location: fs/kernfs/dir.c:708
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813e78d0-ffffffff813e794d: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814395e0)
Location: fs/kernfs/dir.c:667
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff814395e0-ffffffff8143965d: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4660)
Location: fs/kernfs/dir.c:675
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff814b4660-ffffffff814b46eb: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b560)
Location: fs/kernfs/dir.c:696
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff8154b560-ffffffff8154b5ec: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815831b0)
Location: fs/kernfs/dir.c:695
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff815831b0-ffffffff8158323c: kernfs_find_and_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_id(struct kernfs_root *root, u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbe00)
Location: fs/kernfs/dir.c:711
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff815bbe00-ffffffff815bbe8c: kernfs_find_and_get_node_by_id (STB_GLOBAL)
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
