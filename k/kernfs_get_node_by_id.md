# Function: <code>kernfs_get_node_by_id</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcf70)
Location: fs/kernfs/mount.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff812fcf70-ffffffff812fcfa0: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132ab70)
Location: fs/kernfs/mount.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff8132ab70-ffffffff8132aba1: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81341ec0)
Location: fs/kernfs/mount.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff81341ec0-ffffffff81341ef1: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a2e0)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff8136a2e0-ffffffff8136a311: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813824d0)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff813824d0-ffffffff81382501: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff8000104508e0)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffff8000104508e0-ffff800010450948: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c06138c8)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
c06138c8-c0613918: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c000000000568af0)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
c000000000568af0-c000000000568b74: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e387e)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffe0002e387e-ffffffe0002e38d6: kernfs_get_node_by_id (STB_GLOBAL)
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
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137aab0)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff8137aab0-ffffffff8137aae1: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b580)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff8136b580-ffffffff8136b5b1: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81378580)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff81378580-ffffffff813785b1: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_node_by_id(struct kernfs_root *root, const union kernfs_node_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138c030)
Location: fs/kernfs/mount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
```
**Symbols:**

```
ffffffff8138c030-ffffffff8138c061: kernfs_get_node_by_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
