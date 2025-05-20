# Function: <code>kernfs_pin_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812889a0)
Location: fs/kernfs/mount.c:296
Inline: False
```
**Symbols:**

```
ffffffff812889a0-ffffffff81288a47: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b5e60)
Location: fs/kernfs/mount.c:312
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff812b5e60-ffffffff812b5f07: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb6f0)
Location: fs/kernfs/mount.c:313
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff812cb6f0-ffffffff812cb797: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d8b40)
Location: fs/kernfs/mount.c:313
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff812d8b40-ffffffff812d8bd9: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fd3a0)
Location: fs/kernfs/mount.c:384
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff812fd3a0-ffffffff812fd439: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132afe0)
Location: fs/kernfs/mount.c:385
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8132afe0-ffffffff8132b079: kernfs_pin_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *kernfs_pin_sb(struct kernfs_root *root, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81342350)
Location: fs/kernfs/mount.c:392
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff81342350-ffffffff813423e9: kernfs_pin_sb (STB_GLOBAL)
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
