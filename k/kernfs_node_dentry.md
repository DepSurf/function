# Function: <code>kernfs_node_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812885b0)
Location: fs/kernfs/mount.c:96
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff812885b0-ffffffff812886c1: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b5a50)
Location: fs/kernfs/mount.c:111
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff812b5a50-ffffffff812b5b80: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb2e0)
Location: fs/kernfs/mount.c:111
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff812cb2e0-ffffffff812cb410: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d8750)
Location: fs/kernfs/mount.c:111
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff812d8750-ffffffff812d885c: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcfd0)
Location: fs/kernfs/mount.c:184
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff812fcfd0-ffffffff812fd0dc: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:184
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff8132b079-ffffffff8132b091: kernfs_node_dentry.cold.8 (STB_LOCAL)
ffffffff8132abe0-ffffffff8132ace1: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:184
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff813423e9-ffffffff81342401: kernfs_node_dentry.cold.8 (STB_LOCAL)
ffffffff81341f30-ffffffff81342041: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8136a72e-ffffffff8136a746: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff8136a350-ffffffff8136a456: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8138290e-ffffffff81382926: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff81382540-ffffffff81382638: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff813cd02e-ffffffff813cd046: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff813ccd40-ffffffff813cce35: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81bec0b9-ffffffff81bec0d1: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff813de990-ffffffff813dea85: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81bde117-ffffffff81bde12f: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff813e55d0-ffffffff813e56c4: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81cc8591-ffffffff81cc85bd: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff814371a0-ffffffff814372a0: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1e20)
Location: fs/kernfs/mount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff814b1e20-ffffffff814b1f04: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81548950)
Location: fs/kernfs/mount.c:198
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81548950-ffffffff81548a34: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81580500)
Location: fs/kernfs/mount.c:198
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81580500-ffffffff815805e4: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b8f50)
Location: fs/kernfs/mount.c:205
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff815b8f50-ffffffff815b9034: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff800010450998)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffff800010450998-ffff800010450ad4: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c061394c)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
c061394c-c0613ab0: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c000000000568bc0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
c000000000568bc0-c000000000568de4: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e390c)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffe0002e390c-ffffffe0002e3a08: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8137aeee-ffffffff8137af06: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff8137ab20-ffffffff8137ac18: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8136b9be-ffffffff8136b9d6: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff8136b5f0-ffffffff8136b6e8: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff813789be-ffffffff813789d6: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff813785f0-ffffffff813786e8: kernfs_node_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *kernfs_node_dentry(struct kernfs_node *kn, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:172
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8138c46e-ffffffff8138c486: kernfs_node_dentry.cold (STB_LOCAL)
ffffffff8138c0a0-ffffffff8138c198: kernfs_node_dentry (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
